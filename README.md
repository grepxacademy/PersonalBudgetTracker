# PersonalBudgetTracker
this repo is for grepx academy students project

### What Are We Building?
A command-line Python app where you can track your monthly expenses. Add an expense, view all expenses, see a monthly summary, and convert the total to USD using a live currency API.

**Folder Structure**

budget-tracker/
├── data/
│   └── expenses.csv
├── src/
│   ├── expenses.py
│   ├── reports.py
│   └── currency.py
├── tests/
│   ├── test_expenses.py
│   └── test_reports.py
├── main.py
├── requirements.txt
├── .env
└── .gitignore


### Git Branch Workflow
Follow this order for every ticket:

Step 1	git checkout main
Step 2	git pull origin main
Step 3	git checkout -b feature/ticket-name
Step 4	Write your code
Step 5	git add .
Step 6	git commit -m 'TICKET-N: short description'
Step 7	git push origin feature/ticket-name
Step 8	Create Pull Request → merge to main

### Branch summary:

Ticket	Branch Name	What Gets Built
1	feature/setup	Folder structure, venv, requirements.txt
2	feature/add-expense	src/expenses.py — add_expense()
3	feature/view-expenses	src/expenses.py — load_expenses()
4	feature/summary-report	src/reports.py — monthly_summary()
5	feature/currency-convert	src/currency.py — get_usd_rate()
6	feature/main-menu	main.py — full menu loop

