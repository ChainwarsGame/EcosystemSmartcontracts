# ChainWars Essence (CWE) - Blockchain Gaming Ecosystem

## **Project Overview**
ChainWars Essence (CWE) is the core blockchain-based token and economy powering the ChainWars Play-to-Earn (P2E) strategy card game. CWE is designed as an ERC-20 token with staking, NFT integration, governance mechanisms, and a burn system to maintain economic sustainability. This repository contains the smart contracts and development resources for the CWE token and its associated ecosystem.

## **Features**
### **Token (CWE) - ERC-20 Standard**
- **Fixed Supply**: 1,000,000,000 CWE (Max Supply)
- **Burnable**: Reducing supply via staking, crafting, and game fees
- **Mintable**: Only staking and game contracts can mint rewards
- **Governance-Ready**: Transferable to a DAO for community control

### **Play-to-Earn Mechanics**
- **PvP Rewards**: Players earn CWE by winning battles
- **Staking System**: Earn passive rewards by staking CWE
- **NFT Utility**: Use CWE for NFT upgrades, crafting, and lootboxes

### **Deflationary Burn Mechanisms**
- **Battle Tax**: A portion of PvP rewards are burned
- **Lootbox Openings**: CWE is burned when opening lootboxes
- **Crafting System**: NFT crafting consumes CWE
- **Marketplace Fees**: A small % of marketplace transactions is burned

### **DAO Governance (Planned Feature)**
- **Voting System**: CWE holders can vote on game and economy decisions
- **Community-Owned Treasury**: Reward pools managed by DAO votes
- **Economic Adjustments**: Stakeholders control reward rates and burn percentages

## **Smart Contracts Overview**
| **Contract**            | **Type**   | **Purpose** |
|------------------------|----------|-------------|
| CWE Token Contract    | ERC-20   | Core token for ChainWars economy |
| PvP Reward Contract  | Custom   | Manages battle rewards and payouts |
| Staking Contract      | Custom   | Allows players to stake CWE for passive income |
| NFT Staking Contract | Custom   | Stake NFTs for additional rewards |
| Lootbox Contract     | ERC-721  | Provides randomized NFT rewards |
| NFT Crafting Contract | Custom   | Upgrades and combines NFTs |
| Marketplace Contract | Custom   | Enables NFT and CWE trading |
