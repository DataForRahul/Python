ATM Machine Simulator

Welcome to the ATM Machine Simulator project! This project simulates basic ATM operations, such as checking balance, withdrawing money, depositing money, and changing the PIN. The application ensures a user-friendly experience with robust error handling and security measures.

Project Description
This project involves creating an ATM simulation using Python. The key functionalities include:

Balance Inquiry: Check the current balance.
Withdrawal: Withdraw a specified amount from the account, provided there are sufficient funds.
Deposit: Deposit a specified amount into the account.
PIN Change: Change the account PIN and ensure the user verifies the new PIN before proceeding with other transactions.
Key Features
User Authentication: Ensures that only users with the correct PIN can access the account.
Dynamic PIN Update: After changing the PIN, the user must re-enter the new PIN to continue transactions.
Robust Error Handling: Validates user inputs to prevent errors and invalid transactions.
Balance Updates: Reflects real-time balance updates after withdrawals and deposits.
Thought Process and Implementation
Initial Setup
User Class: Created a User class to encapsulate user-specific data such as PIN, balance, and name. This class includes methods to update the balance and PIN.
ATM Simulation Function: Designed the atm_simulation function to interact with the user, providing options to check balance, withdraw, deposit, change PIN, and exit.
Enhancements
Refactored Balance Update Logic: Moved the balance update logic into the User class to adhere to the principles of object-oriented programming, making the code more modular and maintainable.
PIN Update Method: Added an update_pin method to handle PIN changes within the User class, ensuring that all user-specific operations are encapsulated within the class.
Dynamic PIN Re-entry: Incorporated a mechanism to prompt the user to re-enter the new PIN after changing it. This ensures the new PIN is verified before proceeding with other transactions.
Error Handling
Input Validation: Added checks to validate user inputs, ensuring that PINs and transaction amounts are numeric.
Graceful Error Messages: Implemented user-friendly error messages to guide users in case of incorrect inputs or insufficient balance.
Testing and Execution
Multiple User Instances: Created multiple user instances to simulate different users interacting with the ATM.
Main Function: Designed a main function to initiate the ATM simulation for different users, facilitating easy testing and demonstration.
