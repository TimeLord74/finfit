# fin-fit

# Financial Planner Application

Framework: Laravel & PHP
Database: mysql? something light and easy to use that works easily with php

Goal: Develop an application that will manage finances based on income, expenses, etc. 

# What should it do?
- Income
  - [ ] Handle all income based on source (this can be a person or other source such as salary, hourly rate income, bonuses, passive income from investments, etc)
  - [ ] Handle pay day calculations (Bi-Weekly, Semi-Monthly, Monthly and Weekly). You should be able to enter in your pay frequency and your last pay day and the rest should calculate (backwards and forwards for the year). This should handle what is done when there are holidays (i.e. do you get paid before or after a holiday date?).
  - [ ] Update income but do not adjust previous income entries. We don't want it recalculating historical data. 
- Expenses
  - [ ] Handle all expenses based on source (should include day of expense if you want to use this).
  - [ ] Allow breakdown of expenses based on pay frequency and days of owed expense
  - [ ] Allow for unplanned expenses. (this would be things such as some sort of family outing etc).
- Personal Money
  - [ ] Handle personal money (to allow people to project their personal money each pay day and set saving goals for things they want to do with that money). Show breakdowns based on month, quarterly and annual.
- Credit/Debt
  - [ ] Handle credit amounts and allow for entering of pay downs towards those debts (automatically recalculate owed amounts based on pay down, allow projection of time to pay off based on amounts paid and frequency of payments).
- Overview
  - [ ] Would look good if there was an at a glance page that showed an easy to read overview with a pie chart or something to show expenditure vs income, or breakdown of expenses (based on category) or income based on source.
  - [ ] Totals of categories for expenses, etc. This lets you see where your biggest expenses are or best source of income is, etc.
  - [ ] Show a projected amount that is expected to be left over each pay period and also an actual left over amount based on unplanned expenses or just manual entry from checking bank account.
- History
  - [ ] Hold historical data that can be reviewed to see what changes have affected finances.
- Other
  - [ ] Categories for income, expenses, etc. 
