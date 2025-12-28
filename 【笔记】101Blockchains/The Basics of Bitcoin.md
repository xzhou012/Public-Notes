# C1. Introduction to Bitcoin
## What is Bitcoin
- a digital currency that allows people to send and receive money without relying on banks of financial institutions
- key features: decentralised, secure and transparent, finite supply, digital and borderless

## Bitcoin as Digital Money
### Key Features that Make Bitcoin Unique
- Immutability
- Security
- Pseudonymity
- Self-Custody
- Fixed Supply

# C2. Understanding Blockchain Technology
## Foundation of Bitcoin
- Blockchain technology: a decentralised and immutable ledger that records all transactions in a transparent and secure manner

> **Question: How is such a large ledger stored?**

### Key Characteristics of Blockchain
- Decentralisation
- Transparency
- Immutability
- Security

## How a Blockchain Works?
Block: transaction date, hash of the previous block, nonce and proof-of-work

## The Role of Cryptography in Blockchain Security
Two major cryptographic techniques used in Bitcoin are public-key cryptography and hash functions.
- Public Key: a cryptographic address generated from a private key, allowing users to securely receive Bitcoin transactions
- Private Key: a secret cryptographic code used to sign transaction, prove Bitcoin ownership and authorise fund transfer securely

## Decentralisation
Decentralised nature achieved through several mechanisms:
- consensus mechanisms: all transactions must be verified by the network through mining, preventing fraudulent activity
- full nodes: computers that store a complete copy of Bitcoin's blockchain, ensuring that transaction history remains intact
- open-source code

# C3. How Bitcoin Transactions Work
- Characteristics: irreversible, borderless, require network confirmations

## Anatomy of a Bitcoin Transaction
A typical Bitcoin transaction contains three main components:
- Input: the Bitcoin being spent, which comes from a previous transaction
- Digital Signature: cryptographic proof that the sender has authorised the transaction
- Output: the recipients and the amount of Bitcoin they are supposed to receive

Bitcoin is not stored in a single location, like a traditional bank balance. Instead, it exists in the form of unspent transaction outputs(UTXOs).

## Transaction Confirmations
Initiation-Broadcast-Confirmation-Transaction

![Confirmation of Transactions](pics/C1-Confirmation%20of%20Transactions.jpg)

For small transactions, 1-2 confirmations are usually sufficient. However, larger transactions, such as those involving high-value Bitcoin transfer or institutional transactions, typically require at least 6 confirmation to ensure security.

> **Question: Why Bybit didn't see the transfer before the transaction completed?**

## Bitcoin Transaction Fees
Transaction fees are calculated based on:
- size of the transaction
- network demand
- fee rate (satoshis per byte)

Bitcoin blocks have a limited size of 1 MB.

Users can choose from different fee options:
- high-priority fee: ensures quick confirmation, typically within the next block
- medium-priority fee: balances cost and speed, confirming within a few blocks
- low-priority fee: takes longer but saves on fees, often used for non-urgent transfers

## Unconfirmed Transactions
- low transaction fee
- network congestion
- dust transactions: very small transactions may be ignored by miners due to low incentives

Users can:
- wait for it to be confirmed
- used Replace-by-Fee (RBF): increase fee after broadcast
- use Child Pays for Parent(CPFP): attach fee to the original transaction
- rebroadcast the transaction

## The Role of Miners in Verifying Transactions
Proof-of-Work: solve complex mathematical problems to add new blocks to the blockchain

# C4. Bitcoin Mining Explained
Bitcoin mining serves three critical functions:
- issuing new Bitcoins
- securing transactions
- maintaining decentralisation

> **Question: If only the first one gets the reward for making the ledger, what do competitors get?**
> **Questions: Who set the questions?**

## How PoW Secures the Bitcoin Network
The core idea behind PoW is that it makes tampering with past transactions infeasible. If an attacker wanted to modify a previous transaction, they would need to redo the computational work for that block and all subsequent blocks, a task that would require immense computational power and energy consumption. This makes the Bitcoin blockchain highly secure and resistant to manipulation.

## Mining Process Step-by-Step
1. Transaction Collection
2. Creating a New Block
3. Solving the Proof-of Word Puzzle
4. Block Validation
5. Consensus and Block Addition
6. Reward Distribution

# C5. Acquiring Bitcoin
## How to Buy Bitcoin:
1. Choose a Bitcoin wallet
2. Select a reliable exchange
3. Create an account
4. Deposit funds
5. Buy bitcoin
6. Add bitcoin to your wallet

## Storing Bitcoin
- hot wallets
- cold wallets

# C6. Using Bitcoin in Everyday Life

# C7. The Economics of Bitcoin
- The 21 Mollion Bitcoin Limit
- Bitcoin as Digital Gold
- Why Bitcoin is Deflationary
- Bitcoin's Impact on Global Financial Systems
- How Bitcoin is Priced
- The Role of Institutional Investors in Bitcoin's Growth

# C8. Bitcoin Security and Risks
- built on a trustless system, once funds are lost or stolen, no way to recover them
- Bitcoin Scams: Ponzi Schemes, Fake Giveaways, and Phishing
- Avoiding Fraud: How to Identify Fake Exchanges and Wallets
- How to Secure Your Bitcoin Wallet
- Can Lost Bitcoins Be Recovered
- The Dangers of Keeping Bitcoin on an Exchange

## Common Attach Vectors
### 51% Attack
### Dusting Attack
A dusting attack involves sending tiny amounts of Bitcoin to thousands of addressess to track user transactions and deanonymise wallets.
To protect against dusting attacks, users should:
- Ignore and not move tiny Bitcoin amounts from unknown sources.
- Use privary wallets that automatically filter out dust transactions.

### Sybol Attack

# C9. Bitcoin Regulations and Legal Aspects
1. How Governments Around the World Treat Bitcoin
2. Bitcoin and Taxes
3. Bitcoin and Anti-Money Laudering Laws

# C10. Bitcoins vs. Other Cryptocurrencies
## Bitcoins vs. Ethereum
| Feature | Bitcoin | Ethereum |
|---------|---------|----------|
| Purpose | Digital currency | Smart contracts |
| Consensus | Proof-of-Work | Proof-of-Stake |
| Block Time | Roughly 10 min to confirm a block | Around 10 to 15 s for each new block |
| Flexibility | Fixed monetary system | Porgrammable blockchain, supports smart contract |
| Use Cases | Digital payments | DeFi, Web3, tokenisation |

## Bitcoin Forks
- Bitcoin Cash(BCH): created in 2017 due to disagreements over Bitcoin's scalability and block size, faster transactions and lower fees
- Bitcoin SV(BSV): created in 2018 due to further disagreements about block size, 128MB block size
- Litecoin(LTC): created in 2011, faster block time, different mining algo
- Bitcoin Gold(BTG): different mining algo

## Bitcoin vs. Altcoins

## Stablecoins vs. Bitcoin

# C11. The Future of Bitcoin
1. Bitcoin's Role in the Decentralised Economy
2. Will Bitcoin Replace Traditional Banking?
3. Can Bitcoin Become a Global Reserve Currency
4. The Role of Bitcoin in the Metaverse and Web3
> ***What is the Bitcoins' Lightning Network?***
5. Bitcoin's Challenges: Scalability, Adoption, and Regulation
6. Innovations in Bitcoin Development
   1. Taproot Upgrade(2021): increases Bitcoin's smart contract functionality
   2. Schnorr Signatures:
7. The Role of Bitcoin in DeFi
   1. Wrapped Bitcoin(WBTC): allows Bitcoin to be used in DeFi applications by converting it into an ERC-20 token
   2. Bitcoin SideChains(RSK, Liquid Network)
   3. Decentralised Bitcoin Lending Platforms

# C12. Getting Started with Bitcoin
## Buying Your First Bitcoin
## How to Track Bitcoin Prices and Market Trends
- Platforms: CoinMarketCap, TradingView, CoinGecko
- Analyse: price charts, market sentiment, BTC/altcoins market share, on-chain data