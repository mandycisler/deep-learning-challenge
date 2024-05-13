# deep-learning-challenge
## Overview:
The purpose of this analysis is to develop a binary classifier to assist Alphabet Soup, a nonprofit foundation, in selecting funding applicants. The goal is to predict the success of applicants if funded by Alphabet Soup.

## Data Preprocessing:
Target variable(s) for the model: IS_SUCCESSFUL.
Feature variable(s) for the model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
Variables removed from input data: EIN and NAME.

## Compiling, Training, and Evaluating the Model:
The initial model configuration included two layers with a relu and sigmoid activation function. Subsequently, the model architecture was enhanced by adding a third layer.
Despite optimization efforts, the target model performance of 75% accuracy was not achieved. Steps taken to improve model performance included incorporating Name as a feature, binning its values, and retaining Classification as a feature. Additionally, the model was augmented by adding a third layer.

## Summary:
In summary, the deep learning model did not meet the target performance threshold. To address this classification problem, a different model approach may be warranted. For instance, employing a Random Forest or Gradient Boosting classifier could offer better performance by leveraging ensemble learning techniques and handling non-linear relationships more effectively.
