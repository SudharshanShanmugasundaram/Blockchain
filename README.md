This is an implementation of a bsic general purpose Blockchain which can be extended to suffice your imagination.

# Blockchain
A blockchain is a growing list of records, called blocks, which are linked using cryptography.Each block contains a cryptographic hash 
of the previous block,a timestamp, and transaction data (generally represented as a merkle tree root hash).By design, a blockchain is 
resistant to modification of the data. It is "an open, distributed ledger that can record transactions between two parties efficiently 
and in a verifiable and permanent way".For use as a distributed ledger, a blockchain is typically managed by a peer-to-peer network 
collectively adhering to a protocol for inter-node communication and validating new blocks. Once recorded, the data in any given block 
cannot be altered retroactively without alteration of all subsequent blocks, which requires consensus of the network majority. Although 
blockchain records are not unalterable, blockchains may be considered secure by design and exemplify a distributed computing system with 
high Byzantine fault tolerance.Decentralized consensus has therefore been claimed with a blockchain.

*Source : [Wikipedia](https://en.wikipedia.org/wiki/Blockchain)*


# Requirements
1. Python
2. Flask
3. Postman
4. Requests

*The overall implementation was inspired by [this](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46) blog post on Medium.*
