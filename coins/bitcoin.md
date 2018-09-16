---
layout: page
title: Bitcoin
excerpt: The first born...
---
## Bitcoin
![Bitcoin Genesis Block Raw hex](/images/bitcoin_genesis_block.jpg)
      
### Introduction
First proposed in an [email](https://satoshi.nakamotoinstitute.org/emails/cryptography/1/) to the cryptography mailing list, Bitcoin was 'born' on January 3 2009, when the first block was mined by Satoshi Nakamoto.  In the email he describes Bitcoin as 'a cash system that's fully peer-to-peer, with no trusted third party', describing a form of cash that like the internet was essentially free of control by a central authority.  

The internet community had come to see the existence of a cash system free from central control as being imposible due to the problem that data could be transfered to another party without destroying the original copy, thus the need for a central authority to keep track of who owns what. Nakamoto came up with an original solution for this problem by attaching the confirmation of transactions on the blockchain to real life value - in this case cpu power.

There are essentially two innovations that Nakamoto introduced to allow for the ablility to keep track of 'money' in the absence of a trusted third party, namely
1. The database holding all of the transactions should be available to all and not on a centralised database
2. The computing power of the network needs to be able to verify the ownership and exchange of funds 

The foundational element for this introduced by Nakamoto is the blockchain - which by itself is not exciting, but in connection with the functioning of the bitcoin network is VERY innovative.  The blockchain itself is in essence a [linked list](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Linked%20Lists/linked%20lists.html) of 'blocks' of transactions. The block chain is stored by all [full nodes](https://en.bitcoin.it/wiki/Full_node) - who help verify the validity of the blocks of transaction - on the bitcoin network.  The blocks themselves are created by a special type of full node, called a miner.  

### Bitcoin Mining 
Bitcoin miners 'mine' for bitcoin by solving a predictable mathematical problem.  The problem in question has the interesting characteristic that it is difficult to calculate yet easy to solve, making the verification of the problem by everyday computing hardware feasible.  Everytime a miner is solves this problem, it is allowed to add it's block to the end of the blockchain, thus allowing the network to validate the block using a set of rules described in the [bitcoin white paper](https://nakamotoinstitute.org/bitcoin/).  The first miner whose solution is verified by the network is rewarded with a number of bitcoins that is predetermined by the same white paper.


