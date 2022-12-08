# Module 19 Challenge

## Overview of the loan prediction risk analysis:
The aim of this project is to use Machine Learning and Neural Networks to build a binary classifier that can predict whether an applicant will be successful if they receive funding from Alphabet Soup. The classifier will be trained on a dataset containing 34000 past applications that have been funded by Alphabet Soup. The dataset includes information about the applicant's affiliated industry, government classification, type of organization, income amount, special considerations, amount of funding requested, active status, and success status.


## Results
## Data Preprocessing

-   The target/dependent column will be the ‘IS_SUCCESSFUL’ column. The model will predict whether the nonprofit will be successful based on the independent/feature columns.
-   The features/independent columns are ‘APPLICATION_TYPE’, ‘AFFILIATION’, ‘CLASSIFICATION’, ‘USE_CASE’, ‘ORGANIZATION’, ‘STATUS’, ‘INCOME_AMT’, ‘SPECIAL_CONSIDERATIONS’, ‘and ‘ASK_AMT’
-   The columns which would make no impact on the target are the ‘EIN’ and ‘NAME’ columns
## Summary
The deep learning model was unable to accurately predict the success of Alphabet Soup applicants, achieving only 73.03% accuracy, which is below the target of 75%. Although this level of accuracy may be sufficient in some cases, for Alphabet Soup's purposes, it is not sufficient. The model shows promise as a starting point for making predictions, but it will need to be adjusted in order to improve its accuracy and provide better results for Alphabet Soup.
