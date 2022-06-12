# Problem

## Bank DAO

Create ERC-20 token which has its supply controlled by DAO. Only the DAO should be able to mint new tokens, as well as burning the tokens. 
Structure of the DAO: ????

### Burning
Tokens for burning have to be found on the DAO's account, max amount for burning can be 10% of the current supply. Time between burning events should be at least 1M. 

### Minting
DAO can mint tokens as well. Max amount for minting can be 10% of the current supply. Time between minting events should be at least 1M. Minted tokens are generated to the DAO account. 

### Quorum
Quorum for reaching a decision for any of this topics should be min of 40%. Proposal can be active for 1month, after that they are considered stale if 40% of the DAO owners did not vote. If the proposal has more than 40% of votes it will be considered accepted and ready for execution.

