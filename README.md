# SyncSINGIL VS Code Prototype

## Run it
1. Extract this ZIP.
2. Open the `SyncSINGIL_VSCode` folder in Visual Studio Code.
3. Open `index.html` in your browser. Recommended: install the VS Code extension **Live Server**, right-click `index.html`, then choose **Open with Live Server**.

## Demo accounts
- Borrower: `juan` / `demo123`
- Admin: `admin` / `admin123`

## Included screens/features
### Borrower
- Login
- Dashboard with loan totals, outstanding balance and next due date
- My Loans and due dates
- Demo payment form with GCash, bank transfer or cash selection
- Payment confirmation and payment history
- Profile editing and password change
- SMS/email reminder preferences and example reminder preview

### Admin / Staff
- Admin dashboard with borrower/loan/collection summary
- Borrower management, search, add/edit/view borrower details
- Loan management, add/edit loans, schedules, rates and status
- Payment records
- Collection schedule management and mark complete
- Reports with summary and CSV export
- User management and role/status controls
- System notification settings

## Important limitations
This is a **front-end demonstration prototype**, not a production-ready lending system. Data is saved in browser `localStorage` on the current computer only. The sample payment form does **not** transfer money. SMS/email reminders are preference settings and preview examples only; they are **not sent**. Real payment processing and notification delivery need a secure backend, database, authentication/authorization, a payment provider, and SMS/email services. Do not enter real customer data or real passwords.
