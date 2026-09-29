# LoanIQ — AI Loan Eligibility Checker

Premium dark fintech/BFSI demo built with HTML, CSS, Vanilla JavaScript and Netlify Functions.

## Features
- Loan eligibility estimator
- Credit score analyzer
- EMI calculator with chart
- AI financial education chat
- Financial dashboard
- Optional Google Sheets persistence
- Responsive glassmorphism UI

## Deploy to Netlify
1. Push this folder to a GitHub repository.
2. Import the repository into Netlify.
3. Build command: leave blank.
4. Publish directory: `.`
5. Functions directory: `netlify/functions` (already configured in `netlify.toml`).

## Environment variables
In Netlify → Project configuration → Environment variables:

- `CLAUDE_API_KEY` — your Anthropic/Claude API key.
- `CLAUDE_MODEL` — optional model name supported by your Anthropic account.
- `GOOGLE_SHEETS_WEBHOOK_URL` — optional Google Apps Script web-app URL that receives JSON and appends it to Google Sheets.

Never commit API keys or secrets to GitHub.

## Google Sheets
The included `save-data.js` expects a webhook endpoint. A Google Apps Script Web App can receive the POST request and append selected fields to a Sheet.

## Important
This project provides educational estimates and calculations. It is not a lender, does not guarantee loan approval, and is not personalized financial, tax, legal, or investment advice.
