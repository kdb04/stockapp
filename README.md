# Frappe - Stock Market Tracker

A Stock Market Tracker Application using the [Frappe framework](https://frappeframework.com/), which performs basic CRUD operations for tracking stocks and transactions

---

## Features
- Track company stocks and their prices
- Record buy/sell transactions
- Auto-update Total and Last-Updated Date fields
- Webpage to view all stocks company-wise

---

## Required DocTypes
### Stock(Master)
![Stock DocType fields](./screenshots/stock.png)
![Stock DocType input](./screenshots/Stock.png)

### Transactions
![Transactions DocType fields](./screenshots/txn.png)
![Transactions DocType input](./screenshots/txn1.png)
![Transactions DocType input](./screenshots/txn2.png)
![Transactions DocType total](./screenshots/total.png)

---

### Webpage
route: /stocks
![Webpage displaying available stocks](./screenshots/website.png)
![Webpage HTML Code](./screenshots/Website.png)

---

## Execution Instructions
```bash
bench init <dir-name>
cd <dir-name>

bench new-site stocktracker.local

bench get-app stocktracker https://github.com/kdb04/stockapp.git 

bench --site stocktracker.local install-app stocktracker

bench start
```

## TO-DO
- [x] Bench Setup
- [x] Both DocTypes
- [x] Input Validation
- [x] Website to display stocks
