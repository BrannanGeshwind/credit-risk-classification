# credit-risk-classification
Module 20 Challenge


## Analysis:
----------------
For this assignment, the objective was to analyze financial information to assess risks associated with loans and predict if a loan is healthy, or more high-risk. Healthy loans were designated as 0, whereas High-Risk was designated 1.

The goal was to use Machine Learning to study the patterns of those with loans and take into account their Income, Loan Amounts, Interest Rates, and Derogatory Marks. Using the value_counts() function on the columns for loan_status, we were able to get the amounts of users that were considered Healthy(0) and High-Risk(1). From there, we used logistic regression to predict loan status, and trained the model using labels and features. Our labels being the loan status, whereas the features were supplemental account information, with a total sample amount of 77535.

## Results:
----------------
- First and foremost, the accuracy score of of the data from the confusion matrix came out to be 0.9924164, or 99% accurate.
- For Healthy loans: Precision, Recall, and F1-Score were all 1.00. This means all True and False Positives, and all actual positive instances were predicted correctly.
- For High-Risk loans: Precision was 0.87, Recall was 0.89, and the F1-Score was 0.88. While these numbers are still rather high, there is still room for error, as we want to be as close to 1.00 as possible.

## Summary:
----------------
In conclusion, the logistic regression was able to successfully predict if a loan would be healthy or high-risk accurately 99% of the time.

## Updates
11/2 - Finished project. Updating README for submission. Including analysis in README based on the template provided.

11/2 - Created Repository and cloned to local computer. Added in starter code and commited to repo.


## Languages and References
- [Python](https://docs.python.org/3/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/)
- [Pandas](https://pandas.pydata.org/docs/)
- [StackOverflow](https://stackoverflow.com/)
- [Scikit-learn](https://scikit-learn.org/stable/)
