**MSc SQL LAB**  

**Please ensure you are using the EmpDeptQual database for these questions** 

1. Assuming that the salary value stored for each employee is their monthly salary, display their weekly salary rounded to the nearest whole number. 

```sql
SELECT ROUND((sal*12)/52) AS WeeklySalary from emp;
```

1. Display the third letter of each employee name. 
1. Display the empno and ename of the employee who has worked with the company the longest. 
1. Display the name of the employee who earns the most (SAL+COMM) 
1. Display the total number of employee names that contain the letter A. 
1. Display the total number of employees that earn more than the average salary. 
1. Display the name and salary of the employee who earns (Sal+Comm) the least in the organization.  
1. List the names and jobs for all of the employees having the same job as JONES. 
1. List the name and salary of each employee who earns more than the average of all of the employees salaries. 
1. Using a single command, create a table called promotion with fields called ename, job, salary, and comm, then copy the corresponding data from the fields in the emp table into the promotion table for all those employee whose commission is more than one quarter of their salary. 
1. Create a view called emp10 with the empno, ename, and job data for department 10. 
1. List all of the data in view emp10. 
1. Create a table called proj with the following fields : Projno  numeric  3 long  not null 

Pname  character             5 long 

Pbudget  numeric  7 long with 2 decimal places \*Projno is the primary key. 

14. Insert into proj the following data: 101  ALPHA  96000 

    102  BETA   82000 103  GAMMA  15000 

15. List all the data in proj. 
15. Give the emp table a column called projno and describe the table. The projno field should have the same type and size as in the proj table. 
15. Assign everyone in department 20 and every salesman to project 101 and view the emp table. 
15. Assign everyone else to project 102 and view the emp table. 
15. List the employee numbers, jobs, department numbers and project name's. 
15. Alter  the  width  of  the  project  budget  field  to  8  places  including  2  decimal places. 
15. Change the budget for project 103 to 105000 
15. View the employee, number, name, department number, department location, project name and project budget. 
15. Create a view called PERSONNEL which contains employee names, jobs and project names. 
15. Using  the  PERSONNEL  view,  select  the  employee  names,  jobs  and  project names for all employees who are managers. 
15. Delete the PERSONNEL view.  
