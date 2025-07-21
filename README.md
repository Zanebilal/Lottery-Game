

# Foundry Smart Contract Lottery

# Project Title

🎟️ Raffle – A Provably Fair Raffle Game Powered by Smart Contracts

# Description 

Raffle Smart Contract is a decentralized lottery system that allow users to enter a raffle by paying a specified entry fee, with a randomly selected winner receiving the total collected funds from the contract, the contract ensures that all entries are verifiable and the winner is chosen using a secure, tamper-proof randomness mechanism (Chainlink VRF)

This project demonstrates how smart contracts can be used to create trustless, self-executing raffle systems with automated entry handling, winner selection, and prize distribution.

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [foundry](https://getfoundry.sh/)
  - You'll know you did it right if you can run `forge --version` and see your version
## Quickstart

```
git clone https://github.com/Cyfrin/foundry-smart-contract-lottery-cu
cd foundry-smart-contract-lottery-cu
forge build
```


# Usage

## Start a local node

```
make anvil
```

## Library

If you're having a hard time installing the chainlink library, you can optionally run this command. 

```
forge install smartcontractkit/chainlink-brownie-contracts@0.6.1 --no-commit
```

## Deploy to your local node

You need to have it running in another terminal in order for it to deploy.

```
make deploy
```



## Testing

for testing run this command


```
forge test
```

or

```
forge test --fork-url $SEPOLIA_RPC_URL
```

### Test Coverage

```
forge coverage
```