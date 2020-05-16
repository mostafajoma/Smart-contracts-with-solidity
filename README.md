# Smart-contracts-with-solidity
smart contracts to automate some finances.

## Background 

This project contains three smart contracts to automate some finances to increase transparency, and to make accounting and auditing practically automatic for a new Startup.


## Contracts 
* **First Contract** 
    * `AssociateProfitSplitter` 
    This contracts accept Ether into the contract and divide the Ether evenly among the recipient associate level employees.
    This will allow the Human Resources department to pay employees quickly and efficiently.

This contract was deployed and tested on Kovan Test Network
contract address : 0x6b1A019C2904c4215A4Eb47736da3aE1047d55cB

* **Secound Contract** 
    * `TieredProfitSplitter`
    This contract distributes different percentages of incoming Ether to employees at different tiers/levels.
    For example, 
     * the CEO gets paid 60%.
     * CTO 25%.
     * Bob gets 15%.

This contract was deployed and tested on Kovan Test Network
contract address : 0xc9bD989f322aef61Be35eBf85b96f41AC3b9ad7D

* **Third Contract**
    * `DeferredEquityPlan`
    This contract models traditional company stock plans, and it will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a New employee.

This contract was deployed and tested on Kovan Test Network
contract address : 0xd0d820597105058aC3dc0945c6AC6288228C95A9

Feel Free to clone the repo and test it. 

