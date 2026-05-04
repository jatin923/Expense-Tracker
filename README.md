# Expense Tracker

A simple browser-based expense tracker built with **HTML, CSS, and vanilla JavaScript**. Transactions are stored locally in your browser using **localStorage**.

## Features

- Add transactions with a description and amount
- Use **positive** amounts for income and **negative** amounts for expenses
- Shows total balance, total income, and total expenses
- Persists data locally in your browser

## How to run

- **Option 1 (quickest)**: Open `index.html` in your browser.
- **Option 2 (recommended)**: Run a local server (avoids some browser restrictions).

If you have Node.js installed:

```bash
npx serve .
```

Then open the local URL it prints.

## Project structure

- `index.html` — App layout
- `style.css` — Styling
- `script.js` — App logic (add/remove + summary calculations + localStorage)

## Data storage

Transactions are saved in your browser under the localStorage key `transactions`.

## Known issue

- **Deleting a transaction may not persist after refresh** due to a typo in `script.js` where it saves to `transcations` instead of `transactions`.

