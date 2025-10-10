USE CASE NARRATION:
Use Case: Process Employee Payroll
Actors:
Payroll Administrator, Payroll System
Goal:
To calculate and distribute employee payments based on timecards, salaries, and commissions.
Preconditions:
•	Employee records (timecards, sales receipts, and deductions) are available in the database.
•	System date matches a scheduled payday.
Postconditions:
•	Employees are paid according to their payment method.
•	Payment records and deductions are updated in the database.
Main Flow:
1.	Payroll Administrator starts the payroll process.
2.	System retrieves all employee records.
3.	System calculates pay for:
o	Hourly employees (including overtime).
o	Salaried employees (fixed monthly salary).
o	Commission employees (salary + commission).
4.	System deducts applicable union dues and service charges.
5.	System generates payment (check or direct deposit) based on employee preference.
6.	System records the payment in the database.
7.	Payroll Administrator reviews and confirms completion.
