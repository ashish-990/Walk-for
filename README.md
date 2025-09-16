# Walk For — Final (Fixed) — GitHub-ready

This package contains the fixed version per your request:
- Start button begins coin accrual immediately (no countdown).
- Coins increase every second until daily cap (1000 coins) is reached.
- When cap is reached, the system auto-stops. Next day (00:00) daily cap resets.
- Guest/User ID is fixed to **6932175** and shown in the UI.
- "Demo" visible labels removed; withdrawal requests saved locally with status Pending.
- Suitable for hosting on GitHub Pages (frontend-only demo).

## Files
- `index.html`
- `style.css`
- `script.js`
- `README.md` (this file)

## How to run
1. Download and extract the ZIP.
2. Open `index.html` in a browser (desktop or mobile) to test.
3. To publish: create a GitHub repo, push these files to `main` branch, enable GitHub Pages.

## Note
This is a frontend demo. For production, add backend, auth, DB and real payout integration (Razorpay/Paytm payouts or manual admin dashboard).
