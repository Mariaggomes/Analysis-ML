# **Machine Learning Analyses** 

This directory contains implementations of **machine learning** algorithms applied to various classification and prediction problems.

## **Overview of Codes**:

### 1. `Tanh3_NeuralNetwork`
   - **Purpose**: Predict the **next day’s temperature** based on atmospheric and temporal variables from air quality data.
   - **Description**: Uses a **neural network with *tanh* activation** to capture temporal dependencies, creating lagged variables (temperature, relative and absolute humidity) to aid in prediction.
   - **Highlights**:
     - Training with different numbers of hidden neurons.
     - **Early Stopping** implementation to prevent overfitting.
     - High performance with an R² coefficient of 94%, indicating excellent predictive ability.
   - **Algorithm**: Neural Network (*tanh* activation).

---

### 2. `SVM`
   - **Purpose**: Classify whether the **"Y" medication** should be prescribed based on patient health data.
   - **Description**: Applies the **SVM algorithm** to predict if a patient should receive the "Y" medication, based on characteristics such as **sodium-potassium levels**, **blood pressure**, and **cholesterol**.
   - **Highlights**:
     - Hyperparameter tuning using **RandomizedSearchCV** to optimize the SVM.
     - Comparison of kernels: **RBF**, **sigmoid**, **linear**.
     - Evaluation using precision and F1-score metrics.
   - **Algorithm**: **Support Vector Machine (SVM)**.

---

### 3. `NeuralClassifier`
   - **Purpose**: Classify the species **Iris-versicolor** using a neural network.
   - **Description**: A classic classification problem where a **neural network** is trained to identify the **Iris-versicolor** species based on petal length and width.
   - **Highlights**:
     - Training with different hidden neuron configurations (1 to 4).
     - Comparison between **Adam** and **RMSprop** optimizers.
     - Performance visualization with **ROC curves** and a confusion matrix.
   - **Algorithm**: **Neural Network** with Adam and RMSprop optimizers.

---

### 4. `Kmeans`
   - **Purpose**: Perform **chocolate segmentation** based on characteristics such as origin and cocoa content.
   - **Description**: Applies **K-Means** to cluster chocolates, identifying patterns and trends among different varieties.
   - **Highlights**:
     - Segmenting chocolates by characteristics such as **bean type**, **cocoa percentage**, and **origin**.
     - Cluster evaluation and quality analysis.
     - Visualizations to understand the distribution and the formed groups.
   - **Algorithm**: **K-Means** (unsupervised clustering).

## Author
This project was developed by Maria Gabriela Gomes. For more information or to connect, please visit my [LinkedIn profile](https://www.linkedin.com/in/maria-gabriela-gomes-27097431b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app).
