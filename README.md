# Shared Wallet
I this project, I coded a shared wallet via Smart Contracts on Remix. There are two Smart Contracts that run the shared wallet logics. The first called "SharedWallet" is where the functions for receiveing and withdrawing ether are written. Another called "Allowance" is where the functions of how the allowances are distributed for each shared wallet member are written. The "Ownable" Smart Contract from OpenZeppelin was also implemented, since it is an already audited Smart Contract for ownership management. The two Smart Contracts were separated in two files and, then, properly integrated.

## Real World Use Cases
This shared wallet can be used in the following examples of real world use cases:
- Children getting allowance per day/week/month
- Employer gives employee allowance for travel
- Business gives other business budget for expenses

## Wallet Functionality
The following figure describes the shared wallet functionality.
![Shared Wallet Functionality](https://github.com/EWCunha/Shared-Wallet/blob/main/Shared%20Wallet%20Functionalities.png)

Giving more details, anyone is able to make deposits in this shared wallet. Regarding withdrawals, the onwer can withdraw an unlimited amount, i. e. he can withdraw from all the other members' allowances. On the other hand, the non-owner members maximum withdrawal amount is the balance of their respective allowance. Furthermore, only the owner can change the allowances of each member.

## Code Challenges
- Deposit funds with fallback function (receive)
- Withdrawal function
- Permissions using modifier

## What I Learned
- Use fallback functions (receive).
- Properly code a withdrawal function.
- Give specific permissions with modifiers.
- Import my own and third parties (OpenZeppelin) Smart Contracts.
- Integrate different Smart Contracts with the `is` keyword.
- Properly write events and emit them.
- Override existing functions from a third party Smart Contract.
