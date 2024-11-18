# Merkle Tree Assignment

This assignment focuses on building and understanding [Merkle trees](https://en.wikipedia.org/wiki/Merkle_tree), an important data structure in blockchain technology. Students will implement core functions for creating and verifying Merkle proofs, which have applications in blockchain systems like airdrops, decentralized verification, and efficient data authentication.

## Why Merkle Trees?
Merkle trees are used to validate data integrity and are essential in blockchain technology. They allow for efficient verification of data stored in large datasets, like transactions on the blockchain. Use cases include:
- **Airdrops**: Validating eligible participants without revealing the full participant list.
- **Data verification**: Verifying if data has been altered without needing to download the entire dataset.
- **Proof of membership**: Used in systems like Bitcoin to verify transaction inclusion in blocks.

## Functions to Implement
1. **build_merkle_tree** - Construct the Merkle tree from a list of leaf values.
2. **generate_merkle_proof** - Generate a Merkle proof for a specific leaf node, which includes the hash of the leaf and its path of sibling hashes up to the root.
3. **verify** - Verify if a given Merkle proof matches the root hash, ensuring the leaf is part of the Merkle tree.

## Instructions to Run

1. Clone the repository
2. Navigate to the repository
3. run `make`
4. run `./main`
5. All the code that you'll have to edit is in `main.cpp`. Please take a moment to read every function carefully.

## Additional Notes
- Ensure you have `g++` installed to compile the code.
- To modify or extend the code, you may want to look at `main.cpp` and see example usage of each function.
- The Merkle tree is built from a list of leaf nodes. Each leaf node can represent a hash of data (e.g., transactions or messages). The hash functions used in this assignment ensure the integrity and immutability of data.
- Merkle Trees are integral in ensuring the authenticity of data in systems such as blockchain and cryptocurrency, where a Merkle root is used to represent the entire dataset.
- This assignment will introduce you to the importance of cryptographic proofs in modern decentralized systems and how Merkle proofs are used for verifying data in these systems with minimal computational overhead.

## Deliverables
1. Make sure your code passes all test cases. You can use the `display_tree` function to debug. 

This assignment provides hands-on experience with core blockchain data structures, helping students build a strong foundation for further studies in blockchain development.
