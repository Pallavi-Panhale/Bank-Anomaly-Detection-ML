# Bank-Anomaly-Detection-ML
Developed a Machine Learning–based anomaly detection model to identify fraudulent bank transactions. The model analyzes transactional patterns to detect outliers, enabling proactive fraud prevention. Implemented using Python with the Credit Card Fraud Detection Dataset from Kaggle.

# Bank Anomaly Detection System using Machine Learning

This project focuses on detecting **fraudulent bank transactions** using machine learning algorithms.  
Traditional rule-based methods often fail to catch new fraud tactics, so this ML-based system proactively identifies suspicious patterns and anomalies in transaction data.

##  Objective
To develop an intelligent ML-based anomaly detection system capable of identifying potential fraudulent transactions in banking datasets through efficient pattern recognition and clustering algorithms.
##  Algorithms Used

### 1.Isolation Forest
- Detects anomalies by isolating data points through random partitioning.
- Anomalies require fewer splits to isolate, making them easier to detect.

### 2.Local Outlier Factor (LOF)
- Measures the local density deviation of a data point compared to its neighbors.
- Detects anomalies even when the data density varies across regions.

### 3.DBSCAN (Density-Based Spatial Clustering)
- Groups data points based on density.
- Points that don’t belong to any cluster are treated as outliers or anomalies.
- 
##  Dataset Information

- **Dataset Name:** [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Source:** Kaggle
- **Description:**  
  This dataset contains transactions made by European cardholders in September 2013.  
  It includes **284,807 transactions**, with **492 frauds** (0.172%).  
  Each transaction has numerical input features obtained through PCA transformation, and the target variable indicates whether the transaction is fraudulent (`1`) or not (`0`).


##  Technologies Used
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Platform:** Jupyter Notebook / Google Colab  
- **Dataset:** Kaggle – Credit Card Fraud Detection Dataset

## Project Workflow

1. **Data Preprocessing**
   - Load and clean the dataset.
   - Handle missing values and normalize data.

2. **Feature Selection & Scaling**
   - Apply PCA or scaling methods to improve accuracy.

3. **Model Training**
   - Train models using Isolation Forest, LOF, and DBSCAN.

4. **Evaluation**
   - Compare models using accuracy, precision, recall, and F1-score.

5. **Visualization**
   - Plot anomalies vs. normal transactions for interpretability.

## Output & Results
- Successfully identified fraudulent transactions from the dataset.  
- Isolation Forest and LOF achieved better detection performance compared to DBSCAN.  
- Visualized clusters and anomalies using 2D plots.

##  Conclusion
Machine Learning-based anomaly detection helps banks combat fraudulent activities effectively.  
By leveraging algorithms like **Isolation Forest** and **LOF**, the system detects abnormal transactions early, minimizes risks, and enhances financial security.


