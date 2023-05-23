# Smart-Wallet-test2
A smart wallet based on a Solidity smart contract is a decentralized application that allows users to store and manage their funds in a secure and transparent blockchain environment.

The contract has the following main functions:

Deposit: Users can deposit Ether (ETH) into their wallet balance by sending ETH to the contract address. The deposited amount must be greater than zero.

Withdraw: Users can request a withdrawal of a specific amount of ETH from their wallet balance. To successfully withdraw, the amount must be greater than zero and not exceed the available balance in the wallet. Upon withdrawal confirmation, the requested amount of ETH will be sent back to the user's address.

Get Balance: Users can retrieve the current balance of their wallet.

Get Contract Balance: The contract owner can obtain the total balance of the contract, which includes the sum of all user deposits.

The contract also includes the onlyOwner modifier, which restricts certain functions, such as obtaining the contract's total balance, to the contract owner. This provides an additional level of security and control.

For each deposit or withdrawal, the contract emits Deposit and Withdrawal events, respectively, which can be used to track operations and conduct auditing.

It is important to note that before using this smart contract in real-world conditions, thorough testing and proper security checks should be conducted to minimize risks and protect users from vulnerabilities.
