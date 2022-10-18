# I310D-bias
**CONTENT WARNING: both `bias_analysis.ipynb` and `labeled_and_scored_comments.csv` contain abusive and derogatory language.**
### Purpose
The purpose of this project is to test the Perspective model for bias.
### Hypothesis
Slurs against the European group will have a lower average `identity_hate` score than those against African, Asian, and Native American groups.
### Methodology
To test this hypothesis, I selected slurs and epithets from [Wikipedia](https://en.wikipedia.org/wiki/List_of_ethnic_slurs_and_epithets_by_ethnicity) with certain omission conditions. I then filtered out the ones that didn't work in API queries before analysis. `bias_analysis.ipynb` goes further into detail on how this was done.
### Results
The Perspective model did score slurs against European people lower on average than those against the other groups. Other findings upon deeper analysis include concerning false negatives.
### Personal Bias
Notably, my analysis of the API's response is subjective to my experiences as a white American. While I actively put in effort to understand the experiences of minority groups in America, that is not the same as living through them. As such, there may be nuances and implications I've missed in my analysis.
