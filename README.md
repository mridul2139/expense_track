# Expense Tracker - README

## Introduction
This project is a **simple Expense Tracker** application that helps you keep track of your earnings and expenses. The app allows users to add transactions with descriptions and amounts, and it automatically calculates and updates the total balance. It also categorizes transactions as earnings (credits) or expenses (debits).

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [File Structure](#file-structure)
4. [Setup and Installation](#setup-and-installation)
5. [How to Use](#how-to-use)
6. [Contributing](#contributing)

## Features
- **Track balance**: Displays the current balance based on earnings and expenses.
- **Transaction logs**: Shows a list of all added transactions, including their amounts and descriptions.
- **Earnings/Expenses differentiation**: Clearly marks each transaction as a credit or debit.
- **Add transactions**: Users can add descriptions and specify amounts to update the balance.

## Technologies Used
- **HTML5**: Structure of the web page.
- **CSS3**: Styling the user interface.
- **JavaScript (index.js)**: Provides dynamic functionalities like updating the balance and managing the transaction list.

## File Structure
```
.
├── index.html      # Main HTML file
├── style.css       # CSS file for styling
└── index.js        # JavaScript file for functionality
```

### `index.html`
- Contains the structure of the expense tracker including the form for inputting transactions, balance display, and transaction logs.

### `style.css`
- Styles the layout, fonts, and components of the expense tracker.

### `index.js`
- Handles the logic for adding transactions, updating the balance, and dynamically displaying the transaction list.

## Setup and Installation
1. Clone or download the repository.
2. Ensure you have a web browser (Chrome, Firefox, etc.).
3. Open the `index.html` file in your browser to launch the app.

## How to Use
1. **Adding a Transaction**:
   - Enter the description of your transaction in the text input field.
   - Enter the amount in the number input field.
   - Click either the **Earnings** button (for income) or the **Expense** button (for expenditures).
   
2. **Viewing Transactions**:
   - The transaction will appear under the "Transactions" section with either a 'C' for credits or 'D' for debits.
   - Your total balance will be updated accordingly.

3. **Balance Update**:
   - The **Your Balance** section will display the current balance reflecting all added transactions.

## Contributing
Feel free to fork this repository and submit pull requests if you'd like to improve or extend the functionality of this Expense Tracker app.

---

Enjoy using the Expense Tracker to manage your finances!

