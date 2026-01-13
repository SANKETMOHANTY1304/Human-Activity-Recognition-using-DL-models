Human Activity Recognition (HAR) is a key application of time-series analysis and deep learning, widely used in healthcare, fitness tracking, surveillance, and smart devices. This project focuses on building an intelligent system that automatically recognizes human activities such as Walking, Sitting, Standing, Lying, Upstairs, and Downstairs using multivariate time-series sensor data.
The system leverages Recurrent Neural Networks (RNN), specifically LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) architectures, to capture temporal dependencies in sequential sensor signals obtained from smartphone accelerometer and gyroscope sensors.

OBJECTIVES:
To process and model multivariate time-series sensor data
To design and train LSTM and GRU based deep learning models
To accurately classify different human activities
To compare performance of LSTM and GRU models
To evaluate the system using metrics like Accuracy, Precision, Recall, F1-score, and Confusion Matrix

DATASET:
The dataset contains time-series signals from smartphone sensors (Accelerometer and Gyroscope).
Each sample represents a fixed time window of sensor readings.
Activities include:
Walking
Walking Upstairs
Walking Downstairs
Sitting
Standing
Lying
