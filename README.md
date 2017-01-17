# HR_Analytics
Human Resources Analytics: Why are a company's best employees leaving?

Using an open source data set from Kaggle containing employee features such as satisfaction rates, evaluation scores, salary, department, and retention information to determine what kinds of employees are leaving the company and why.

Data Set Features: 
Satisfaction Level, Last Evaluation, Number of Projects, Average Monthly Hours, Time Spent at Company, Work Accident, Quit Company, Promotion in Last 5 Years, Department, Salary

## The Big Picture: An Overview of Past and Present Employees

  - The Average Monthly Hours for all workers is around 201
  - Satisfaction Levels are around 61%
  - People work on average 3 or 4 projects a year
  - Performance average is around 71%
  - Workers spend an average of 3.5 years at the company
  
## The Big Picture: Coorelation

![Coorelation](https://github.com/nsamrao/HR_Analytics/blob/master/Coorelation_1.png)

We are concerned with the rentention rate of our company, lets look at two variables that directly address this: whether the employee has left or not and the length of time the employee has been at the company.

- **Satisfaction level is a strong indicator of whether an employee will leave the company.** As satisfaction increases, the number of employees that leave decreases.
- The evaluation of an employee has no influence on an employee leaving the company.
- **The longer the employee has been at the company, the more likely they are to leave.
- The more projects, higher average monthly hours and higher evaluation score of an employee the longer the employee is retained by the company.
- The longer the employee stays at the company, the less they are satisfied with the company.**

## Let's Compare: Who stayed, who left? There are many strong indicators that charecterize the individuals who quit our company:

The time the employee will spend at the company will decrease, in other words: **An employee will quit, as thier satisfaction levels, evaluation, # of projects and hours work decrease.** They will work less hours as they score less in evaluations and are given less projects.

Comparing the descriptive statistics for both groups we discover:

- The retention rate of the company is 11428/14999 = 76.19%
- On average, employees who quit are far less satisfied (.44 vs .66)
- They also work more hours, more projects and recieve somewhat higher evaluation scores, on average.
- They spend more average time at the company at 3.87 whereas employess still at the company have worked there an average of 3.38.
