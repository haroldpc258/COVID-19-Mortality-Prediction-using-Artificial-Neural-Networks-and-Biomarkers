# **COVID-19 Mortality Prediction using Neural Networks and Biomarkers**
This Python project leverages artificial neural networks to predict COVID-19-related mortality based on biomarkers. 
The project involves the comprehensive analysis of a dataset containing information from both deceased and surviving COVID-19 patients.
The dataset was preprocessed and explored in two variations: one with the original data and the other with scaled data. Principal Component Analysis (PCA) was subsequently 
applied to both versions, resulting in four distinct database versions: original data, original data with PCA, scaled data, and scaled data with PCA.

The core of the project centers around the design and implementation of an artificial neural network, which was trained and evaluated using a 70-30 split for training and testing.
A comprehensive set of accuracy metrics, including a confusion matrix, was computed to assess the model's performance.

## Key Features and Components:

1. **Data Preprocessing and Exploration:** Gain insights into the initial dataset, understand its features, and handle any missing or inconsistent data.
Explore the distribution of biomarkers and relevant variables to identify patterns and potential correlations.

2. **PCA Transformation:** Witness the power of Principal Component Analysis as it reduces dimensionality and captures the most significant variations in the data.
Compare and contrast the effects of PCA on both the original and scaled versions of the dataset.

3. **Neural Network Architecture:** Delve into the heart of the project, where an artificial neural network is meticulously designed to learn complex relationships
between biomarkers and COVID-19 mortality. Understand the network's layers, activation functions, and optimization techniques.

4. **Data Split and Training:** Discover the process of dividing the dataset into a 70-30 ratio for training and testing the neural network.
Gain insights into the training procedure, including hyperparameter tuning and convergence analysis.

5. **Performance Metrics:** Learn about the array of accuracy metrics employed to assess the predictive capabilities of the neural network.
Explore the intricacies of precision, recall, F1-score, and the generation of a comprehensive confusion matrix.

6. **Interpretability and Visualization:** Visualize the model's predictions and explore its decision-making process. Gain insights into which biomarkers play a crucial role
in predicting COVID-19 mortality.

