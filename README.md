# FinancialInstitution
Code Challenge where you get to be the Bank and run an audit

A large Bank has commissioned you to develop a prototype computerised system for use in their local branches. 
They want to be able to store and retrieve information on their customers and accounts. They have Business and Personal account holders; and they have Deposit and Current accounts. Revenue also requires that Current accounts and Business customers are Auditable.

You will prepare a schedule, due in 30 mins. Demo time is 3pm.
You are required to present a Top-level Class Diagram for your proposed system. You are also required to provide details of state and behaviour of all classes and interfaces in your design, due in 60 mins.
~~
Each Customer should have information such as:
Name, Address, Phone Number, Account(s) they hold (only one Customer per Account).
Personal Customers should also have a DOB, PPS Number.
Business Customers should also have a VAT Number, and whether or not they hold a Tax Clearance Cert.
Each Account should have information such as:
Account number, Transactions, Balance.
Deposit Accounts should also have an interest rate of 4%.
Current Accounts should also have a Max Overdraw Amount, and whether or not a chequebook has been issued.
Randomly assign amounts to these Accounts in the range -100000 to +100000 Euro.

--
Using notepad and the command line, write a program that creates 100 Personal Customers, 100 Business Customers; and their associated Account(s).
Provide a menu giving the following options:
1)	List all Customers, and their accounts
2)	List all Accounts, and their Customers
3)	Audit all Customers
4)	Exit
All customers should then be considered for audit. The audit should provide details (print to the console) of all Customers who:
-	Have a negative balance
-	Have no Tax clearance Cert
-	Have earned > 1000 in interest
--
If time permits, provide menu options to save all customer details to file, and retrieve all customer details from file.
