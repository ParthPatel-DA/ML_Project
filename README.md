# ML Final Project

## Team Members

| S. No | Name           |
| ----- | -------------- |
| 1     | Parth Patel    |
| 2     | Kishan Patel   |
| 3     | Rajkumar Bhuva |

## Project Links

Code Link:
https://colab.research.google.com/drive/1J3REJGF2sTa_Fw4-KP8Y4MbXP78iWBLn?usp=sharing

Readable Link:
https://notebooks.githubusercontent.com/view/ipynb?browser=chrome&bypass_fastly=true&color_mode=auto&commit=4cfd41d558b18264fba255f149a2ef38e5c34c58&device=unknown_device&docs_host=https%3A%2F%2Fdocs.github.com&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f506172746856174656c2d44412f4d4c5f50726f6a6563742f346366643431643535386231383236346662613235356631343961326566333865356333346335382f50726f6a6563742e6970796e62&logged_in=true&nwo=ParthPatel-DA%2FML_Project&path=Project.ipynb&platform=mac&repository_id=729930852&repository_type=Repository&version=119#027d71c0-07dc-4bb2-b514-cdb7560fbc1d

## Outline

The project involves the analysis of a dataset containing information on the cost of living in various regions of the United States. Through data exploration, visualization, and preprocessing, key features influencing economic stability are identified. The dataset is then used to train and evaluate machine learning models, including Logistic Regression, SGD Classifier, SVC, Decision Tree, Random Forest, MLP Classifier and Artificial Neural Network, to predict an economic stability category. The models are assessed based on accuracy metrics and classification reports. The project aims to provide insights into the factors impacting the cost of living in different areas and offers a practical application of machine learning for predictive analysis in understanding economic dynamics.

## Observation

Initial Data Exploration: The dataset includes features such as median family income, housing cost, food cost, and others. Initial exploration involved understanding the distribution of these features and checking for missing values.

Data Exploration and Visualization: The script begins with a comprehensive exploration of the dataset, providing insights into the distribution of various cost factors contributing to the Economic Stability Categories. Visualizations, such as histograms, box plots, and correlation matrices, are employed to better understand the relationships between different variables.

Feature Engineering: The script implements feature engineering techniques to enhance the predictive capabilities of the machine learning models. Interaction terms and other transformations are considered to capture relationships in the data.

Model Development and Evaluation: Several machine learning models, including Logistic Regression, SGD Classifier, SVC, Decision Tree, Random Forest, MLP Classifier, and Artificial Neural Networks, were trained and evaluated. The models were assessed based on their accuracy and the classification reports.

Evaluation Metrics: Multiple evaluation metrics, including accuracy, precision, recall, and F1-score, are employed. This holistic approach to evaluation ensures a nuanced understanding of the models' performance, considering both false positives and false negatives.

Model Comparison: A comparative analysis of the models is conducted, highlighting their strengths and weaknesses in predicting economic stability. MLP Classifier and Artificial Neural Networks emerge as top performers, showcasing potential for precise Economical Stabilities Categories predictions.

ESI Categorization: The ESI values were categorized into groups such as 'very low', ‘low’, 'moderate', ‘high’, and, 'very high' using different statistical methods like K-Means clustering and IQR-based categorization.

Practical results
The output observed from the execution of the model is as follows:

| S. No | Model Name          | Accuracy |
| ----- | ------------------- | -------- |
| 1     | Logistic Regression | 94.19    |
| 2     | SGD                 | 82.59    |
| 3     | SVC                 | 98.02    |
| 4     | Decision Tree       | 94.36    |
| 5     | Random Forest       | 96.32    |
| 6     | MLP Classifier      | 99.30    |
| 7     | ANN                 | 98.91    |

## Distinguishing Our Project from Previous Kaggle Initiatives

The works done on Kaggle do not include the machine learning model training, evaluation, and prediction of the Economic Stability category. The project we have implemented has the use of various machine learning models, and the evaluation metrics and classification reports are not part of the work done on Kaggle.
In summary, the works done on the Kaggle are a subset of the entire project, focusing on the initial data exploration and visualization steps.

## Conclusion

In conclusion, the script presents a thorough analysis of the cost of living in the United States, employing a diverse set of machine learning models to predict the Economic Stability Category. Through extensive data exploration and visualization, key insights into the distribution of costs, regional variations, and demographic factors influencing economic stability are uncovered. The models, including Logistic Regression, Decision Tree Classifier, and Neural Networks, demonstrate varying degrees of accuracy in predicting ES categories. Notably, the MLP Classifier and Artificial Neural Networks exhibit superior performance, showcasing their potential for precise ESI predictions. Despite the success, continuous refinement, hyperparameter tuning, and monitoring for model generalization are recommended for enhancing predictive capabilities.
The project demonstrates a systematic approach to analyzing economic stability, employing advanced machine learning techniques for accurate predictions and offering valuable insights into the factors influencing regional economic conditions.
