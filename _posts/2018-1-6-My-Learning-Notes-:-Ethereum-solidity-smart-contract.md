[Code on Git](https://github.com/vivek-bombatkar/Ethereum-solidity-smart-contract)




### 1. Online portal to practice smart contract
http://remix.ethereum.org


#### 1.1 Write code in editor...

<img src="./pics/a_complie_contract.JPG" width="300" height="200" />

#### 1.2 Hit "Start to compile" in "Compile" tab, in between to validate code.

<img src="./pics/b_complie_contract.JPG" width="300" height="200" />

#### 1.3 To deploy contract on blockchain, select name of the contarct from drop down and hit "Create" from "Run" tab. With this each contract gets its unique address representing the block index of blockchain.


<img src="./pics/c_publish_contract_on_blockchain.JPG" width="300" height="200" />

#### 1.4 You will see the contract deployed and ready to execute...

<img src="./pics/d_execute_contract.JPG" width="300" height="200" />

#### 1.5 Do watch the debug messages for better understanding.

<img src="./pics/e_debuging_execution_logs.JPG" width="300" height="200" />

#### 1.6 We could call a contract by specifing its address insted of creating new opbject, 
```
new CalledContract(); VS CalledContract(0x0dcd2f752394c41875e259e00bb44fd505297caf);
```
<img src="./pics/f_call_contract_by_address.JPG" width="300" height="200" />

<img src="./pics/g_call_contract_by_address.JPG" width="300" height="200" />
 

### 2. Geth

Geth is the C L I or command line interface for running a full Ethereum node, also works with windows cmd.

https://geth.ethereum.org/downloads/


geth console:
```
geth --datadir data --networkid 123 --nodiscover --maxpeers 0 console

personal.new Account
```

1. Geth is used to mine, in other words, to create blocks that are published to the Ethereum blockchain. The miner receives Ethereum currency or "Ether" as a reward for doing so.
```
geth --mine --datadir data --networkid 123 --nodiscover --maxpeers 0 --verbosity 6 console
```

2. Geth is used to create and manage Ethereum accounts. Accounts can store Ether. Geth also lets you transfer Ether between accounts . This transfer of Ether between accounts is known as a transaction.
```
geth --datadir data --networkid 123 --nodiscover --maxpeers 0 account list > output.txt

console > personal.new Account
```

3. Geth is used to create contracts. Contracts can receive transfers just like regular accounts. However, they can also receive more complicated transactions that run code, and optionally, update the state of the contract.



```
console
> loadScript('gethload.js')
> checkAllBalances()
> checkAllBalances()
  eth.accounts[0]:      0x50e663e7eb53bc247210cf61c465d562e0255f58      balance: 0 ether
  Total balance: 0 ether


geth --mine --datadir data --networkid 123 --nodiscover --maxpeers 0 --verbosity 6 console
<<<run for 10 to 15 minutes, then close the CMD and open new>>>

console
> loadScript('gethload.js')
> checkAllBalances()
> checkAllBalances()
  eth.accounts[0]:      0x50e663e7eb53bc247210cf61c465d562e0255f58      balance: 3752.5 ether
  Total balance: 3752.5 ether
  
personal.unlockAccount(eth.accounts[0])  

```


#### Ethereum Natural Specification Format
https://github.com/ethereum/wiki/wiki/Ethereum-Natural-Specification-Format

### 3. My learning resources
https://github.com/magonicolas/Ethereum-Solidity
https://www.youtube.com/watch?v=kWZ_XLZ61yg

https://www.youtube.com/watch?v=aV8C77xAaQA
https://www.youtube.com/watch?v=289EzMOHYnQ
https://www.youtube.com/watch?v=Li0Loy8VRp4
https://github.com/turboprep/geth-tutorial/tree/master/voting2

https://www.youtube.com/watch?v=V457ca7nxgU
https://www.youtube.com/watch?v=qChbuhCQBBg

https://ethereum.github.io/browser-solidity/#optimize=false&version=soljson-v0.4.21+commit.dfe3193c.js

https://medium.com/etherereum-salon/hello-ethereum-solan-contract-4643118a6119


### TODO
- Run contract on private blockchain with Geth.
Build Custom logic for validations.

- Build DAP with python

https://medium.com/python-pandemonium/develop-your-first-python-app-for-decentralized-stellar-network-7eb6eeae060a
