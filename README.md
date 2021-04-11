# Gaussian Naive Bayes
### COMP30027 Machine Learning - Assignment 1, Semester 1 2021
#### By: Janice Theresia Sutrisno (1013239) & Patricia Angelica Budiman (1012861)

Objective: 
1. Implement a supervised Naive Bayes learner to classify pose from key- points provided by a deep convolutional neural network
2. The classifier is trained, tested, & evaluated on the provided dataset. 
3. Assuming dataset is located in : 
  - train_file_name="COMP30027_2021_assignment1_data/train.csv"
  - test_file_name="COMP30027_2021_assignment1_data/test.csv"
  
### To Re-Create Results ###  
A. To re-create **Gaussian Naive Bayes** result:
1. Run the block under ***PREPROCESSING*** heading
    - Run the Preprocess functions and all the supporting functions
    - To read the file and store it in required structure
    - Global variables to locate test and train dataset
        - train_file_name="COMP30027_2021_assignment1_data/train.csv"
        - test_file_name="COMP30027_2021_assignment1_data/test.csv"
2. Run the block under ***TRAIN*** heading
    - Run the Train functions and all the supporting functions to find mean, standard deviation and class probabilities
3. Run the block under ***PREDICT*** heading
    - Run the Predict functions and all the supporting functions to count probability and make predictions
4. Run the ***EVALUATE*** heading
    - Run the Evaluate functions to find the accuracy of the Gaussian Naive Bayes Classifier
5. Run the block under ***RUN HERE*** heading
    - To run the Gaussian Naive Bayes Classifier with the provided train and test datasets
    - preprocess,  train, predict, & evaluate is used here

B. To re-create results for **Q 1,3,4,5**:
1. Run each block under each questions
2. If error occurs, please run Section A.

## Questions Description
Q1. 
* Block 1: functions to calculate micro average & macro average and create confusion matrix
* Block 2: Run the functions and print the confusion matrix and results

Q3. 
* Block 1: functions to train, calculate probability, & predict classes using KDE and to calculate similarity between when using the Gaussian Naive Bayes
* Block 2: Run the functions and print the confusion matrix, accuracy %, similarity % with the Gaussian Naive Bayes 

Q4.
* Block 1: functions to 
  * preprocess train dataset for Q4 
  * do cross validation to choose best bandwidth
  * display graph of kde vs x1 attribute for class 'bridge' to show the difference when using best bandwidth and using arbitrary bandwidth
* Block 2: 
  * Run the functions to find the best bandwidth 
  * Run KDE Naive Bayes using the bandwidth
  * Display the graph
  * Show the accuracy using KDE with the best bandwidth & accuracy when using arbitrary bandwidth
        
Q5.
  * Block 1: functions to find mean of attribute per class & impute missing value with respective mean
  * Block 2: 
    * Run the functions and the Naive Bayes Classifier on the mean-imputed training dataset
    * Compare accuracy % when using 0-imputation and mean-imputation for Gaussian and KDE Naive Bayes Classifier
                
        
