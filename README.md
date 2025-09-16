# Walk For — Demo (GitHub-ready)

This is a demo, single-page **web game** called *Walk For*. It's a frontend-only (demo) app that simulates earning coins while a character "walks". Withdrawals are saved locally (demo). For production you must add a backend, database, authentication and real payout integration.

## Files in this package
- `index.html` — Main page (open in browser)
- `style.css` — Styles and animations
- `script.js` — Game logic (localStorage demo)
- `README.md` — This file

## How to run locally
1. Download and extract the ZIP.
2. Open the folder and double-click `index.html` to run in your browser.
3. To publish: Create a GitHub repo, push these files to the `main` branch and enable **GitHub Pages** (use root). The site will be available at:
   `https://yourusername.github.io/repo-name/`

## Notes & Demo behavior
- 1000 coins = ₹100 (1 coin = ₹0.1)
- Minimum withdraw ₹200 = 2000 coins
- Daily cap: 1000 coins (once reached, earning stops for the day)
- Withdraw requests are saved to `localStorage` with status `Pending` (demo)
- Admin approval & real bank transfer must be handled by you in production

## Next steps for production
- Replace localStorage with a secure backend (Node/Express + DB or Firebase)
- Add user authentication & KYC
- Use a payout API (Razorpay/Paytm payouts) or manual admin dashboard for transfers
- Add ads SDK or integrate your own ad rotation

