# Pewlett-Hackard-Analysis

Pewlett Hackard, is very large organization that has noticed that several thousand employees, are coming into retirement age and will cause what is known as the “silver tsunami”. The company would like an analysis done to find out how the “silver tsunami” will impact the company. The information that they would like me to analyze is as follows:

-	Identify the retiring employees by their title.
-	Determine the sum of retiring employees grouped by title.
-	Identify the employees eligible for participation in the mentorship program.
-	Determine the number of roles-to-fill grouped by title and department.
-	Determine the number of qualified, retirement-ready employees to mentor the next generation grouped by title and department.

## Results:
### Relational Database Diagram

I used Quick DBD through quickdatabasediagrams.com to create the entity relationship diagram (ERD) of the database (conceptual, logical, and physical diagram of the database).

![Relational Database Diagram](https://github.com/backwater-graphics/Pewlett-Hackard-Analysis/blob/main/Media/relational-database.png)
---

Following the ERD I created the database in Postgres. The tables and queries were created in SQL. The definition for retiring employees has been defined as anyone born between 1952 and 1955 and also hired between 1985 and 1988 that will begin to retire. Below you will find the four major points from the two analysis we created:

### Number of Retiring Employees by Title

1.	There are 300,024 employees at the Pewlett Hacker company and of the that a total of 90,398 employees are set to retire from the company soon.
2.	 Most of the employees that will be retiring soon are in Senior positions at about 23.9% which will lead to a huge loss of knowledge within the company and fortunately, the company will only lose 2 managers, which means that will minimize the need to train new leadership.
3.	We see the departments with the highest number of potential retirees are in Development coming in at around 25.45%, the next in line is production at 22.30% and last is sales at 7.27%.

![Number of Retiring Employees by Department](https://github.com/backwater-graphics/Pewlett-Hackard-Analysis/blob/main/Media/dept-numbers.png)
---

### Employees Eligible for Mentorship Program

4.	The number of employees who are eligible for the mentorship program is low at 1,549 employees in comparison to the number of retiring employees.

![Number of Retiring Employees for mentorship](https://github.com/backwater-graphics/Pewlett-Hackard-Analysis/blob/main/Media/numberofemployeesformentorship.png)
---

## Summary:

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

Through analysis I begin to see that the "silver tsunami" will begin to make an impact, when the 90,398 roles start to retire and that there will be a need to fill 7 different job categories across the organization. Most of which are senior level positions, but luckily there are only 2 manager positions that will need to be filled with this retirement.

![Number of Retiring Employees](https://github.com/backwater-graphics/Pewlett-Hackard-Analysis/blob/main/Media/mentership.png)
---

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

I also noticed that through analysis that there are not enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees, they currently only have 1549 employees available for the mentorship program. That would mean that each mentor would be responsible for about 58 mentees, which is way too many for any employee to mentor. When we break down the mentorship eligibility by each department, we can see that the employees are proportionally spread to the employees that are retiring but there are still too few mentors to employees. 

