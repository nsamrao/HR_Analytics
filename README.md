### _Using an open source data set from Kaggle containing employee features such as satisfaction rates, salary, and retention to determine what kinds of employees are leaving the company and why._

### Data Set Features: 
Satisfaction Level, Last Evaluation, Number of Projects, Average Monthly Hours, Time Spent at Company, Work Accident, Quit Company, Promotion in Last 5 Years, Department, Salary

### The Big Picture: An Overview of Past and Present Employees

![screen shot 2017-01-17 at 4 37 03 pm 2](https://cloud.githubusercontent.com/assets/22280221/22046130/715f5cda-dcd3-11e6-82fe-35705d0822db.png)

  - The Average Monthly Hours for all workers is around 201
  - Satisfaction Levels are around 61%
  - People work on average 3 or 4 projects a year
  - Performance average is around 71%
  - Workers spend an average of 3.5 years at the company
  
### The Big Picture: Coorelation

![264c19f0-dcd2-11e6-977a-7c5c14350550](https://cloud.githubusercontent.com/assets/22280221/22046362/f17b9d9c-dcd4-11e6-9c77-cf9ff991a609.png)

We are concerned with the rentention rate of our company, lets look at two variables that directly address this: whether the employee has left or not and the length of time the employee has been at the company.

- **Satisfaction level is a strong indicator of whether an employee will leave the company.** As satisfaction increases, the number of employees that leave decreases.
- The evaluation of an employee has no influence on an employee leaving the company.
- **The longer the employee has been at the company, the more likely they are to leave.**
- **The longer the employee stays at the company, the less they are satisfied with the company.**

### Let's Compare: Who stayed, who left? There are many strong indicators that charecterize the individuals who quit our company:

![screen shot 2017-01-17 at 4 40 46 pm 2](https://cloud.githubusercontent.com/assets/22280221/22046189/d15e0442-dcd3-11e6-995c-367d96addcd9.png)

The time the employee will spend at the company will decrease, in other words: **An employee will quit, as thier satisfaction levels, evaluation, # of projects and hours work decrease.** They will work less hours as they score less in evaluations and are given less projects.

Comparing the descriptive statistics for both groups we discover:

- The retention rate of the company is 11428/14999 = 76.19%
- On average, employees who quit are far less satisfied (.44 vs .66)
- They also work more hours, more projects and recieve somewhat higher evaluation scores, on average.
- They spend more average time at the company at 3.87 whereas employess still at the company have worked there an average of 3.38.
