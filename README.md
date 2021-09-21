# SmartContracts
SmartContracts for Minxie

Minxie features 3 smart contracts:

1. Minxie.sol - this contract automically creates a new liquidity pool on pancake swap using UniSwaps pair code directly in the smart contract. 
2. masterMinx.sol - this contract is the master of Minxie.sol that is able to call the rebase function on Minxie.sol. The rebase reduces the circulating supply cause a rise in price similar to a burn. 
3. MinxieOracle.sol - this contract is to get the latest price information on the minxie token in relation to swapping to BNB and for swapping BNB to BUSD stable coin. 
