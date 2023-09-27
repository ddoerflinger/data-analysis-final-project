# data-analysis-final-project
This is my final project for the Data Analysis course. Checkpoint 4 can be found on Tableau Public.

##Checkpoint 1
Checkpoint 1 was choosing my dataset. I chose a dataset on diabetes, focusing on patient data. I specifically chose the dataset from Iran because it was over a period of time, included many features including age, BMI, and medical testing data, and it was less binary than other datasets that I had found.

##Checkpoint 2
Checkpoint 2 was performing Exploratory Data Analysis (EDA) on the diabetes dataset. This mostly involved getting to know my dataset and getting an idea of the features it included and the size. My EDA looked into the general statistics of each feature, how many values in each, how many null values were in the dataset, and if there were any duplicates. I also started creating visualizations to see if I could find relationships between some of the variables. The data did not have null values, or duplicates, but only had 800 unique patient IDs, which was interesting. There were several typographical errors within the dataset that I would need to take care of, like extra genders and class types.

##Checkpoint 3
Checkpoint 3 was all about cleaning up the dataset. There was no missing data, outliers, or unnecessary data. I found out the 200 duplicated patient IDs were patients that had returned to the clinic multiple times for retesting. There were some inconsistent data I had to fix in the gender and class columns.

##Checkpoint 4
Checkpoint 4 is on Tableau.public. I created meaningful visualizations from the dataset and created a story that shows the factors used to predict diabetes and complications that can arise from the disease and how those can be detected with the data.

##Checkpoint 5
Checkpoint 5 is practice with data modeling and machine learning using sklearn and statsmodels. Initially, I looked for correlations between variables and found a strong correlation between the creatinine and urea variables. The goal of this checkpoint was to develop a linear regression model between these two variables. I, then, split the data into 70% training data and 30% test data and fit the training data to a linear regression model using ordinary least squares. Then, I plotted this linear regression model against the original data points to see if it fit. The model ended up having a low correlation score (0.367), indicating that a linear model did not best fit this data. 
