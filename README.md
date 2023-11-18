# Washing Machine Vibration Classification Project

This project aims to classify vibrations from a washing machine using a K-Nearest Neighbors (KNN) model with anomaly detection capabilities. Three labels were defined: "heavy" for heavy loads, "light" for light loads, and "off" when the machine is not in operation. The model was successfully trained, achieving an impressive accuracy of 97.7% with minimal loss of 0.07. This high precision ensures reliable classification of washing machine movements. The source code and deployment instructions for an Arduino Nano 33 BLE make the project accessible and practical.

The combination of motion classification and anomaly detection provides a robust solution for real-time monitoring of washing machine operations.

Step 1: Data Collection.

For data collection, I put my Arduino 33BLE on my phone and I activated Vibrator to simulate a washing machine vibration. I kept varying the vibration intensity to have 2 classes: Heavy and Light. I used a split of 75/25 for the training and the test datas.
![image](https://github.com/saidg78/projet_3/assets/148437845/d50cf96b-6fa5-4c0f-91d2-6b5cb53f7521)

Step 2: Creating an impulse. 
So I used the KNN model with anomaly detection. 
![image](https://github.com/saidg78/projet_3/assets/148437845/34f8daca-c9a0-4f91-a566-77005bcd166a)

Step 3: Extract features and generate features.


![image](https://github.com/saidg78/projet_3/assets/148437845/0c393def-f37e-4441-934b-85e4235471a0)


Step 4: Train


![image](https://github.com/saidg78/projet_3/assets/148437845/4d158379-3530-4ed1-a232-e5fda9623a1b)

Step 5: Anomaly detection
![image](https://github.com/saidg78/projet_3/assets/148437845/28da9de9-99d5-4be8-ac8c-3aa232221a59)


Step 6: Model testing
As we can, I have a good score of 90% so there was no need to change the parameters.

![image](https://github.com/saidg78/projet_3/assets/148437845/0c095c08-3515-4790-9ba5-de75d727c9e7)

Step 7: Download the arduino Library

![image](https://github.com/saidg78/projet_3/assets/148437845/5c0babb7-e924-448f-b6cc-0c0e522a38fb)
