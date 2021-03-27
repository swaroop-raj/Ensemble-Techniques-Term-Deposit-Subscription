# Problem statement (Term Deposit Sale)

We have data from a Portuguese bank on details of customers related to selling a term deposit. The objective of the project is to help the marketing team identify potential customers who are relatively more likely to subscribe to the term deposit and this increase the hit ratio.


## What is a Term Deposit?

A Term deposit is a deposit that a bank or a financial institution offers with a fixed rate (often better than just opening deposit account) in which your money will be returned back at a specific maturity time.

 

## Resources Available

The historical data for this project is available in file https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

 

## Deliverable –1 (Exploratory data analysis)–(15)

* Univariate analysis (9marks)
* Data types and description of the independent attributes which should include (name,  range of values observed, central values (mean and median), standard deviation and quartiles, skewness). - 3 Marks
* Make a function to plot ‘countplot’ if the variable is categorical and ‘distplot’ if the variable is numeric. - 3 Marks
* Identify outliers using IQR and verify the same using plots. Also mention the percentage of data points which are considered outliers. Should we treat them, why or why not? - 3 Marks
* Multivariate analysis (6marks)
* Make a function to plot boxplots for all continuous variables VS ‘Target’ variable and countplots for all categorical variables VS ‘Target’ variable? - 3 Marks
( Bi-variate analysis between predictor variables and target column. Comment on your findings in terms of their relationship and degree of relation if any. Visualize the analysis using pair plots, heatmaps, histograms or density curves. - 3 Marks
 

Deliverable –2 (Prepare the data for analytics)–(5)

Label encode or create dummy variables for categorical variables. Give reason for selecting either of them. - 2 Marks
Create the training set and test set in a ratio of 70:30. Make sure and verify distribution of classes is the same in the full dataset and train test split data. - 3 Marks
 

## Deliverable –3 (Create the ensemble model)–(30)

* Build the ensemble models (Bagging and Boosting) and Decision Tree model (at least 4 models in total). Note the model performance by using different metrics. Use confusion matrix to evaluate class level metrics i.e. Precision/Recall. - 10 Marks
* Also reflect the training and testing score of all the models. Build a dataframe with model names as row index and all the metrics calculated as columns - 5 Marks
* Explain the confusion matrix related terms like recall, precision etc. Also, select the best metric to choose one of the models from above. Give your reason for the same. - 5 Marks
* Answer the following questions : - 10 Marks
* What do you mean by recall and what information does it provide here?
* Suggest some changes for the organization so that they can increase the number of customers who take term deposit.
* How much influence does the previous campaign and mode of interaction have on financial performance.
* Which features should be more/less focused by the bank to get better results and why?
* What did you learn about banking industries from this data?
 

**Note :** Use random_state=7 (wherever the parameter can be used) so that we can compare all submissions.

Provide comments in the solution notebook regarding the steps you take and also provide insights drawn from the plots. - 5 Marks.

Marks distribution for Students with recall_score (pos_label = ‘yes’) on the test set:

Above 43% - 5 Marks

Between 40% to 43% - 4 Marks

Less than 40% - 3 Marks

Note : Make sure you are not overfitting the model in order to increase the recall score only.

 

## Attribute Information


1 - age
2 - job : type of job
3 - marital : marital status
4 - education
5 - default: has credit in default?
6 - housing: has housing loan?
7 - loan: has personal loan?
8 - balance in account
9 - contact: contact communication type
10 - month: last contact month of year
11 - day: last contact day of the month
12 - duration: last contact duration, in seconds
13 - campaign: number of contacts performed during this campaign and for this client
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign
15 - previous: number of contacts performed before this campaign and for this client
16 - poutcome: outcome of the previous marketing campaign
17 - Output variable ('Target'): has the client subscribed a term deposit?
