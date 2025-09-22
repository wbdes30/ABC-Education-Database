# ABC-Education-Database
This project is part of the assignment for COMP2350 unit: Database Systems.
### Assignment Background 
ABC education provider is planning to automate the manual process for fees management, unit enrolment, and student performance. You are tasked to design a database solution for an organization that provides academic and certification courses. Business rules relevant to the tasks are provided, so create stored functions and stored procedures to handle scenarios involving fee management, unit enrolment, and student performance.

- Task 1: Create and populate required tables: Student, Unit, Registration, Unit Grade, and Fee.
- Task 2: Write a stored function that determines a student's total outstanding balance, including payment for late penalty and dropped units.
- Task 3: Write a stored procedure that implements business rules BR6, BR2, BR4 such that the following requirements are met: 
  1. Prevent students with an outstanding balance or more than 2 failed units from enrolling in advanced-level units (BR6),
  2. Enforce the unit registration based on outstanding balance from previous semester (BR2),
  3. Automatically apply a penalty for dropped units, if dropped after the no-penalty deadline (BR4),
  4. Error handler must be implemented to handle exceptions. 
 
