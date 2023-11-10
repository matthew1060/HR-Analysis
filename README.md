# HR-Analysis : Salifort Motors


# Project Overview
Salifort Motors seeks to improve employee retention and identify the factors that are likely to make an employee leave the company. The final random forest model performed with 96.3% accuracy and 86.9% precision determining what features were most important in predicting whether an employee will leave or not. 

# Business Understanding 

If you look at a normal work month an employee will work an average of 40 hours per week * 50 weeks / 12 months = 166.67 hours per month. During the visualization stage we were able to conclude that Salifort Motor employees were overworked, with a significant amount of employees working over 175 average hours per month.

# Data Understanding 

The Salifort Motors data came from Coursera Google Advanced data analytics course. The data consisted of approximately 11991 unique enteries and 10 features. The features included if the employee was a present employee, their average monthly hours, their satisfaction level, their last evaluation score and their tenure in the company to name a few.

In connection to this, a feature was engineered to represent if an employee was overworked or no. An employee was considered overworked if they worked an average of more than 175 hour per month.

<img width="339" alt="image" src="https://github.com/matthew1060/HR-Analysis/assets/62417078/272e4691-824f-4b89-a198-df38df293ac2">


# Modeling and Evaluation 

A random forest model was used to determine feature importance on whether an employee would leave or not. The plot below shows that last evaluation, number of projects, tenure and overworked were the top 4 most important factors in determining whether an employee would leave. The model performed with 96.3% accuracy and 86.9% precision.

<img width="637" alt="image" src="https://github.com/matthew1060/HR-Analysis/assets/62417078/a1c38dd5-47b3-422d-b4de-65f41a6fd34c">



# Conclusion

The model can confirm that employees are being overworked, some recommendations to take note of are:
- Limit the number of project an employee can work on, or at least ensure that they are capable of handling the workload.
- Employees who work longer hours and perform well should be rewarded by the company and promoted.
- The company should set guidlines for employees with regards to expectations for workload, and the overtime policy of the company.
- Investigate why employees who leave after 4 years have unusually low satisfaction levels.
