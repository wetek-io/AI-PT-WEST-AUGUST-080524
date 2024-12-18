# Spotting Data Leakage

## Introduction

In this activity you will examine two datasets and attempt to find the column that is leaking data into the model. Remember that data leakage is incredibly difficult to spot in the wild! Use your intuition and examine the results closely.

## Instructions

Use the Jupyter notebook in the `Unsolved` folder to complete the following steps.

### Part 1: Crowdfunding

1. Run the provided code to import and split the data, train a model, and calculate the training and testing scores. Do you believe there is evidence of data leakage? Hint: If the scores seem too good to be true, they probably are!

2. Display the head of the DataFrame and examine each column. Do you see any columns that might provide information that would not be available when trying to predict whether a crowdfunding project would be successful? Hint: Think about whether any of the columns might depend on the project being successful.

3. Check the correlation of the columns against the outcome column.

4. Plot the rewards_given and outcome columns in a scatter plot.

### Part 2: Start Up Success

1. Run the provided code to import and split the data, train a model, and calculate the training and testing scores. Do you believe there is evidence of data leakage?

2. Display the head of the DataFrame and examine each column. Do you see any columns that might provide information that would not be available when trying to predict whether a crowdfunding project would reach its goal?

3. Check the correlation of the columns to the Firm Category column.

4. Plot Firm ID and Firm Category in a scatter plot.

## References

Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
