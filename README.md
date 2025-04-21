## Credit-Card-Fraud-Detection-System

### Motivation
The increasing digital transactions and sophisticated fraud techniques necessitate a robust fraud detection system, motivating this project to leverage advanced machine learning for enhanced accuracy and reliability in credit card fraud prevention.

My motivation stems from the desire to protect consumers from financial loss and to support financial institutions in mitigating risks associated with fraudulent transactions. By developing a comprehensive credit card fraud prevention system, we can significantly reduce the occurrence of fraud, ensuring a safer and more secure transaction environment. The project's success will not only contribute to financial security but also build greater trust in digital payment systems.

### Methodology
<div style="text-align: center;">
 <img src='workflow.png' width="700" height="300" align="center">
 <br><br>
 End-To-End Fraud Prevention System Workflow Schema
</div>

1. [Data Overview](#Data-Overview)
<br><br>
You can download the data from https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions. 
- Understanding unbalanced data and converting class into factors<br><br>
Content:<br><br>
The dataset presents an extensive collection of around 24.4 million credit card transactions, sourced from IBM's financial database. Capturing a wide spectrum of user interactions, the data provides a detailed snapshot of transaction behaviors, patterns, and potential vulnerabilities.

2. [Data Preprocessing](#Data-Preprocessing)

- Fixing inconsistencies and missing values to keep the data clean, and remove redundancies for accuracy.

- [Scaling & Distributing](#Scaling-&-Distributing)

3. [Exploratory Data Analysis](#Exploratory-Data-Analysis)

- [Fraud Dataset](#Fraud-Dataset)<br><br>
    - [Card Distribution](#Card-Distribution)<br>

    - [Time Distribution](#Time-Distribution)<br><br>
    *Time Variation*: The distribution of fraud cases displays distinct time variations
        - [Year](#Year)
        - [Month](#Month)
        - [Day of Month](#Day-of-Month)
        - [Day of Week](#Day-of-Week)
        - [Hour](#Hour)

    - [Amount Distribution](#Amount-Distribution)<br>
    
    - [Geographical Distribution](#Geographical-Distribution)<br>
        - [State](#State)<br>
        - [City](#City)<br>

    - [Transaction Method](#Transaction-Method)<br><br>
    *Transaction Amount*: Fraud is predominantly observed in transactions of smaller values<br>

    - [Checking Outliers](#Checking-Outliers)<br>

4. [ML Model Optimization](#ML-Model-Optimization)

    Implementing Logistic Regression on three sampling methods which are undersampling, oversampling and SMOTE<br><br>
    Improve Logistic Results using Decision Tree & Random Forest on SMOTE<br><br>
    Implementing ANN (Artificial Neural Network)<br><br>
    Evaluation of model results using Performance Metrics (Recall, Precision and F1score, AUC-ROC)<br><br>
    Displaying Performance Reports<br><br>

5. [Insights](#Insights)

    Exploratory Data Analysis showed that some variables have significant impact on the fraud rate such as time, amount and transaction method, so I incorporated them into the predictive models.<br>

### Models Comparison
- Please refer to the Jupyter notebook Fraud_Detection_Report.ipynb for model comparison details.