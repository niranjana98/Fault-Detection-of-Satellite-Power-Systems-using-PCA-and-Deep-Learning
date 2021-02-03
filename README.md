# Fault Detection of Satellite Power Systems using Deep Learning

## Link to Publication

http://sersc.org/journals/index.php/IJAST/article/view/16367

## Abstract:
Fault detection and diagnosis is one of the key technologies for monitoring the functions of power systems in satellites. In this project, we use Principal Component Analysis to identify the features in the data and Deep Neural Network to diagnose the faults. This method is then compared with other Machine Learning Classifiers like SVM and MLP. Usually a classifier trains faulty data to identify the causes of the anomalies and this aspect has generally limited the use of model-driven approaches to fault detection tasks. The proposed method is more suitable for characterizing complex features of equipment information, allowing for more accurate identification of equipment health status under complex monitoring tasks. Here, the dataset used is acquired from the Advanced Diagnostic and Prognostic Testbed (ADAPT) from NASA. It mimics the Power System of a satellite in the form of Electrical Power system that consists of numerous sensors and components and the readings of the sensors under fault and no-fault conditions are obtained.

## Dataset:
The ADAPT is a test bed developed by NASA Ames and Research Centre to act as a benchmark or testing and verification tool. All data samples in the datasets are viewed as a list of faults and under normal conditions, including all sensor data collected across a time period at various frequencies, spanning the length of the particular injection of fault. The datasets consist of multiple experiments in Multivariant Time Series with many types of sensors. The types of sensors have different notations. For instance, the Relay sensor is notified as EY, Voltage Sensor as E, Current sensor as I, and Position sensor as X. The fault has been studied across different types of sensors. There are many experiments, out of which we have chosen the ‘Industrial Tier1 Competition’ experiment’s datasets. dataset. In that the number of experiments is 60 and out of that 30 experiments have faults injected. This particular dataset has 21 sensor outputs taken across 4 minutes time duration. 

## Pre-Processing:
The Dataset is preprocessed after Standardisation using Principal Component Analysis and Kernel Principal Component Analysis. This is mainly done to reduce the dimentionality of the data (in this case, 21 feature vectors to 5) to reduce computational complexity during training and the "Curse of Dimentionality". Furthermore, it helps in easy visualisation of data. 

## Model:
The Model used is a Deep Neural Network with 2 ReLu layers and an output Sigmoid Function. The Cross Entropy Loss function is used along with an Adam Optimiser. The evaluation parameters used are:
1. Accuracy
2. Precision
3. Recall
4. F1 Score
5. Cohen's Kappa 
6. ROC AUC

![alt text](https://github.com/niranjana98/Fault-Detection-of-Satellite-Power-Systems-using-Deep-Learning/blob/main/Model.png)

## Other Classifiers
The given Dataset is also processed using other classifiers such as SVM, Decision Tree, Naive Bayes and Multi Layer Perceptron


