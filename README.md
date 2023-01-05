# Basic Books

A simple report of books designed for presentation during a meeting.

The entries are added via hand editing JSON.

Intended for under a dozen transactions per month.  Think special interest group or school organization that occasionally deals with money.


## How to use

(not implemented yet)

For each fiscal year, the books are "closed" and then another set of books are "opened".  We will start at the point of opening a new set of books for a new fiscal year.

From the existing books, do a "export for next fiscal year" operation.  This will create a data file with the following in it:

* names of all the bank accounts
* closing balances for each bank account
* a list of outstanding transactions that have yet to hit a bank account
* a copy of the budget

Then, do "create new books from prior year export", and select the data file you just exported.

You may want to then edit the budget as needed for the new year.

Now you are ready to do the monthly accounting cycle operations.

As decisions are made to spend money in specific dollar amounts,
  these should be recorded as transactions even though they have not yet hit a bank account statement.

Money coming in should also be recorded as transactions.  Money coming in will either hit the bank statement first, or there could be some kind of promise, such as money from a grant.  The best practice is to only record transactions that have a high confidence level of actually occurring.  If the transactions already hit the bank account, that's a sure thing.  If it's grant money thats expected, it might be good to wait until an approval letter is received before creating a transaction for it.  The reason for this, is that as soon as a transaction is created, it's reportable to the stakeholders.

Budget - what we think is going to happen.
Accrued Statements - what we know will happen.
Occurred transactions - what actually happened.

The difference between Accrued and Occurred is outstanding checks, whether for deposit or withdrawal.

## TODO

exceptions should display dialogue on page.

transaction entry

close report, start new

save