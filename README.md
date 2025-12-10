📌 Flow Stress Prediction using Artificial Neural Network (ANN) =>
This project builds an Artificial Neural Network (ANN) model to predict Flow Stress based on:
- Strain
- Strain rate
- Deformation temperature
The model is trained using processed features created from physical metallurgical relationships.

1. Project Overview =>
- Data preprocessing
- Feature engineering
- ANN model building using Keras
- Hyperparameter tuning (neuron search)
- Model evaluation (R², MAE, RMSE)
Export of trained model to JSON Matrix (for external use).

2. Model Evaluation =>
Metrics used:-
- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
Plots generated:-
- Predicted vs Experimental Flow Stress
- Flow Stress vs Strain
- Flow Stress vs Temperature
- 5% Error Bands plot

Objective =>
(1) To fabricate an ANN model using trial-and-error method.
(2) To predict flow stress using the same ANN model.
(3) To validate the experimental data using the developed ANN model.
(4) To predict flow stress for unknown combinations of parameters using ANN architecture.

