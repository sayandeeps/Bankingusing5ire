## Banking App Using BlockChain
first comile and deploy the smart contract in 5ire ide
```solidity
pragma solidity ^0.8.18;


contract Bank{
    int bal;
    constructor() public{
        bal=1;
    }
    function getBalance() view public returns(int){
        return bal;
    }
    function withdraw(int amt) public{
        bal=bal-amt;
    }
    function deposit(int amt) public{
        bal = bal + amt;
    }

}
```
###  Make sure you have metamask wallet 
1. You can claim free 5ire coins from the [5ire faucet](https://explorer.5ire.network/faucet)
2. Also dont forget to chage the explorer 5ire network to EVM chain (Also if EVM Faucet is not working you can claim native coins and swap)