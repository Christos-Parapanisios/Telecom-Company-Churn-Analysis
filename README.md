# Telecom-Company-Churn-Analysis

### Problem Statement
A Telecom company is very concerned about its customers discontinuing the service and opting to move to the one provided by the competitors. It is a major phenomenon is several service industries and is called ‘Churn’. The company thinks that there are early indications available in the way a customer uses its service in predicting whether he/she is likely to churn.

### Dataset
The dataset is about telecom industry which tells about the number of customers who churned the service. It consists of 3333 observations having 21 variables. We have to predict which customer is going to churn the service.

### Methodology
In this case study I approached the dataset as if it were stored in an HDFS cluster combining Spark with essential Python libraries for data manipulation, visualization, and Exploratory Data Analysis (EDA).
To apply basic Python libraries such as Pandas, Matplotlib, and Seaborn, I partitioned the dataset. This mimics the process that would be required for handling very large datasets. After preparing the data I built machine learning classification models such as Decision Tree, Random Forest, and Gradient-Boosted Trees using PySpark to predict customer churn.

### Why I Chose to Use Google Colab
Google Colab provides a free and convenient environment for exploring and practicing with PySpark. While this case study involves a relatively small dataset, Colab allows me to simulate the approach I would use for processing large datasets in a distributed environment like HDFS.
PySpark integrates seamlessly with machine learning libraries such as TensorFlow and Scikit-learn, enabling smooth transitions from data processing to model training. I can also test smaller data samples using Pandas for initial analysis and efficiently manage memory throughout the process. This workflow helps me build complete data pipelines, gain hands-on experience with scalable data processing, and prepare for working with big data systems.
