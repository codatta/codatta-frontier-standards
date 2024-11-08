# 🏦 Crypto Account Annotation - Taxonomy and Schema


## 🌟 Introduction

**Account annotation** is critical for enhancing transparency and understanding within blockchain ecosystems. This process involves assigning metadata to blockchain addresses, providing insights into the identities, purposes, and behaviors associated with them. Account annotations are valuable across a range of applications, including:

- **🛡️ AML (Anti-Money Laundering) Management**: Account annotations help identify and monitor addresses involved in high-risk or illicit activities, such as money laundering or fraud. This enhances compliance with regulatory requirements and supports law enforcement investigations.
- **📈 On-Chain Marketing and Trend Analysis**: By understanding user behavior and activity patterns, companies can conduct targeted marketing and analyze trends in user engagement, token usage, and DeFi participation. Annotated data allows for in-depth insights into audience segments and market trends.
- **⚠️ Risk Management**: Financial institutions and crypto platforms leverage account annotations to assess risks associated with specific addresses, such as identifying potentially malicious or high-risk actors. This supports a proactive approach to security and compliance.
- **🌐 Reputation and Identity Systems**: Account annotations contribute to building reputation scores and trust networks by marking addresses with a history of positive or negative actions.

The taxonomy and schema provided here are designed to standardize data across these use cases, facilitating reliable, reusable account data across the industry.

> **Alternative Names**: Account annotation is also known as **address labeling**, **entity classification**, and **wallet tagging** within blockchain communities. Each term refers to the practice of categorizing blockchain addresses with meaningful metadata.


### 🤝 Call for Contributions
---
Codatta invites collaboration and contributions from research institutions, industry experts, and community members. If your organization or team is interested in enhancing these standards or proposing new use cases, please reach out. We welcome joint efforts to expand the taxonomy and address evolving industry needs.

For inquiries, contributions, or to propose a collaboration, please contact us at **[dev-opensource@codatta.io](mailto:dev-opensource@codatta.io)**.

## 📑 Source

The **Source** value provides information about how the given data entry was collected. We define five source values in the data model:

- **🌍 Ground Truth**: This method relies on conducting real-life transactions on-chain to identify blockchain addresses belonging to a specific entity. For example, depositing a small amount of ETH to identify addresses owned by a particular exchange.
- **🔍 Heuristic**: Clusters addresses using models based on publicly available information, such as transaction patterns. Examples include the Commonspend heuristic for UTXO chains.
- **🤖 Machine Learning**: Utilizes machine learning algorithms with on/off-chain data to create address clustering models.
- **📚 Research**: Relies on thorough research over publicly available information, especially useful during significant events in the space.
- **📥 External**: Gathers metadata from other open sources, like Etherscan.

## 🌐 Chain

The **Chain** indicates the blockchain or network where the address resides. The protocol has a fixed list of values defined in the data model, with flexibility to add new chains to accommodate metadata from emerging networks.

## 🏢 Entity

The **Entity** represents the owner of a given address, often at an organizational level. For instance, various Uniswap addresses for different purposes share the same entity name, "Uniswap." New entity values can be added as required by emerging networks.


## Category


Thought for 9 seconds

🏦 Crypto Account Annotation - Taxonomy and Schema
🌟 Introduction
Account annotation is critical for enhancing transparency and understanding within blockchain ecosystems. This process involves assigning metadata to blockchain addresses, providing insights into the identities, purposes, and behaviors associated with them. Account annotations are valuable across a range of applications, including:

🛡️ AML (Anti-Money Laundering) Management: Account annotations help identify and monitor addresses involved in high-risk or illicit activities, such as money laundering or fraud. This enhances compliance with regulatory requirements and supports law enforcement investigations.
📈 On-Chain Marketing and Trend Analysis: By understanding user behavior and activity patterns, companies can conduct targeted marketing and analyze trends in user engagement, token usage, and DeFi participation. Annotated data allows for in-depth insights into audience segments and market trends.
⚠️ Risk Management: Financial institutions and crypto platforms leverage account annotations to assess risks associated with specific addresses, such as identifying potentially malicious or high-risk actors. This supports a proactive approach to security and compliance.
🌐 Reputation and Identity Systems: Account annotations contribute to building reputation scores and trust networks by marking addresses with a history of positive or negative actions.
The taxonomy and schema provided here are designed to standardize data across these use cases, facilitating reliable, reusable account data across the industry.

Alternative Names: Account annotation is also known as address labeling, entity classification, and wallet tagging within blockchain communities. Each term refers to the practice of categorizing blockchain addresses with meaningful metadata.

🤝 Call for Contributions
Codatta invites collaboration and contributions from research institutions, industry experts, and community members. If your organization or team is interested in enhancing these standards or proposing new use cases, please reach out. We welcome joint efforts to expand the taxonomy and address evolving industry needs.

For inquiries, contributions, or to propose a collaboration, please contact us at dev-opensource@codatta.io.

📑 Source
The Source value provides information about how the given data entry was collected. We define five source values in the data model:

🌍 Ground Truth: This method relies on conducting real-life transactions on-chain to identify blockchain addresses belonging to a specific entity. For example, depositing a small amount of ETH to identify addresses owned by a particular exchange.
🔍 Heuristic: Clusters addresses using models based on publicly available information, such as transaction patterns. Examples include the Commonspend heuristic for UTXO chains.
🤖 Machine Learning: Utilizes machine learning algorithms with on/off-chain data to create address clustering models.
📚 Research: Relies on thorough research over publicly available information, especially useful during significant events in the space.
📥 External: Gathers metadata from other open sources, like Etherscan.
🌐 Chain
The Chain indicates the blockchain or network where the address resides. The protocol has a fixed list of values defined in the data model, with flexibility to add new chains to accommodate metadata from emerging networks.

🏢 Entity
The Entity represents the owner of a given address, often at an organizational level. For instance, various Uniswap addresses for different purposes share the same entity name, "Uniswap." New entity values can be added as required by emerging networks.

🗂 Category
The Category value provides detailed information about the purpose or sector of the address. The updated taxonomy is hierarchical, allowing for more precise classification and reducing overlap between categories. 
The protocol has a fixed list of values defined at the data model (as shown below) but new category values can be added to accommodate metadata from new blockchain networks.

Below is the new taxonomy for categories:

---

# **Finance**

## **Decentralized Finance (DeFi)**

*Description:* Financial applications developed on blockchain technology, facilitating open, accessible, and interoperable financial systems.

- **Exchanges (DEXs)**

  *Description:* Decentralized platforms where users can trade cryptocurrencies directly from their wallets without the need for an intermediary or custodian.

  - **Examples:** Uniswap, SushiSwap, Curve Finance

- **Lending and Borrowing**

  *Description:* Platforms that allow users to lend their assets for interest or borrow against their cryptocurrencies.

  - **Examples:** Aave, Compound, MakerDAO

- **Yield Farming and Liquidity Mining**

  *Description:* Strategies where users lock up their assets to receive rewards, often in the form of another token.

  - **Example:** Yearn.finance

- **Derivatives and Synthetic Assets**

  *Description:* Platforms offering financial instruments that derive their value from underlying assets, like cryptocurrencies.

  - **Examples:** Synthetix, dYdX

- **Insurance Protocols**

  *Description:* Offer decentralized insurance products built on blockchain to provide coverage against losses in various scenarios.

  - **Example:** Nexus Mutual

- **Prediction Markets**

  *Description:* Platforms where users can bet on the outcomes of future events, such as elections or market prices.

  - **Examples:** Augur, Gnosis

## **Financial Infrastructure and Services**

*Description:* Infrastructure and services on blockchain for payments, custodial services, and financial transactions.

- **Wallet Services**

  *Description:* Platforms that provide secure storage and management for cryptocurrencies and digital assets.

- **Payment Gateways and Processors**

  *Description:* Tools for accepting cryptocurrency payments, facilitating transactions for merchants and users.

  - **Examples:** NOWPayments, Superfluid

- **Centralized Exchanges and Trading Platforms**

  *Description:* Centralized platforms facilitating the buying, selling, and trading of various assets, including cryptocurrencies and fiat currencies.

## **Real-World Asset (RWA) Tokenization**

*Description:* Platforms that tokenize tangible assets, such as real estate, commodities, or art, allowing them to be represented and traded on the blockchain.

- **Art and Digital Collectibles**

  *Description:* Digital representations of art or collectibles, each token being unique or part of a limited series.

  - **Examples:** CryptoPunks, SuperRare

- **Real Estate Tokenization**

  *Description:* Platforms that represent ownership of real estate properties through tokens on the blockchain.

  - **Examples:** RealT, Propy

---

# **Business and Services**

## **Identity and Authentication**

*Description:* Technologies that provide decentralized solutions for verifying identities and managing access through blockchain.

- **Self-Sovereign Identity (SSI)**

  *Description:* Digital identities where individuals have control over their personal data.

  - **Examples:** uPort, Civic, SelfKey

## **Supply Chain and Provenance Tracking**

*Description:* Blockchain-based solutions to track and verify the journey of products across supply chains, improving transparency and authenticity.

- **Supply Chain Management**

  *Description:* Platforms that use blockchain to provide end-to-end visibility into supply chain operations.

  - **Example:** VeChain

- **Anti-Counterfeiting**

  *Description:* Solutions that use blockchain to verify product authenticity.

  - **Example:** Arianee

## **Content Sharing, Intellectual Property, and Rights Management**

*Description:* Platforms that leverage blockchain for content sharing, enabling users to maintain control and ownership over their data and media.

- **Streaming**

  *Description:* Services providing streaming media content using blockchain for content distribution and payment processing.

  - **Examples:** Livepeer, Audius

- **Music**

  *Description:* Platforms allowing creators to control and receive royalties.

  - **Example:** Opus

## **Medical Data Management**

*Description:* Solutions to secure and share patient data.

- **Examples:** FarmaTrust

## **Education and Certification**

*Description:* Blockchain-based credential verification for educational achievements and certifications.

- **Examples:** BitDegree, Odem

## **Sports and Entertainment**

*Description:* Applications related to sports products or services, including fantasy sports, collectibles, and betting platforms.

- **Examples:** Sorare, Chiliz

## **Data Marketplaces**

*Description:* Decentralized marketplaces for buying, selling, and sharing data.

- **Data Sharing Platforms**

  *Description:* Marketplaces where users can monetize their data.

  - **Examples:** Datum, Ocean Protocol

## **Decentralized Physical Infrastructure Networks (DePIN)**

*Description:* Networks that decentralize physical infrastructure services using blockchain technology.

- **File Storage**

  *Description:* Decentralized networks where users can store and retrieve files securely without relying on centralized servers.

  - **Example:** Filecoin

- **Compute Power Sharing**

  *Description:* Platforms that allow users to rent or share computational resources in a decentralized network.

  - **Example:** Golem

- **Decentralized Wireless Networks**

  *Description:* Community-built networks providing wireless connectivity services.

  - **Example:** Helium

- **Decentralized Energy Grids**

  *Description:* Platforms enabling peer-to-peer energy trading and decentralized energy management.

  - **Examples:** Power Ledger, Grid+

- **Decentralized Transportation Networks**

  *Description:* Systems that use blockchain to manage transportation services.

  - **Examples:** Dovu, DAV Network

- **Physical Asset Sharing Platforms**

  *Description:* Platforms facilitating the shared use or rental of physical assets.

  - **Example:** Origin Protocol

## **Advertising and Marketing**

*Description:* Blockchain solutions in advertising, allowing for new models and fraud prevention.

- **Attention Economy Models**

  *Description:* Platforms where users are compensated for their attention to ads.

  - **Example:** Brave Browser & Basic Attention Token (BAT)

- **Ad Fraud Prevention**

  *Description:* Solutions to detect and prevent ad fraud.

  - **Example:** AdEx

## **Charity and Philanthropy**

*Description:* Platforms leveraging blockchain for transparency in donations.

- **Charity Platforms**

  *Description:* Systems to track and ensure funds reach intended recipients.

  - **Examples:** Giveth, AidCoin

## **Gambling**

*Description:* Blockchain applications offering transparency and fair play.

- **Transparent Betting Platforms**

  *Description:* Platforms for placing bets transparently on blockchain.

  - **Examples:** FunFair, Edgeless

---

# **GameFi**

*Description:* Blockchain-based games that offer economic incentives to players.

- **Gaming NFTs**

  *Description:* Tokens that represent in-game assets, which players can own, sell, or use within gaming environments.

  - **Examples:** Axie Infinity, Decentraland

- **Virtual Real Estate**

  *Description:* Parcels of digital land in virtual environments.

  - **Examples:** The Sandbox, Somnium Space

# **Decentralized Autonomous Organizations (DAOs)**

*Description:* Blockchain-based entities where code replaces traditional management structures, and members make decisions collectively through votes.

---

# **Layer Two Solutions and Scalability**

*Description:* Technologies that enhance the scalability and efficiency of blockchains through secondary frameworks.

- **Payment and State Channels**

  *Description:* Off-chain solutions for fast transactions.

  - **Example:** Raiden Network

- **Sidechains**

  *Description:* Independent blockchains that run parallel to the main chain.

  - **Examples:** xDai, Loom Network

- **Rollups**

  *Description:* Layer 2 scaling solutions that aggregate multiple transactions into one.

  - **Optimistic Rollups**

    *Description:* Assume transactions are valid, checked only when a dispute is raised.

    - **Example:** Optimism

  - **Zero-Knowledge Rollups (ZK-Rollups)**

    *Description:* Use cryptographic proofs to verify transaction validity.

    - **Example:** zkSync

- **Bridging Solutions**

  *Description:* Platforms providing interoperability solutions to connect different blockchain networks.

  - **Examples:** Polkadot, Cosmos

# **Enterprise and Government Applications**

*Description:* Blockchain applications tailored for enterprise and government use.

- **Digital Government Services**

  *Description:* Governmental initiatives using blockchain to provide digital services.

  - **Examples:** Republic of Georgia's Land Registry, Sweden's Land Registry

- **Central Bank Digital Currencies (CBDCs)**

  *Description:* Government-issued digital currencies operating on blockchain technology.

  - **Examples:** Marshall Islands' Sovereign (SOV), Petro (Venezuela)

- **Law Enforcement and Regulatory Agencies**

  *Description:* Addresses or wallets certified to belong to law enforcement agencies.

---

# **Privacy and Anonymity Solutions**

*Description:* Products or services that provide privacy solutions on the blockchain.

- **Mixers**

  *Description:* Services used to obscure the origins of cryptocurrency transactions.

  - **Examples:** Tornado Cash, Wasabi Wallet

- **Privacy Coins and Protocols**

  *Description:* Cryptocurrencies and protocols designed to provide enhanced privacy features.

  - **Examples:** Monero, Zcash

# **Security, Scams, and Malicious Activities**

*Description:* Covers malicious activities, scams, security threats, and their corresponding countermeasures within the blockchain ecosystem.

- **Ponzi and Pyramid Schemes**

  *Description:* Investment scams promising high returns using funds from new investors.

  - **Examples:** BitConnect, OneCoin

- **Phishing and Social Engineering Attacks**

  *Description:* Deceptive tactics to obtain sensitive information from users.

- **Rug Pulls**

  *Description:* Developers exit projects after securing investments.

- **Theft and Hacking Incidents**

  *Description:* Addresses linked to theft or hacking incidents involving cryptocurrency.

- **Illicit Financing and Terrorism**

  *Description:* Addresses involved in financing illegal activities.

- **Money Laundering Activities**

  *Description:* Addresses identified as being involved in money laundering.

- **Sanctioned Addresses**

  *Description:* Addresses sanctioned by government authorities.

- **High-Risk and Others**

  *Description:* Addresses associated with suspicious activities not covered elsewhere.

# **Oracles**

*Description:* Oracles act as bridges between blockchain smart contracts and external data sources.

- **Data Oracles**

  *Description:* Provide external data to smart contracts.

  - **Examples:** Chainlink, Band Protocol

- **Computation Oracles**

  *Description:* Perform off-chain computations for smart contracts.

  - **Example:** Provable

- **Human Oracles**

  *Description:* Rely on individuals to provide and verify data.

  - **Examples:** Augur, Kleros

---

# **SocialFi**

*Description:* Platforms that merge social networking with blockchain and decentralized finance (DeFi).

## **Decentralized Social Networks**

*Description:* Social media platforms where users own their data and content.

- **Examples:** Steemit, Lens Protocol

## **Social Tokens and Creator Economies**

*Description:* Tokens representing individuals, brands, or communities.

- **Examples:** BitClout, Roll

---
You're absolutely right, and I apologize for the oversight in the previous schema. The categories should reflect their hierarchical relationships, showing that subcategories are nested under their parent categories. Let me correct the JSON schema to properly represent the hierarchical taxonomy.

## 🛠 Updated Schema

We will modify the `category` field in the JSON schema to represent the hierarchical paths of categories. Each category will be an array of strings, where each string represents a level in the hierarchy from the top-level category to the most specific subcategory.

Here is the updated JSON schema:

```json
{
  "address": "string",
  "name": "string",
  "source": {
    "type": "string",
    "enum": ["Ground Truth", "Heuristic", "Machine Learning", "Research", "External"]
  },
  "chain": "string",
  "entity": "string",
  "category": {
    "type": "array",
    "items": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "description": "A hierarchical category path represented as an array of strings, e.g., ['Finance', 'Decentralized Finance (DeFi)', 'Exchanges (DEXs)']"
    },
    "description": "An array of category paths that the address or entity belongs to, based on the hierarchical taxonomy"
  },
  "submit_on": {
    "type": "string",
    "format": "date-time",
    "description": "The ISO timestamp of when the data was sourced, in the format YYYY-MM-DD HH:MM:SS"
  },
  "description": {
    "type": "string",
    "description": "A human-readable description of the address or entity"
  },
  "evidence_uri": {
    "type": "string",
    "format": "uri",
    "description": "The multimedia link of the evidence"
  },
  "submit_by": {
    "type": "string",
    "description": "The code of the operator, in the format 'operator:workflow', e.g., 'coinbase:workflowA' or 'circle:labelB'"
  }
}
```

### Explanation of the Changes

- **Category Field**: The `category` field is now an array of category paths. Each category path is itself an array of strings representing the hierarchy from the top-level category to the specific subcategory.

  - **Example**: For an address associated with Uniswap, a decentralized exchange, the category would be:

    ```json
    "category": [
      ["Finance", "Decentralized Finance (DeFi)", "Exchanges (DEXs)"]
    ]
    ```

  - This structure clearly demonstrates that "Exchanges (DEXs)" is a subcategory under "Decentralized Finance (DeFi)", which in turn is under "Finance".

### Sample Entry

Here's a sample JSON entry using the updated schema:

```json
{
  "address": "0x1234567890abcdef1234567890abcdef12345678",
  "name": "Uniswap V2: Router",
  "source": "Research",
  "chain": "Ethereum",
  "entity": "Uniswap",
  "category": [
    ["Finance", "Decentralized Finance (DeFi)", "Exchanges (DEXs)"]
  ],
  "submit_on": "2023-11-08T12:00:00Z",
  "description": "The main router contract for Uniswap V2, used for swapping tokens.",
  "evidence_uri": "https://etherscan.io/address/0x1234567890abcdef1234567890abcdef12345678",
  "submit_by": "codatta:annotation_team"
}
```

This sample shows how the hierarchical category path is represented, accurately reflecting the taxonomy.

---

## 🔄 Changes Made

- **Corrected Category Representation**: Updated the `category` field in the JSON schema to accurately represent the hierarchical relationships between categories and subcategories.

- **Hierarchical Paths**: Each category is now represented as a hierarchical path, showing the full lineage from the top-level category to the specific subcategory.

- **Examples Provided**: Included examples to demonstrate how to represent categories in the schema.

---

## 🗂 Updated Taxonomy Representation

To further clarify, here's how some categories would be represented in the hierarchical structure:

- **Exchanges (DEXs)**:

  ```json
  ["Finance", "Decentralized Finance (DeFi)", "Exchanges (DEXs)"]
  ```

- **Lending and Borrowing**:

  ```json
  ["Finance", "Decentralized Finance (DeFi)", "Lending and Borrowing"]
  ```

- **Supply Chain Management**:

  ```json
  ["Business and Services", "Supply Chain and Provenance Tracking", "Supply Chain Management"]
  ```

- **Gaming NFTs**:

  ```json
  ["GameFi", "Gaming NFTs"]
  ```

- **Mixers**:

  ```json
  ["Privacy and Anonymity Solutions", "Mixers"]
  ```

---

## 📜 Acknowledgment

We gratefully acknowledge the contributions of the Microscope Protocol for building a foundational framework that supports standardization in the industry. Their pioneering work has provided a significant foundation for the schema and taxonomy used here, advancing the practice of account annotation and making industry-wide standardization achievable. You can view their original taxonomy documentation at [Microscope Protocol - Taxonomy Documentation](https://github.com/microscopexyz/chainmetareader/blob/main/doc/taxonomy.md).