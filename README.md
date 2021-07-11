# Shared Wallet
I this project, I coded a shared wallet via Smart Contracts on Remix. There are two Smart Contracts that run the shared wallet logics. The first called "SharedWallet" is where the functions for receiveing and withdrawing ether are written. Another called "Allowance" is where the functions of how the allowances are distributed for each shared wallet member are written. The "Ownable" Smart Contract from OpenZeppelin was also implemented, since it is an already audited Smart Contract for ownership management. The two Smart Contracts were separated in two files and, then, properly integrated.

## Real World Use Cases
This shared wallet can be used in the following examples of real world use cases:
- Children getting allowance per day/week/month
- Employer gives employee allowance for travel
- Business gives other business budget for expenses

## Wallet Functionality


## Code Challenges
- Deposit funds with fallback function (receive)
- Withdrawal function
- Permissions using modifier

## What I Learned
