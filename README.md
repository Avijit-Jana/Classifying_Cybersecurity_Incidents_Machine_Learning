<h1 align="center">👨‍💻Classifying Cybersecurity Incidents👨‍💻</h1>

![GitHub repo size](https://img.shields.io/github/repo-size/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/Avijit-Jana/Classifying_Cybersecurity_Incidents_Machine_Learning?color=red&style=plastic)

## 📖Project Description 

This is a Data Science Project to enhance the efficiency of Security Operation Centers (SOCs) by developing a machine learning model that can accurately predict the triage grade of cybersecurity incidents. Utilizing the comprehensive dataset, the goal is to create a classification model that categorizes incidents as true positive (TP), benign positive (BP), or false positive (FP) based on historical evidence and customer responses. The model should be robust enough to support guided response systems in providing SOC analysts with precise, context-rich recommendations, ultimately improving the overall security posture of enterprise environments.

## 📁Data Set Overview:

 There are three hierarchies of data: (1) evidence, (2) alert, and (3) incident. At the bottom level, evidence supports an alert. For example, an alert may be associated with multiple pieces of evidence such as an IP address, email, and user details, each containing specific supporting metadata. Above that, we have alerts that consolidate multiple pieces of evidence to signify a potential security incident. These alerts provide a broader context by aggregating related evidences to present a more comprehensive picture of the potential threat. At the highest level, incidents encompass one or more alerts, representing a cohesive narrative of a security breach or threat scenario. 
 
 The primary objective of the dataset is to accurately predict incident triage grades—true positive (TP), benign positive (BP), and false positive (FP)—based on historical customer responses. To support this, we provide a training dataset containing 45 features, labels, and unique identifiers across 1M triage-annotated incidents. We divide the dataset into a train set containing 70% of the data and a test set with 30%, stratified based on triage grade ground-truth, OrgId, and DetectorId. We ensure that incidents are stratified together within the train and test sets to ensure the relevance of evidence and alert rows.

- You can download the datasets from here : [**Datasets**](https://www.kaggle.com/datasets/Microsoft/microsoft-security-incident-prediction?select=GUIDE_Test.csv)

<h3 align="center">Developed By - Avijit Jana</h3>