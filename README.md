# Functions and Errors Project

This project is smart contract developed in Solidity. It's a contract that demonstrates the use of require(), assert(), and revert() statements in Solidity.

## Description

 It’s a smart contract that allows you to deposit and withdraw amounts, and even end the contract using the three functions. It includes a public string variable greet that returns “Hello World!” and a public unsigned integer balance that keeps track of the contract’s balance.

## Getting Started

### Installing

Install [Truffle](https://github.com/trufflesuite/truffle)

   ```bash
   npm install -g truffle
   ```

### Executing program

Start Truffle console in development mode
   ```bash
   truffle develop
   ```
In the Truffle console, execute
   ```bash
   compile
   migrate
   ```
If you want to remigrate existing contracts, run `migrate --reset` instead of simply `migrate`.

### Test your contract
   In the interactive Truffle console, run the following commands:
   ```javascript
   instance = await HelloWorld.deployed()
      instance.greet()
      instance.deposit()
      instance.withdraw()
      instance.endContract()
```

### Authors 
Marl Shane G. Esteron
