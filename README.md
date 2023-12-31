# ERC1155-Foundry
Features of the contract :

### 1.  Tiered Tokens:
             The contract has 5 tiers of tokens. Each tier will be associated with a unique tokenId, ranging from 1 to 5.

### 2. Minting Functionality:
             The contract includes a minting function that allows whitelisted users to mint tokens by paying a specific price in Ether. The initial prices for each tier are as follows:

    Tier 1: 2 Ether

    Tier 2: 1 Ether

    Tier 3: 0.75 Ether

    Tier 4: 0.5 Ether

    Tier 5: 0.1 Ether

    ***These prices can be modified by the owner of the contract***

Minting Limit: Whitelisted users are not allowed to mint more than 20 tokens for each tier.

### 3. Burning Mechanism: 
            The contract includes a burning function that allows token owners to burn their tokens and receive a small refund. The refund is fixed at 0.05 Ether for all tiers, regardless of the tier's initial price.
