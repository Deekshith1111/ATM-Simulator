# ATM-Simulator
The given code simulates an ATM machine functionality with basic features such as checking balance, withdrawing money, depositing money, and exiting the system. Below is the description of the code:

1. **Function Definition**:
   - The code defines a function named `ATM()`.

2. **Initial Balance**:
   - The initial balance is set to 10000.

3. **User Interaction**:
   - The program prints a welcome message for the ATM simulator.
   - It prompts the user to input their PIN.
   - Options are displayed for the user to choose from: Balance check, Withdrawal, Deposit, or Exit.

4. **Transaction Handling**:
   - The user's selected option is stored in the variable `option`.
   - Based on the option selected, the program executes the corresponding functionality.
   - If the option is 1, it prints the outstanding balance.
   - If the option is 2, it prompts the user to input the withdrawal amount, checks if the balance is sufficient, and updates the balance accordingly.
   - If the option is 3, it prompts the user to input the deposit amount and adds it to the balance.
   - If the option is 4, it prints "Exited" and terminates the program.
   - If an invalid option is selected, it prints a message stating "No Transaction Selected".

5. **Description**:
   - There is no loop to allow for multiple transactions; once a transaction is completed, the program terminates.

Overall, the code provides a basic simulation of ATM functionality but lacks robustness and flexibility for real-world usage. It could be improved by adding a loop for multiple transactions until the user chooses to exit.
