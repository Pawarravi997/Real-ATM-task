# Real-ATM-task


A console-based ATM system built in Python that simulates core banking operations using dictionaries for account data storage.



## Features
- 🔐 Secure login with account number and PIN verification
- 💰 Check account balance with account holder name
- 💵 Deposit money into account
- 💸 Withdraw money with insufficient balance handling
- 🔑 Change ATM PIN
- 🚪 Clean exit from the menu loop
- ⚠️ Input validation (handles invalid account numbers and non-numeric menu choices gracefully)

## Tech Stack
- Python 3
- Core concepts used: Dictionaries, Functions, Loops, Exception Handling (try/except)

## How It Works
1. User enters their account number and PIN to log in
2. On successful login, a personalized welcome message is displayed
3. User navigates a menu to perform banking operations
4. All account data is updated in real-time within the session

## Sample Accounts (for testing)
| Account No. | PIN  |
|-------------|------|
| 101         | 1234 |
| 102         | 123  |
| 103         | 431  |

## Run it
\`\`\`bash
python Realtime_ATM_Task.py
\`\`\`
