**Overview**:
This project aims to predict cancer mortality rates using two different machine learning models: Linear Regression and Deep Fully Connected Neural Networks (DNN). 
The dataset used includes various features aggregated from sources such as the American Community Survey, clinical trials, and cancer databases. 
The goal is to compare the performance of these models and understand how well they predict the "TARGET_deathRate."

The target label for prediction is "TARGET_deathRate".
The dataset contains multiple features, including demographics, health factors, and clinical trial data.

**Project Structure**
Linear Regression Model: A baseline model used to predict cancer mortality rates.
Deep Fully Connected Neural Networks (DNNs): Multiple architectures, including models with 2 to 4 hidden layers, were explored to predict mortality rates.

**Models Evaluated**
Linear Regression
DNN-16: Single hidden layer with 16 nodes.
DNN-30-8: Two hidden layers with 30 and 8 nodes respectively.
DNN-30-16-8: Three hidden layers with 30, 16, and 8 nodes.
DNN-30-16-8-4: Four hidden layers with 30, 16, 8, and 4 nodes.

**Technologies Used**
Python
TensorFlow/Keras (for building DNN models)
Scikit-learn (for linear regression)
Pandas and NumPy (for data handling)
Matplotlib and Seaborn (for visualization)
