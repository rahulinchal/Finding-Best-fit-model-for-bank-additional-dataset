# Performing Exploratory Data analysis and finding bestscore using best model 
There is no much difference in model performance after dealing with outliers, The performance can be incresed by tuning and so far the best fit model is Gradient boosting and adaboost model 91.09816298454317 % and 91.42242724844785 %
Understanding the dataset
Problem statement: We have data from a Portuguese bank on details of customers related to selling a term deposit The objective of the project is to help the marketing team identify potential customers who are relatively more likely to subscribe to the term deposit and this increase the hit ratio

Data info:

age (numeric)
job : type of job (categorical: "admin.","blue-collar","entrepreneur","housemaid","management","retired","self-employed","services","student","technician","unemployed","unknown")
marital : marital status (categorical: "divorced","married","single","unknown"; note: "divorced" means divorced or widowed)
education (categorical: "basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","unknown")
default: has credit in default? (categorical: "no","yes","unknown")
housing: has housing loan? (categorical: "no","yes","unknown")
loan: has personal loan? (categorical: "no","yes","unknown")
contact: contact communication type (categorical: "cellular","telephone")
month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
day_of_week: last contact day of the week (categorical: "mon","tue","wed","thu","fri")
duration: last contact duration, in seconds (numeric)
campaign: number of contacts performed during this campaign and for this client
pdays: number of days that passed by after the client was last contacted from a previous campaign
previous: number of contacts performed before this campaign and for this client
poutcome: outcome of the previous marketing campaign
emp.var.rate: employment variation rate - quarterly indicator
cons.price.idx: consumer price index - monthly indicator
cons.conf.idx: consumer confidence index - monthly indicator
euribor3m: euribor 3 month rate
nr.employed: number of employees - quarterly indicator
