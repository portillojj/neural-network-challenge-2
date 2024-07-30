# neural-network-challenge-2
Module 19 Challenge - Neural Network Challenge 2

## Background
You are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

## Files

## Before You Begin
Before starting the assignment, be sure to complete the following steps:
   - [x] Create a new repository for this project called `neural-network-challenge-2`. **Do not add this homework assignment to an existing repository.**
   - [x] Clone the new repository to your computer.
   - [x] Inside your local Git repository, add the starter file `attrition.ipynb` from your file downloads.
   - [x] Push these changes to GitHub.
   - [x] Upload `attrition.ipynb` to Google Colab and work on your solution there.
        - Make sure to periodically download your file and push the changes to your repository.

## Instructions

Open the starter file in Google Colab and complete the following steps, which are divided into four parts:

## Part 1: Preprocessing

1. Import the data and view the first five rows.

2. Determine the number of unique values in each column.

3. Create `y_df` with the attrition and department columns.

4. Create a list of at least 10 column names to use as X data. You can choose any 10 columns you’d like EXCEPT the attrition and department columns.

5. Create X_df using your selected columns.

6. Show the data types for `X_df`.

7. Split the data into training and testing sets.

8. Convert your `X` data to numeric data types however you see fit. Add new code cells as necessary. Make sure to fit any encoders to the training data, and then transform both the training and testing data.

9. Create a StandardScaler, fit the scaler to the training data, and then transform both the training and testing data.

10. Create a OneHotEncoder for the department column, then fit the encoder to the training data and use it to transform both the training and testing data.

11. Create a OneHotEncoder for the attrition column, then fit the encoder to the training data and use it to transform both the training and testing data.Using your knowledge of Pandas and scikit-learn’s `StandardScaler()`, preprocess the dataset so that you can use it to compile and evaluate the neural network model later.

## Part 2: Create, Compile, and Train the Model

1. Find the number of columns in the X training data.

2. Create the input layer. Do NOT use a sequential model, as there will be two branched output layers.

3. Create at least two shared layers.

4. Create a branch to predict the department target column. Use one hidden layer and one output layer.

5. Create a branch to predict the attrition target column. Use one hidden layer and one output layer.

6. Create the model.

7. Compile the model.

8. Summarize the model.

9. Train the model using the preprocessed data.

10. Evaluate the model with the testing data.

11. Print the accuracy for both department and attrition.

## Part 3: Summary

Briefly answer the following questions in the space provided:

1. Is accuracy the best metric to use on this data? Why or why not?

2. What activation functions did you choose for your output layers, and why?

3. Can you name a few ways that this model could be improved?


## Hints and Considerations

- Review previous modules if you need help with data preprocessing.

- Make certain that your training and testing data are preprocessed in the same ways.

- Review Day 3 of this module for information on branching neural networks.

## Badges

## Visuals

## Installation

## Usage

## Support
Some of the code on this assigment was done with the help of a bootcamp tutor.

## Roadmap

## Contributing

## Authors and acknowledgment
1. Reference material - [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/)
2. Python HOWTOs - [https://docs.python.org/3/howto](https://docs.python.org/3/howto/index.html)
3. This site was built using [GitHub Pages](https://pages.github.com/)

## License
Apache License
Version 2.0, January 2004

## Project status
- 

## Footnotes