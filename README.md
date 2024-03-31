# ERC20 and Vault Contracts

This repository contains ERC20 and Vault contracts for managing tokens and securely storing them.

## ERC20 Contract

The ERC20 contract implements the standard ERC20 interface, which allows for the creation and management of tokens on the Ethereum blockchain. It provides functionalities such as transferring tokens between addresses, approving spending allowances, and checking token balances.

### Features
- Standard ERC20 functionality compliant with the ERC20 token standard.
- Support for transferring tokens between addresses.
- Approving spending allowances for other addresses.
- Checking token balances.

### Usage
1. Deploy the ERC20 contract on the Ethereum blockchain.
2. Interact with the deployed contract using compatible wallets or smart contracts.
3. Use standard ERC20 methods such as `transfer`, `approve`, `transferFrom`, and `balanceOf` to manage tokens.

## Vault Contract

The Vault contract provides a secure way to store tokens by allowing only authorized addresses to deposit and withdraw tokens. It acts as a custodian for tokens and ensures that only permitted actions are executed.

### Features
- Secure token storage with permissions management.
- Only authorized addresses can deposit or withdraw tokens.
- Owner-controlled access to manage permissions.

### Usage
1. Deploy the Vault contract on the Ethereum blockchain.
2. Set permissions for addresses that can deposit or withdraw tokens.
3. Use the `deposit` method to add tokens to the vault.
4. Use the `withdraw` method to retrieve tokens from the vault, subject to permissions.
