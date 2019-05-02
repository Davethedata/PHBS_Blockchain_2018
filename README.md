# How to use blockchain to protect data safety more efficiently?———Discussion in aspect of how to solve blockchain trilemma
## Background

In big data era, privacy data safety gradually draws public attention. We’re handing over more and more personal data to companies that store this information in **centralized** databases, which serve as a magnet for hackers looking to hijack our identities and steal our money.

Recently, lots of data breach brings giant loss to the society. Globally, the **average** cost of a data breach is **$3.62 million**.

Let’s review the biggest one------**the Facebook data breach**.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/FacebookDataBreach.jpg" width=512 height=256 />
</div>
  
**March 18th, 2018:** 50 million Facebook profiles were harvested for Cambridge Analytica in a major data scandal. This number was revised to 87 million Facebook profiles later. Moveover, the data sold to Cambridge Analytica was then used to develop “psychographic” profiles of people and deliver pro-Trump material to them online.

**March 20th,2018:** The Federal Trade Commission (FTC) opened an investigation into whether Facebook had violated a settlement reached with the U.S. government agency in 2011 over user privacy protections.

**March 21st,2018:** Zuckerberg eventually responded to the continued fallout over the data scandal. He said: “We have a responsibility to protect your data, and if we can’t then we don’t deserve to serve you. I’ve been working to understand exactly what happened and how to make sure this doesn’t happen again.”

After the data breach, Facebook’s market value declined about **50 billion** and Facebook might face **2 trillion** fine.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/Facebook%20Scandal.jpg" width=512 height=1024 />
</div>

## Why blockchain?

In big data era, more and more data are used to business analysis to make more money. Since public data are available but worthless, a person’s private data is precious to firms. A lot of firms pay a lot to those that have private money. Our private data are revealed unconsciously. Therefore, data safety is of vital importance for all of us.

The reason why our data are revealed is we **“trust”** those institutions and give them our private data. However, they **“betray”** us for money. If we can have a **“trustless”** system, we won’t worry about the reveal of our privacy data. Nowadays, we call this **“trustless”** system------**BLOCKCHAIN**.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/Blockchain.jpg" width=512 height=256 />
</div>

### Two main features of blockchain related to data safety

#### 1.Decentralization

Decentralization describes the design of a database that isn’t managed by a central party. Instead, **peer-to-peer** interaction drives the system, as no third party is needed.

The decentralized nature of blockchain, with all data replicated on every computer node within the database, means that any hacker trying to attack a single node — the “trusted” centralised institution’s database — is thwarted by the continual processing and recording of data on the other nodes.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/Centralized.png" width=512 height=256 />
</div>

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/Decentralized.png" width=512 height=256 />
</div>

#### 2.Security———Immutability

Immutability guarantees that data cannot be altered once added to the blockchain. Immutability on the blockchain is powered by “proof of work” cryptographic processes that require huge amounts of computing power to add new information to the system, as well as an almost inconceivably high amount needed to “game” the system. For a hacker, if he wants to hijack our data, he only has to attack several computers in the centralized institution in the traditional situation. However, he has to attack 51% computers in the system using blockchain.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/CentralizedAttack.PNG" width=512 height=256 />
</div> 

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/DecentralizedAttack.PNG" width=512 height=256 />
</div>

## Why does blockchain not become popular?

#### 1. Blockchain has an environmental cost

Blockchain relies on immutability to maintain its security and establish consensus over a distributed system. In order to give a user permission to add data, complex algorithms must be run, which require quantities of computing power. Taking the blockchain of Bitcoin as an example, the computing power required to keep the network running consumes as much energy as was used by **159** of the world’s nations. Over **170 billion** dollars are required to guarantee its current market capacity and security. Therefore, this huge environmental cost lower the blockchain development.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/Nations.PNG" width=1024 height=512 />
</div>

#### 2.Lack of regulation creates a risky environment

Due to the lack of regulatory oversight, scams and market manipulation are common situation.
There is always a chance that your blockchain might be attacked and if there is no related regulation to protect your right, you may have huge loss.Again, this is a consequence of the lack of regulatory oversight across the blockchain.

#### 3.Storage

The blockchain protocols are designed in such a way that each node should maintain the same copy of the blockchain and the blockchain should contain every transaction from the beginning of time. This means that any new device, in order to become a node in the blockchain, should download all the transactions right from the first block. 

Bitcoin’s blockchain size is more than 100GB and Ethereum’s blockchain size is approximately 50GB. These are just financial transactions and these systems limit the number of transactions per second. Due to the replicated storage mechanism, every device should hold a copy of blockchain in order to be a part of the network and a simple device might not provide the demanded storage capacity.

#### 4.Hard to understand

To be honest,for most people now,it is impossible to understand blockchain.

## Scalability

We have talked about the advantages and disadvantage of blockchain. Besides, the biggest and most important problem for blockchain is based on it pros and cons. We call it **scalability**.

**Let's explain what scalability is:**

If we briefly review the pros and cons of blockchain:

**A blockchain is essentially a linked-list of blocks containing data, with some constraints around it:**

  —Blocks can't be modified once created  
  —A person want to change data may need download all blockchain which have big data size  
  —There are specific rules (for consensus) for putting data inside a blockchain and a long time to reach consensus  

**These constraints, when implemented in a form of a protocol, yield a data-recording mechanism with some highly desirable characteristics:**

  —No single point of control or failure  
  —Immutability of data  
  —Decentralized and trustless system  

Due to these advantages, blockchain systems are suited for the scenarios where mutually mistrusting parties have to exchange value digitally. However, these advantages don't come for free. If we look at it from a different angle, a blockchain is a slow, immutable database with very high redundancy, which means it is expensive to maintain and also hard to scale. 

Scalability will influence the speed of data input and access. In addition, it will lower the whole society’s efficiency.

### Take credit card transaction as an example:

For bitcoin and ethereum to compete with more popular systems like visa and paypal, they need to seriously step up their game when it comes to transaction times. While paypal manages 193 transactions per second and visa manages 1667 transactions per second, Ethereum does only 20 transactions per second while bitcoin manages a whopping 7 transactions per second!.
The only way that these numbers can be improved is if they work on their scalability.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/Speed.PNG" width=512 height=256 />
</div>

## Blockchain trilemma———Decentralization, Security, Scalability

A trilemma is a difficult choice from three options, each of which is (or appears) unacceptable or unfavourable. Many observe that blockchains have their own trilemma – one that is preventing mass adoption.

The **ideal blockchain** would have all three of the characteristics：

  —Decentralization to build a trustless system  
  —Scalability to increase speed and efficiency  
  —Scalability to increase speed and efficiency  

Unfortunately, **we can’t have them all**

Blockchain Trilemma is a term put up by Ethereum founder Vitalik Buterin that addresses the problem of how to develop a blockchain technology that offers scalability, decentralization and security, without compromising either one.Vitalik believes that at a fundamental level, Blockchains can only **achieve 2 out of 3** of these traits at one time.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/BlockchainTrilemma.jpg" width=512 height=256 />
</div>

### How do we annlyze blockchain trilemma logically?

A briefly process of prove is shown as follows.For complete proof,please check:[Proof of blockchain trilemma](https://news.8btc.com/why-it-is-impossible-to-solve-blockchain-trilemma)

Firstly, we need to know two basic theories about distributed systems———FLP theory and CAP theory.

FLP theory proves that in a completely asynchronous distributed system, no completely asynchronous consensus protocol can tolerate even a single unannounced process death. 

For the complete proof, please check:[Proof of FLP theory](https://www.the-paper-trail.org/post/2008-08-13-a-brief-tour-of-flp-impossibility/)

CAP theory proves it is impossible to get all three merits in a distributed system: **consistency, availability, and partition tolerance** at the same time.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/CAP.png" width=512 height=256 />
</div>

For the complete proof, please check:[Proof of CAP theoty](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)

We can prove that for three properties in blockchain trilemma------security, decentralization, scalability------are related to the properties in CAP theory, which is consistency, availability, and partition tolerance. Specifically, we can prove:

—Security needs Consistency
—Scalability needs Availability 
—Decentralization needs Partition-tolerant


Then we combine these two trilemma together:

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/FLP-CAP.png" width=512 height=256 />
</div>

We prove that the blockchain trilemma exists theoritically 

## How to solve blockchain trilemma?———This leads to the future of blockchain

Recently, a lot of solution have been created.We divide these solutions into two aspects———algorithm and structural change

### From the aspect of algorithm 

Traditional blockchain like bitcoin use PoW.However,creating a block and reaching consensus is time-consuming under PoW.Therefore, alternatives of PoW are created.

#### Proof-of-Stake

In proof of stake, your chance of being picked to create the next block depends on the number of coins in the system you have.Once a block is created, that block still needs to be committed to the blockchain. In some systems, every node in the system has to sign until **a majority vote is reached**, while in other systems, a **random** group of signers is chosen. In a word, the consensus process **save more time** compared to Proof-of-Work. 

However, we still run into a problem———‘nothing-at-stake‘ problem. A participant with nothing to lose has no reason not to behave badly.

#### Proof-of-Activity

In proof of activity, mining is in an ordinary Proof-of-Work way, with miners trying to solve a difficult puzzle. Depending on the implementation, blocks mined do not contain any transactions, so the winning block will only contain a header and the miner’s reward address.**At this point**, the system switches to Proof-of-Stake. Based on information in the header, a **random** group of signer is chosen to sign the new block. The more coins in the system a miner owns, the more likely he or she is to be chosen.

Criticisms of proof of activity are the same as for both proof of work (too much energy is required to mine blocks) and proof of stake (there is nothing to deter a validator from double signing).

#### Proof-of-Burn

With Proof-of-Burn, instead of pouring money into expensive computer equipment, you ‘burn’ coins by sending them to an address where they are irretrievable. In other words, you earn a lifetime privilege to mine on the system based on a random selection process.

Depending on how Proof-of-Burn is implemented, miners may burn the native currency or the currency of an alternative chain, like bitcoin. The more coins you burn, the better chance you have of being selected to mine the next block.Eventually,you will want to burn more coins to increase your odds of being selected in the lottery. 

While proof of burn is an interesting alternative to Proof-of-Work, the protocol still wastes resources needlessly. Another criticism is that mining power simply goes to those who are willing to burn more money.

#### Proof-of-Capacity

In Proof-of-Capacity,you ‘pay’ with storage space.The more storage space you have, the better your chance of mining the next block and earning the block reward.Prior to mining in a Proof-of-Capacity system, the algorithm generates large data sets known as ‘plots’, which you store on your hard drive. The more plots you have, the better your chance of finding the next block in the chain.

But with Proof-of-Capacity, we still have the problem of nothing at stake to deter bad actors.

Variations of Proof-of-Capacity include **Proof-of-Storage** and **Proof-of-Space**.

####  Proof-of-Elapsed-time 

Chipmaker Intel has come up with its own alternative consensus protocol called Proof-of-Elapsed-time. This system works similarly to proof of work, but consumes far less electricity.

### From the aspect of structural change

#### First-Layer Solutions（on-Chain）

First-layer solution needs changes to be made on the codebase of the actual blockchain(also called on-Chain). This suggests improving the core features of the blockchain. 

Some examples of first layer solutions include increasing the block size limit from 1MB to 10 MB or reducing the block creation time from 10 minutes to 5 minutes. It is important to note that any structural or fundamental change to the property of a blockchain needs a hard fork. This requires the entire community to transit into a new and improved chain.

—Here are 3 on-Chain solution examples:

[Segregated Witness (Segwit)](https://en.wikipedia.org/wiki/SegWit)  
[Sharding](https://github.com/ethereum/wiki/wiki/Sharding-FAQ)  
[Hard Fork](https://en.wikipedia.org/wiki/Fork_(blockchain)) 

#### Second-Layer Solutions (Off-Chain)

Second-layer scalability solutions refer to secondary protocols built on top of the main blockchain where transactions are ‘off-loaded’ from the main blockchain to save space and reduce network congestion. Second-layer solutions are usually in the form off side-chains and state-channels.

Ultimately, the thinking is that not every small transaction necessarily has to take place on the chain, rather the chain can be regularly updated to reflect balances. Taking transactions away from the main blockchain alleviates the stress on it.

—Here are 2 off-Chain solution examples:

[Plasma](http://www.plasma.io/)  
[Lightning Network](https://en.wikipedia.org/wiki/Lightning_Network)  

#### Scalable Distributed Ledgers

Blockchain technology is a subset under the general Distributed Ledger Technology (DLT) due to its distributed architecture. There are other forms of distributed ledgers that do not use the same data structure of organizing information (transactions) into chained, sequential blocks. The most popular form of distributed ledgers is a technology called the [Directed Acyclic Graphs](https://en.wikipedia.org/wiki/Directed_acyclic_graph).The solutions use DAG include IOTA,NANO,Byteball.

## Conclusion

In big data era, data safety problem is gradually becoming a threatening problem of social safety.Frequent data breaches bring huge loss and social fluctuation.Blockchain can mitigate the data safety problem depending on its decentralization and immutablity.However, scalability becomes the most tough barrier to overcome for blockchain and there exists a trilemma among increasing scalability, staying decentralized and having immutabilty.The solution of this trilemma is the future of blockchain.

We put up several solutions which are divided into two aspects.However, we think the structural change solutions may overwhelm algorithm solutions for reasons:


—Algorithm solutions mostly base on digital currency, it may not apply to data storage better than changing blockchain's structure  
—Algorithm solutions has omitted process to save time and this may lead to more problem than structural change  
—Stuctural change solutions have more possbility to develop in the future.Coversely, Algorithm solutions can only work on the way of mining and reaching consensus  

