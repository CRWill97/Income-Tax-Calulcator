# Income-Tax-Calulcator
Program to calculate income tax for a local Certified Public Accountant.

 Customer ID Number (int)
 Total earnings for the year (double)
 Federal taxes withheld (double)
 State taxes withheld (double)
 Amount of tax deductions (double)

Calculating Federal Tax
People who earn more money have to pay a higher percentage of their income to taxes.  As a person’s 
income increases, there are transition points, called tax brackets, where additional taxes are paid.  
Assume the following tax brackets.

Calculating State Tax
To calculate state income tax, simply multiply the total Federal taxes due ($11,500) by 7% ($805).

Calculating Refunds
To calculate refunds (or additional taxes due), subtract Federal taxes from Federal taxes withheld.  Do 
the same for state taxes.  A customer receiving a refund should have a positive value.  Those owing 
additional taxes should be negative.

