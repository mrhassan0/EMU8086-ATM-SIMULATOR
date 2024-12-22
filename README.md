# EMU8086-ATM-SIMULATOR
This EMU8086 ATM simulation project models basic ATM operations like PIN authentication, user handling, balance check, deposits, withdrawals, transaction log, PIN change, fund transfers, account locking, and logout. It demonstrates assembly programming with real-world functionality in mind.

Features:
1. PIN Authentication
Secure login system that ensures only authorized users can access their accounts by entering a valid PIN.
2. PIN Lock
Protects the system by locking access after a certain number of failed PIN entry attempts, preventing unauthorized access.
3. User Handling
Supports up to 2 users, allowing for easy management of multiple accounts within the simulation.
4. Balance Check
Press 1:
Enables users to view their current account balance with a simple command.
Additional Functionality:
6. Deposit Money
Press 2: Deposit money into the user’s account.
Users can add any amount, and their balance will be updated accordingly.
7. Withdraw Money
Press 3: Withdraw money from the user’s account.
Ensures that the user does not withdraw more than their available balance.
8. Transaction Log
Press 4: View transaction history.
Displays a detailed log of deposits, withdrawals, and account balance changes.
9. Logout
Press 0: Log out and exit the system, ensuring that all session data is cleared.

Built with:
EMU8086 – A simulation tool for programming in 8086 assembly language.
This project serves as a demonstration of assembly programming and how microprocessor simulations can model real-world applications, providing an understanding of basic ATM system functions and security features.
