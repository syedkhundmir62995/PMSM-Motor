# PMSM-Motor-Temperature-Prediction
### Project Details: 
- Permanent magnet synchronous motors have gained popularity in robotic arms, wind turbines, electric vehicles due to their merits of high efficiency, power density, less noisy, low maintenance cost, and reliability. The dataset was downloaded from the Kaggle and it contains total of one lakh thirty thousand measurement records of different PMSM motors identified by a unique profile id. 
 
### Opportunity:
- The company is looking for the best solution which can be able to monitor the stator and rotor temperatures of a PMSM in real-time. Due to the very complicated structure of PMSM, direct temperature measurement with thermal sensors of stator and rotor is not possible.

### Approach:
- The idea behind this project is to build a machine learning model with appropriate feature engineering and selection techniques, that estimates four target variables. I have implemented two machine learning models which are Decision Tree and SVM where I have observed the accuracy was 95+. But a limitation of multi-output prediction with machine learning is that the relationships between inputs and outputs can be blocky or highly structured based on the training data. So, I have implemented an Artificial Neural Network for this task and it works very well. Total of three models were used for this project of which one with the best accuracy was selected.

### Results:
- I have used the r2 score as our measurement metric and achieved an accuracy of 90+% on the test as well as on validation data.
