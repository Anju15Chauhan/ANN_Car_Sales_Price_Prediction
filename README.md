# Car Sale Price Prediction using Artificial Neural Network (ANN)
![images](https://github.com/user-attachments/assets/82829cf9-5910-401a-82bc-92ca92060e7d)



## Project Overview

This project aims to predict car sale prices using an Artificial Neural Network (ANN). By leveraging customer data and vehicle information, the model provides accurate price predictions, which can help businesses and individuals make informed decisions.

### Dataset

The dataset used for this project includes the following features:

* **Customer Information:**

  * Gender

  * Age

  * Annual Salary

  * Credit Card Debt

  * Net Worth

* **Target Variable:**

  * Car Purchase Amount (price paid for the car)

## Project Steps

### **1. Data Preprocessing**

* **Dropped Irrelevant Columns:** Removed customer name and customer e-mail.

* **Handled Categorical Variables:** Applied one-hot encoding to the country column.

* **Feature Scaling:** Used Min-Max Scaling to normalize numerical features.

### **2. Model Building**

* **Input Features:** Prepared scaled input data with one-hot encoded features.

* **ANN Architecture:**

   * **Input Layer:** 128 neurons with ReLU activation.

   * **Hidden Layer:** 64 neurons with ReLU activation.

   * **Output Layer:** 1 neuron with linear activation (for regression).

### **3. Model Training**

   * **Optimizer:** Adam

   * **Loss Function:** Mean Squared Error

   * **Metric:** Mean Absolute Error

   * Trained the model for 50 epochs with a batch size of 32 and a validation split of 20%.

### 4. Model Evaluation

  * **Loss Metrics:**

    * Training Loss and Validation Loss decreased steadily, indicating effective learning and good generalization.

  * **Test Metrics:**

    * Evaluated model performance on unseen test data using MAE and MSE.

### Key Results

* The model achieved a low Mean Absolute Error, indicating accurate predictions of car sale prices.

* Both training and validation losses steadily decreased over epochs, confirming that the model learned effectively without overfitting.

