# Bockchain-prototype
There are three main components in Blockchain.

Client
Miners
Blockchain

CLIENT:- The Client class generates the private and public keys. During the object initialization, we create private and public keys and store their values in the instance variable.

MINOR:- The Miner is the one who picks up the transactions from a transaction pool and assembles them in a block. The miner has to provide a valid proof-of-work to get the mining reward. All the money that miner collects as a fee will be for him to keep. He may spend that money on buying goods or services from other registered vendors on the network, just the way a Client described above does.

BLOCKCHAIN:- Blockchain is a data structure that chains all the mined blocks in a chronological order. This chain is immutable and thus temper-proof.
