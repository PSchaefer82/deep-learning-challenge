# deep-learning-challenge
Module 21 Assignment

# Overview
An analysis using binary classification of the success rate the Alphabet Soup foundation has with funding applications. By looking over the past success rate we will try to predict the success of future applications. Dataset includes over 34,000 entries with multiple datapoints each.

Data is processed, fitted, adjusted, and results analyzed. 

# Preprocessing Data:
•	target variable: IS_SUCCESSFUL

•	feature variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

•	purged variables: EIN, NAME

# Compiling, Training, and Evaluating the Model
Layers: 

•	Initially used two hidden layers (30 and 15 neurons) 

## Activation: 
relu was used on hidden layers

sigmoid was used for output layer

# Target Performance: 
75% was not attainable. 

##Attempts:
First: 73.24%
•	Used parameters as outlined in the assignment.
![text](https://github.com/PSchaefer82/deep-learning-challenge/blob/main/deep-learning-challenge/Module%2021%201.png)

Second: 73.19%
•	Second: Added a third hidden layer.
![text](https://github.com/PSchaefer82/deep-learning-challenge/blob/main/deep-learning-challenge/Module%2021%202.png)

Third: 73.73%
•	Third: Changed all layers to sigmoid activation.
![text](https://github.com/PSchaefer82/deep-learning-challenge/blob/main/deep-learning-challenge/Module%2021%203.png)

Fourth: 73.67%
•	Fourth: Increased epoch to 75. 
![text](https://github.com/PSchaefer82/deep-learning-challenge/blob/main/deep-learning-challenge/Module%2021%204.png)

75% was not attainable. 

## Summary: 
None of the adjustments were able to increase the accuracy even 1%. 

A different model such as Random Forest could be attempted instead. 

Changing all activations to sigmoid had little impact but would allow it to work more efficiently.

# Dependencies
•	Pandas

•	sklearn.model_selection - train_test_split

•	sklearn.preprocessing – StandardScaler

•	tensorflow

## Getting Started
1. Install Python on your computer
```
https://www.python.org/downloads/
```
2. Create a new environment
```
conda create -n dev python=3.10 anaconda -y
```
3. Activate the environment
```
conda activate dev
```
4. Install all the required dependencies.
```
pip install -r requirements.txt
```
5. Clone this repository to your local computer using `git clone`.

6. Open Visual Studio Code


