# Terminology

## BE

Block Explorer

## BCT

Block Confirm Time

## BGI

Block Generation Interval

## BGT

Block Generation Time

## CLI

Command Line Interface

## DGOS

Distributed Governance Organization Syndicate

## DPoR

Delegated Proof of Reputation

## DPoS

Delegated Proof of Stake

## FB

Full Block

## FBN

Full Block Node

Replicate ISAG information. Replication information can be distributed to other nodes.

## FVM

FINL Virtual Machine

## IS

Index Server

IS manages information about the entire mainnet system and can control the system.

It provides the function of whether to participate in the consensus group and the selection of the node role. It provides functions such as network initialization, save, update, and restart. Provides node startup and shutdown functions. Provides functions such as adding, fine-tuning, and deleting topics by cluster to the Kafka/Zookeeper cloud network. Genesis contract creation function is provided. Provides functions to start, stop, or restart block generation.

## ISA

Index Server Agent

## ISAG

Index Server Agent Global

It has a duplicate of the information stored in the IS.

If an external node wants to check the information stored in the IS, it can acquire the necessary information through the ISAG instead of directly accessing the IS.

## KFK

Kafka

## NN

Network Node ( including ISA, SCA, NNA)

## NNA

Network Node Agent ( = Block Producer )

#### Consensus group network information update and configuration function

P2P main network update function. P2P subnetwork update function P2P subnetwork and P2P main ne twork configuration function according to node information.

#### Node security update function

Automatic firewall setting function according to node and network information. \[Block creation start, reception, verification, delivery function] Function to create and verify blocks Function to deliver the created block to other consensus groups Fu nction to deliver the created block to the local SCA.

#### Transaction processing function

Transaction reception function from Local SCA.

## PBH

Previous Block Hash

## PoW

Proof of Work

## PoS

Proof of Stake

## RTT

Round Trip Time

## SC

Smart Contract

## SCA

Smart Contract Agent

#### Contract reception, verification, storage function

User contract reception, verification, and storage functions entered through the distributed scheduler Contract reception, verification, and storage functions through ISA.

#### Transaction creation and storage function

The non-duplicate key value given to the contract and the hashed value of the contract are bundled tog ether and called a transaction. Create and store these transactions.

#### Block information reception function

Receive block information generated by the local consensus node.

## TX

Transaction

## ZKP

Zookeeper
