# How to use blockchain to protect data safety more efficiently?————Discussion in aspect of how to solve blockchain trilemma
## Background

In big data era, privacy data safety gradually draws public attention. We’re handing over more and more personal data to companies that store this information in **centralized** databases, which serve as a magnet for hackers looking to hijack our identities and steal our money.

Recently, lots of data breach brings giant loss to the society. Globally, the **average** cost of a data breach is **$3.62 million**.

Let’s review the biggest one------**the Facebook data breach**.

 <div align="center">
<img src="https://github.com/Davethedata/PHBS_Blockchain_2018/blob/master/FacebookDataBreach.jpg" width="50%" height="50%" />
</div>
  
**March 18th, 2018:** 50 million Facebook profiles were harvested for Cambridge Analytica in a major data scandal. This number was revised to 87 million Facebook profiles later. Moveover, the data sold to Cambridge Analytica was then used to develop “psychographic” profiles of people and deliver pro-Trump material to them online.

**March 20th,2018:** The Federal Trade Commission (FTC) opened an investigation into whether Facebook had violated a settlement reached with the U.S. government agency in 2011 over user privacy protections.

**March 21st,2018:** Zuckerberg eventually responded to the continued fallout over the data scandal. He said: “We have a responsibility to protect your data, and if we can’t then we don’t deserve to serve you. I’ve been working to understand exactly what happened and how to make sure this doesn’t happen again.”

After the data breach, Facebook’s market value declined about **50 billion** and Facebook might face **2 trillion** fine.

## Why blockchain?

In big data era, more and more data are used to business analysis to make more money. Since public data are available but worthless, a person’s private data is precious to firms. A lot of firms pay a lot to those that have private money. Our private data are revealed unconsciously. Therefore, data safety is of vital importance for all of us.

The reason why our data are revealed is we **“trust”** those institutions and give them our private data. However, they **“betray”** us for money. If we can have a **“trustless”** system, we won’t worry about the reveal of our privacy data. Nowadays, we call this **“trustless”** system------**BLOCKCHAIN**.

(图片）

### Two main features of blockchain related to data safety

#### 1.Decentralization

Decentralization describes the design of a database that isn’t managed by a central party. Instead, **peer-to-peer** interaction drives the system, as no third party is needed.

The decentralized nature of blockchain, with all data replicated on every computer node within the database, means that any hacker trying to attack a single node — the “trusted” centralised institution’s database — is thwarted by the continual processing and recording of data on the other nodes.

（图片）

#### 2.Security————Immutability

Immutability guarantees that data cannot be altered once added to the blockchain. Immutability on the blockchain is powered by “proof of work” cryptographic processes that require huge amounts of computing power to add new information to the system, as well as an almost inconceivably high amount needed to “game” the system. For a hacker, if he wants to hijack our data, he only has to attack several computers in the centralized institution in the traditional situation. However, he has to attack 51% computers in the system using blockchain.

（图片）

## Why does blockchain not become popular?

#### 1. Blockchain has an environmental cost

Blockchain relies on immutability to maintain its security and establish consensus over a distributed system. In order to give a user permission to add data, complex algorithms must be run, which require quantities of computing power. Taking the blockchain of Bitcoin as an example, the computing power required to keep the network running consumes as much energy as was used by 159 of the world’s nations. Over 170 billion dollars are required to guarantee its current market capacity and security. Therefore, this huge environmental cost lower the blockchain development.

（图片）

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

(图片）

## Blockchain trilemma————Decentralization, Security, Scalability

A trilemma is a difficult choice from three options, each of which is (or appears) unacceptable or unfavourable. Many observe that blockchains have their own trilemma – one that is preventing mass adoption.

The **ideal blockchain** would have all three of the characteristics：

  —Decentralization to build a trustless system  
  —Scalability to increase speed and efficiency  
  —Scalability to increase speed and efficiency  

Unfortunately, **we can’t have them all**

Blockchain Trilemma is a term put up by Ethereum founder Vitalik Buterin that addresses the problem of how to develop a blockchain technology that offers scalability, decentralization and security, without compromising either one.Vitalik believes that at a fundamental level, Blockchains can only **achieve 2 out of 3** of these traits at one time.
