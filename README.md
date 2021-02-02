# Fault-Detection-of-Satellite-Power-Systems-using-Deep-Learning

Dataset:
The ADAPT is a test bed developed by NASA Ames and Research Centre to act as a benchmark or testing and verification tool. All data samples in the datasets are viewed as a list of faults and under normal conditions, including all sensor data collected across a time period at various frequencies, spanning the length of the particular injection of fault. The datasets consist of multiple experiments in Multivariant Time Series with many types of sensors. The types of sensors have different notations. For instance, the Relay sensor is notified as EY, Voltage Sensor as E, Current sensor as I, and Position sensor as X. The fault has been studied across different types of sensors. There are many experiments, out of which we have chosen the ‘Industrial Tier1 Competition’ experiment’s datasets. dataset. In that the number of experiments is 60 and out of that 30 experiments have faults injected. This particular dataset has 21 sensor outputs taken across 4 minutes time duration. 
Dataset.csv: Contains the above explained Dataset 

The Goal chosen is Binary Classification and hence the dataset is labelled as 0 for "No Fault" and 1 for "Faulty"

The Dataset(only for PCA Code) is edited so as to be given for the code PCA_and_KPCA.ipynb and the output thus obtained is the Dataset_KPCA.csv. This is the data that will be given as input to the Neural Network and Machine Learning Model. 



