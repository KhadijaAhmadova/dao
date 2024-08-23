## DAO

A simple Decentralized Autonomous Organization implemented in Solidity.

-   Contract controlled by a DAO
-   Every transaction that the DAO wants to send has to be voted on
-   ERC20 tokens will be used for voting


### Requirements
- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

### Installation
```bash
git clone https://github.com/KhadijaAhmadova/dao
cd dao
```
Install Openzeppelin library
```bash
forge install OpenZeppelin/openzeppelin-contracts@v4.8.3
```
Add `remappings = ["@openzeppelin/contracts/=lib/openzeppelin-contracts/contracts/"]` in `foundry.toml`.

> Note: If you install the latest version of openzeppelin contracts, this codebase won't work. Be sure to install `v4.8.3`.