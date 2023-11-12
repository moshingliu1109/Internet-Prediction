# Internet-Prediction with Titanic Competition

This repository uses machine learning to create a model that predicts which passengers survived the Titanic shipwreck. The goal of this was to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data.

## Dataset
The dataset for this analysis can be downloaded 
[train](https://github.com/moshingliu1109/Internet-Prediction/blob/main/train.csv).
[test](https://github.com/moshingliu1109/Internet-Prediction/blob/main/test.csv).

## Context

### Pre-processing

•	Ticket names were divided into sections, and passenger names were tokenized.
•	Transformations were applied to the dataset, resulting in additional columns like "Ticket_number" and "Ticket_item".

### Model Training

•	Initially, a GBT model was trained using default parameters.
•	Subsequently, the model was trained again using specific parameters.

### Model Summary

•	The model used is named "gradient_boosted_trees_model_2".
•	The model type is "GRADIENT_BOOSTED_TREES" and it's designed for classification tasks.
•	The model's architecture, including the number of parameters, layers, and other details, is given in the `model.summary()` output.

### Key Insights

The document emphasizes the importance of variables in the model, suggesting that some variables significantly influence predictions. However, specific details on variable importance were not extracted from the provided content.

### Recommendations

For a deeper understanding and evaluation of the model's performance, consider:
-	Reviewing variable importance details to identify key predictors.
-	Evaluating the model's accuracy, precision, recall, and other metrics.
-	Conducting a feature importance analysis to understand the relative importance of each variable in the model's predictions.

## Slides and Appendix

Please refer to the attached [report](https://github.com/moshingliu1109/Internet-Prediction/blob/main/Muxin%20Liu_%E4%BA%92%E8%81%94%E7%BD%91%E9%A2%84%E6%B5%8B%E9%A1%B9%E7%9B%AE_1020.pdf) for a summary of the findings and recommendations. 

Thank you for your interest in this internet prediction analysis. Should you have any further questions or require additional information, please feel free to reach out to us.

