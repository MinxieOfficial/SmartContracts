# SmartContracts
SmartContracts for Minxie

MINX v1 features 1 liquidity generating token contract (SafeMoon fork)

1. 3% transaction tax for yield to all MINX holders
2. 3% transaction tax to add liqudity to pancake swap pool

MINX v2 features 3 smart contracts:

1. Minxie.sol - this contract automically creates a new liquidity pool on pancake swap using UniSwap's pair code directly in the smart contract. It features a rebase function that automatically reduces the circulating supply of MINX in existence.
2. masterMinx.sol - this contract is the master of Minxie.sol, it is able to call the rebase function on Minxie.sol, set the rebase percent, and set the frequency of rebases.
3. MinxieOracle.sol - this contract is to get the latest price information on the minxie token in relation to swapping to BNB and for swapping BNB to BUSD stable coin. 
