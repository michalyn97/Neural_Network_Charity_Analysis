# Neural_Network_Charity_Analysis
Challenge 19

## Overview of the loan prediction risk analysis:

The purpose of the challenge is to help Alphabet Soup predict out of the 34,000 organizations who received funding which will be successful.
We are using our knowledge of machine learning and neural networks to create a binary classifier.

## Results
* Data Processing

The IS_Successful was used as a target variable while the columns listed below were features for our model.

![image](https://user-images.githubusercontent.com/30275459/153733781-bbaeb295-f2ad-4ffd-84ea-a6d468c09696.png)

We removed the EIN and NAME columns as they appeared to be unnecessary information for our dataset.

* Compiling, Training and Evaluating the Model

Since the ReLU activation function is commonly used in deep learning models, I used the function for both the hidden layers and the output.  
Within the testing phases, I attempted to undersample and oversample the data by changing the nodes/neurons in the hidden layers. Also, I removed one of
the features ["Special Considerations"] and increased the Epochs.
None of these changes proved to be succxessful as with each attempt the accuracy either lowered or remained the same.
* Test 2

![image](https://user-images.githubusercontent.com/30275459/153733986-995c4524-d4a0-4a7f-89c3-a8a1b5b9592e.png)

* Test 3

![image](https://user-images.githubusercontent.com/30275459/153733999-9369824f-d81b-4a15-977a-b19f22a4ee57.png)

* Test 4

![image](https://user-images.githubusercontent.com/30275459/153734016-f3b11734-1630-4dd8-8083-3d2564a6cddb.png)

## Summary
In the original testing model, there was a 64% accuracy rate that the organizations who received funding would be successful.  The additional tests were not as successful.
I would try the Random Forest supervised learning method as it may have a higher accuracy rate and would easily handle any outliers.  


