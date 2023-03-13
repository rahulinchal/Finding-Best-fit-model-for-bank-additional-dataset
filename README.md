# Performing Exploratory Data analysis and finding bestscore using best model 
There is no much difference in model performance after dealing with outliers, The performance can be incresed by tuning and so far the best fit model is Gradient boosting and adaboost model 91.09816298454317 % and 91.42242724844785 %  
Understanding the dataset
Problem statement: We have data from a Portuguese bank on details of customers related to selling a term deposit The objective of the project is to help the marketing team identify potential customers who are relatively more likely to subscribe to the term deposit and this increase the hit ratio

## Data info:

age (numeric) <br> 
job : type of job (categorical: "admin.","blue-collar","entrepreneur","housemaid","management","retired","self-employed","services","student","technician","unemployed","unknown") <br> 
marital : marital status (categorical: "divorced","married","single","unknown"; note: "divorced" means divorced or widowed) <br> 
education (categorical: "basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","unknown") <br> 
default: has credit in default? (categorical: "no","yes","unknown") <br> 
housing: has housing loan? (categorical: "no","yes","unknown") <br> 
loan: has personal loan? (categorical: "no","yes","unknown") <br> 
contact: contact communication type (categorical: "cellular","telephone") <br> 
month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec") <br> 
day_of_week: last contact day of the week (categorical: "mon","tue","wed","thu","fri") <br> 
duration: last contact duration, in seconds (numeric) <br> 
campaign: number of contacts performed during this campaign and for this client <br> 
pdays: number of days that passed by after the client was last contacted from a previous campaign <br> 
previous: number of contacts performed before this campaign and for this client <br> 
poutcome: outcome of the previous marketing campaign <br> 
emp.var.rate: employment variation rate - quarterly indicator <br> 
cons.price.idx: consumer price index - monthly indicator <br> 
cons.conf.idx: consumer confidence index - monthly indicator <br> 
euribor3m: euribor 3 month rate <br> 
nr.employed: number of employees - quarterly indicator <br> 
