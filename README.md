<h1 align="center">Classifying Cybersecurity Incidents</h1>

![GitHub repo size](https://img.shields.io/github/repo-size/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?color=red&style=plastic)

## 📖Project Description 

Imagine you are working as a data scientist at Microsoft, tasked with enhancing the efficiency of Security Operation Centers (SOCs) by developing a machine learning model that can accurately predict the triage grade of cybersecurity incidents. Utilizing the comprehensive GUIDE dataset, your goal is to create a classification model that categorizes incidents as true positive (TP), benign positive (BP), or false positive (FP) based on historical evidence and customer responses. The model should be robust enough to support guided response systems in providing SOC analysts with precise, context-rich recommendations, ultimately improving the overall security posture of enterprise environments.

You need to train the model using the train.csv dataset and provide evaluation metrics-macro-F1 score, precision, and recall-based on the model's performance on the test.csv dataset. This ensures that the model is not only well-trained but also generalizes effectively to unseen data, making it reliable for real-world applications.

## 📁Data Set Overview:

 Weprovide three hierarchies of data: (1) evidence, (2) alert, and (3) incident. At the bottom level, evidence supports an alert. For example, an alert may be associated with multiple pieces of evidence such as an IP address, email, and user details, each containing specific supporting metadata. Above that, we have alerts that consolidate multiple pieces of evidence to signify a potential security incident. These alerts provide a broader context by aggregating related evidences to present a more comprehensive picture of the potential threat. At the highest level, incidents encompass one or more alerts, representing a cohesive narrative of a security breach or threat scenario. 
 
 The primary objective of the dataset is to accurately predict incident triage grades—true positive (TP), benign positive (BP), and false positive (FP)—based on historical customer responses. To support this, we provide a training dataset containing 45 features, labels, and unique identifiers across 1M triage-annotated incidents. We divide the dataset into a train set containing 70% of the data and a test set with 30%, stratified based on triage grade ground-truth, OrgId, and DetectorId. We ensure that incidents are stratified together within the train and test sets to ensure the relevance of evidence and alert rows.

## 📂Data Set Explanation:

 The GUIDE dataset contains records of cybersecurity incidents along with their corresponding triage grades (TP, BP, FP) based on historical evidence and customer responses. Preprocessing steps may include:
 - **Handling Missing Data:** Identifying and addressing any missing values in the dataset.
 - **Feature Engineering:** Creating new features or modifying existing ones to improve model performance, such as combining related features or encoding categorical variables.
 - **Normalization/Standardization:** Scaling numerical features to ensure that all input data is on a similar scale, which can be important for certain machine learning models.
-  Dataset Link : [**Datasets**](https://www.kaggle.com/datasets/Microsoft/microsoft-security-incident-prediction?select=GUIDE_Test.csv)

<h3 align="center">Developed By - Avijit Jana</h3>