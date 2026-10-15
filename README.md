THAVAKKUL EARTH MOVERS — WORK & ACCOUNTS WEBSITE

OPENING THE WEBSITE
1. Download and extract the complete project ZIP.
2. Open index.html in an up-to-date Chrome or Edge browser.
3. This starter version saves data in that browser on that device. Use Data & Backup to download a JSON backup regularly.

DAILY / MONTHLY / YEARLY BUSINESS ANALYSIS
1. On the main Dashboard, choose Today, This month, This year or All time.
2. Choose Daily, Monthly or Yearly in “Group by” to see activity grouped into the selected interval.
3. The analysis shows hour-meter work income, extra income, expenses, net activity, customer payments, wages settled later and wages still due.
4. The top KPI cards reflect the selected reporting scope. The analysis table is activity in the chosen date period; it does not treat carry-forward opening balances as new-period income.

HORIZIA PARTNERSHIP TRACKING
1. Open Vehicles and edit each of the five shared vehicles.
2. Enable “Horizia partnership vehicle” for those vehicles. Up to five vehicles can be selected.
3. When adding a work entry, choose “Client's own contract” or “Third-party contract”. Enter hour-meter start/end readings and the hourly rate as usual.
4. Enter any additional side/extra payment in “Extra income received from third party”. Enter diesel, operator wages and other partnership expenses. Record who paid each expense.
5. On the Horizia Partnership page, choose the period and group by daily, monthly or yearly to review income, expenses, net activity and payer totals.
6. Opening balances entered under Horizia categories are included in the lifetime Horizia settlement. In the period analysis, an opening balance appears only when its effective date falls within that selected period.
7. Export the settlement CSV for a spreadsheet report.

SETTLEMENT RULE CURRENTLY USED
Meter work income = (ending meter - starting meter) x hourly rate.
Total partnership income = all meter work income + extra income received from third parties + Horizia opening income balances.
Total partnership expenses = diesel charges + total operator wages + other expenses + Horizia opening expense balances.
Net settlement = total partnership income - total partnership expenses.
- Positive net: Thavakkul's client/operator pays Horizia the difference.
- Negative net: Horizia pays Thavakkul's client/operator the absolute difference.
- Zero net: income and expenses are balanced.

Payer totals are displayed separately to show what was paid by the Thavakkul client/operator, third parties, Horizia, or other/unassigned payers. Opening “already paid by” amounts are for payer tracking only and do not add to income or subtract expenses again. This basic calculation does not apply a profit-share percentage or adjust for capital contribution, loans, depreciation, tax or previous settlements. Have the partnership agreement and final accounting method confirmed by your accountant before using it for final payment.

OPENING BALANCES
1. Open Accounts & balances.
2. Select an effective date and account category, enter the opening amount, and add a customer/operator name and notes if useful.
3. Categories include general customer receivable/advance, operator wage payable, diesel/other expenses outstanding, and Horizia income, expense and payer-contribution categories.
4. For an opening operator wage balance, enter the operator name. You can later use “Settle wages” to record a full or partial payment against that balance.

OPERATOR WAGES — TWO TYPES
- “Booking / accrued — pay later”: enter the full wage owed and normally leave “paid at this job” at zero. The balance remains outstanding until you record a later settlement under Accounts & balances → Operator wage settlements.
- “Day/job wage — paid now”: the paid-now field is prefilled to the full amount when possible, and can be adjusted if partly paid. The remaining amount stays outstanding.
- For later payments, select the specific work booking or opening wage balance. Partial payments reduce that exact balance, and the payment is dated in the daily/monthly/yearly analysis. The wage expense is not counted twice.

PUBLISHING / LOGINS
This local preview now includes demo Owner/Admin and Client/Horizia sign-in screens and UI-level view-only controls for the client. These are not secure production accounts. At final publishing, replace them with two real separate accounts connected to one shared cloud database, with permissions enforced securely on the server/database.

DEMO LOGINS (LOCAL PREVIEW ONLY)
- Owner / Admin: username `owner`, password `Owner@12345`.
- Client / Horizia: username `horizia`, password `Horizia@12345`.
- Choose the appropriate role on the login page before signing in.
- Owner mode shows the controls for adding, editing, deleting, wage settlements and backups.
- Client mode hides write controls and is intended for viewing records/reports plus sending chat messages and image attachments.
- Log out to switch between the demo roles. This helps preview both screens on one device.

CHAT AND IMAGE ATTACHMENTS
1. Sign in and open “Chat with Client”.
2. Type a message and press Send, or choose “+ Photo” to attach an image. Large images are resized in the browser before saving.
3. Chat messages and compressed image attachments persist in local browser storage (IndexedDB when available, otherwise a small localStorage fallback).
4. Both demo roles can view and send messages within the same browser profile. This is NOT a real chat between separate devices: messages are not transmitted over the internet and do not sync to the client's phone.

IMPORTANT SECURITY AND PUBLISHING LIMITATION
This website is still a single-file local preview. Demo sign-in credentials are defined in the front-end, and role permissions here are UI-level convenience only; a technically skilled user can bypass them. Do not deploy this version with real business or client data and do not share the demo credentials as if they were secure accounts.
Before public publishing, connect a real authentication provider and shared cloud database with server/database-enforced owner/client permissions. Add private cloud object storage for chat photos, and realtime or polling message delivery. Create distinct real accounts for the owner and client, set their passwords privately, and remove these demo credentials. Owner should have create/edit/delete permissions; client should have read-only access to business records while still being allowed to create chat messages and attach images.

