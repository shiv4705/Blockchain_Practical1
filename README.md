In a peer-to-peer (P2P) fund transfer system, transactions between users must be stored securely, verified, and immutable to ensure trust and transparency. Blockchain technology can be leveraged to achieve this goal. Each block in the blockchain will represent a set of fund transfer transactions, ensuring that the data remains secure, validated through cryptographic puzzles, and immutable unless explicitly modified for testing or auditing purposes.

Perform following tasks:

I. Create a Blockchain with 5 Blocks
  •	Build a blockchain structure where the first block is the genesis block.
  •	Each block stores a set of fund transfer transactions between users.
  •	Each block will include:
    o	Block Version
    o	Timestamp
    o	Transaction Data
    o	Hash of the Previous Block

II. Implement Mining Logic to Validate Blocks
  •	Develop a mining process that uses cryptographic mathematical puzzles (like Proof of Work).
  •	Miners must solve these puzzles to add new blocks to the blockchain.

III. Set Difficulty for Blocks
  •	Define and set a difficulty level for mining each block, ensuring the system’s security by    controlling block creation time.

IV. Define Block Parameters
  •	Each block will include the following parameters:
    o	Block Version: Indicates the block structure version.
    o	Timestamp: Exact time when the block was created.
    o	Transaction Data: Financial transactions (e.g., Alice sends 10 BTC to Bob).
    o	Previous Hash: Hash of the previous block in the chain.

V. Verify the Blocks
  •	Implement logic to validate each block by:
    o	Checking its hash and previous hash linkage.
    o	Ensuring the cryptographic puzzle is solved correctly.

VI. Access All Financial Transactions
  •	Implement functionality to retrieve and display all stored financial transactions across      the blockchain.

VII. Modify Block Data from Ledger (For Testing)
  •	Allow authorized modifications of transaction data within the blockchain to simulate real-    world audit or debugging processes.

Implement following functionality using NodeJS.

Include functions to:
  •	Add transactions to blocks.
  •	Perform mining and validate blocks.
  •	Access and retrieve transaction history.
  •	Modify and verify block data for testing purposes.
