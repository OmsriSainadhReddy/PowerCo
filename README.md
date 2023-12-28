# PowerCo
PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with us to help diagnose the source of churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, knowing which customers are more (or less) likely to churn at their current price is helpful, for which a good predictive model could be useful.

Moreover, for those customers who are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).

The Associate Director (AD) held an initial team meeting to discuss various hypotheses, including churn due to price sensitivity. After a discussion with the team, we have been asked to go deeper on the hypothesis that the churn is driven by the customers’ price sensitivities. 

Your AD wants an email with thoughts on how the team should go about testing this hypothesis.

The client plans to use the predictive model on the 1st working day of every month to indicate to which customers the 20% discount should be offered.

client_data and price_data are two datasets sent by the client for analysis.
Data Description file is the data dictionary for the columns in the above two datasets.

## TASK 1:
First task is to understand what is going on with the client and to think about how you would approach this problem and test the specific hypothesis.

We must formulate the hypothesis as a data science problem and lay out the major steps needed to test this hypothesis. Communicate thoughts and findings in an email to the AD, focusing on the data that we would need from the client and the analytical models we would use to test such a hypothesis.

<b> Mail_to_AD is the file that has the solution for this task. </b>

Please note, there are multiple ways to approach the task and my solution is just one way to do it.

## TASK 2
The project team thinks that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data and the AD wants us to perform some exploratory data analysis.

The data that was sent over includes:

Historical customer data: Customer data such as usage, sign-up date, forecasted usage, etc
Historical pricing data: variable and fixed pricing data, etc
Churn indicator: whether each customer has churned or not

Sub-Task 1:

Perform some exploratory data analysis. Look into the data types, data statistics, specific parameters, and variable distributions. This first subtask is for us to understand the dataset holistically. 

Sub-Task 2:

Verify the hypothesis of price sensitivity being, to some extent, correlated with churn. It is up to us to define price sensitivity and calculate it.


Sub-Task 3:

Prepare a half-page summary or slide of key findings and add some suggestions for data augmentation – which other data sources should the client provide you with, and which open-source datasets might be useful? 

eda_starter and summary_suggestions are the deliverable files for this task. eda_starter has the Python code for the analysis performed, and summary_suggestions has the summary of EDA findings and suggestions for the client.

