# Smart Money Decision Assistant

A simple web app that helps people make better everyday money decisions. It runs fully in the browser, with no backend and no sign-up. Data stays on the user's device.

**Live demo: https://sivaniprashanth666-source.github.io/smart_money_decision_assistant/

## Features

- **Can I afford this?** Compares a purchase price with monthly spare money and gives a verdict: Comfortable, Risky or Unaffordable.
- **Subscription leak detector:** Tracks recurring subscriptions, shows monthly and yearly totals, warns before renewals and estimates yearly savings from cancelling.
- **Where is my money going?** Breaks spending into categories, compares with last month, flags big increases and gives simple suggestions.
- **EMI reality checker:** Shows the total repayment, the extra paid over the item price and the approximate yearly interest rate.
- **Hidden cost calculator:** Adds running and maintenance costs to the purchase price to show the real cost of ownership.

## Tech

HTML, CSS and vanilla JavaScript in a single file. Subscriptions are saved with `localStorage`. The EMI interest rate is found with a bisection search.

## Run it

Download `index.html` and open it in a browser.

## Ideas for next steps

- Charts for spending
- Save all inputs
- Export data as CSV
- Python or backend version with a database

## Disclaimer

A budgeting aid, not financial advice.
