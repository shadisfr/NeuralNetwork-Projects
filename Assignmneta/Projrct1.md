# Student Performance Prediction using PyTorch

This project involves predicting student performance using the Student Performance dataset. The dataset contains information about students' demographics, family background, and academic performance. The goal is to build a Multilayer Perceptron (MLP) model using PyTorch to accurately predict students' performance.

## Dataset Description

The Student Performance dataset contains the following columns:

- `school`
- `sex`
- `age`
- `address`
- `famsize`
- `Pstatus`
- `Medu`
- `Fedu`
- `Mjob`
- `Fjob`
- `reason`
- `guardian`
- `traveltime`
- `studytime`
- `failures`
- `schoolsup`
- `famsup`
- `paid`
- `activities`
- `nursery`
- `higher`
- `internet`
- `romantic`
- `famrel`
- `freetime`
- `goout`
- `Dalc`
- `Walc`
- `health`
- `absences`
- `G1` (First period grade)
- `G2` (Second period grade)
- `G3` (Final grade)

## Tasks

### 1. Data Loading and Preprocessing

- Download the Student Performance dataset from the appropriate source.
- Load the dataset using Pandas or any other suitable library.
- Perform necessary preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features.

### 2. Data Splitting

- Split the dataset into training and testing sets. Use a suitable ratio (e.g., 80% training, 20% testing) to ensure an adequate amount of data for training and evaluation.

### 3. Model Implementation with PyTorch

- Implement a Multilayer Perceptron (MLP) model using PyTorch to predict student performance.
- Design the architecture of the MLP model, including the number of input nodes, hidden layers, neurons per layer, and output nodes.
- Experiment with different activation functions, dropout layers, and regularization techniques to improve model performance.

### 4. Training the MLP Model

- Train the MLP model using the training data. Utilize techniques such as mini-batch gradient descent and backpropagation to update the model parameters iteratively.
- Monitor training progress by tracking metrics such as loss and accuracy on both training and validation sets.

### 5. Model Evaluation

- Evaluate the performance of the trained MLP model using the testing data.
- Calculate relevant evaluation metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared to assess the model's predictive performance.

### 6. Analysis and Interpretation

- Analyze the results of the MLP model and interpret its predictions.
- Identify factors that significantly influence student performance based on feature importance or coefficients from the model.
- Discuss potential interventions or strategies for improving student performance based on the analysis.

## Dataset Link

You can download the dataset from the following link: [Student Performance Dataset](https://www.kaggle.com/datasets/larsen0966/student-performance-data-set)
