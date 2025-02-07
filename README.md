# Neural-Networks

o Situation: Predicting risk of heart attacks in both the genders considering underlying health factors and surrounding parameters.

o Task: Predicting heart disease rate based on given set of data using machine learning algorithms and perform model evaluation.

o Action: PCA analysis to get suitable data, created ML models based on Random Forest and using Neural networks predictions were performed

o Result: The Neural network model scores at 77% of accuracy, indicating reasonably good predictive performance


PCA effectively reduces dimensionality while retaining some information about class separability. 

The first two components explain about 33% of the variance, but more components may be required for improved representation. The visualization suggests that additional features or nonlinear methods might be needed for more robust classification.

Naive Bayes provides slightly better accuracy and F1-scores, making it a strong general-purpose choice.

Random Forest has a competitive ROC AUC score, indicating its strength in decision-making, especially in more complex or high-dimensional datasets.

Model Evaluation: Given the balanced nature of the problem (equal importance of identifying "Disease" and "No Disease"), Naive Bayes is marginally more favorable due to its overall performance consistency. However, Random Forest can be an excellent alternative with further tuning or in scenarios prioritizing class separation.

Conclusion: The neural network performed well, achieving a good accuracy in predicting heart disease.

The model achieved an overall accuracy of 77%, indicating reasonably good predictive performance.

For class 0 (no heart disease):
- Precision: 79%, Recall: 68%, F1-Score: 73%.
For class 1 (heart disease):
- Precision: 76%, Recall: 85%, F1-Score: 80%.
- 
The model performs better at identifying heart disease cases (recall = 85%) than detecting the absence of heart disease


Skills: Python (Programming Language) · Data Analytics · Random Forest · Principal Component Analysis · Neural Networks · Machine Learning
