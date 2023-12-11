---
title: "Fundamentals of the Hyperledger"
seoTitle: "Fundamentals of Hyperledger"
datePublished: Sat Oct 28 2023 08:59:30 GMT+0000 (Coordinated Universal Time)
cuid: clo9t9ici001908mo564m7pjy
slug: fundamentals-of-the-hyperledger
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/T9rKvI3N0NM/upload/6a671ea6119a4da4c5e2cce5734b4452.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1698483525451/50c2ed7c-a216-4a72-935e-5c332d99d7f3.jpeg
tags: distributed-system, blockchain, hyperledger, distributed-ledger, privateblockchain

---

Hyperledger is an open-source collaborative project hosted by the Linux Foundation. It serves as an umbrella for multiple blockchain and distributed ledger technology (DLT) projects. So, before understanding Hyperledger, you need to have a basic understanding of *Distributed Ledger Technology(DLT)*

### **Distributed Ledger Technology(DLT)**

A system known as ***distributed ledger technology (DLT)*** keeps all of the data in a decentralized manner, rendering it unchangeable by any central authority. Every network member keeps a copy of the ledger, which contains all of the information about the changes that have happened and the data that has been collected. The system is safe since a transaction is reflected in the network via consensus.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1698478456609/e852baf4-1aff-42da-b294-7f189017f0d2.png align="center")

***Distributed Ledger Technology(DLT)*** has some basic building blocks:

* **Data Model**: How you store your data on top of the network. The concept of the data model in DLT forms the building block for the concept known as the ***ledger***.
    
* **Language of Transactions**: You need some logic, which you have to put on your data to make that data change in state from value a to value b. The concept of the language of the transaction in DLT forms the basis of what is known as a ***Smart Contract***.
    
* Consensus Protocol: It allows us to define the one sequence of these transactions as they have to be replicated across all of the peers. This leads to protocols like ***Proof of Work (POW), Proof of Stake (POS)*** or other mining-based protocols you can see on Ethereum, Bitcoin or any other public blockchain.
    

These fundamental blocks are present in the Ethereum and they are also present in Hyperledger Fabric or any other blockchain which is built on ***Distributed Ledger Technology(DLT).*** However, Ethereum is a permissionless open-public blockchain, which means anybody can join or leave the network at any point if they wish to. Also, networks like Ethereum cannot fulfil the requirements of enterprises in terms of scalability, privacy and throughput of transactions.

Now let's understand the key requirements of the enterprise one by one:

1. Speed
    
2. Scalability
    
3. Latency
    
4. Privacy
    
5. Restricted Access
    

**Speed**: In public blockchains like Ethereum the speed of transactions is very slow. Imagine you have to build a social media application like Instagram. And you decide to build your entire application on a **Distributed Network**. If it were built on Ethereum, a single-click button(like or share) on somebody's post, would take around 5 to 10 minutes to go through. That's an unimaginable scenario.

So enterprises like Google, Meta or applications of that level would need speed of transactions to be able to achieve that desirable goal.

**Scalability**: Imagine a transaction processing system like UPI, Rupay or Visa. These networks are spread across thousands and millions of POS(Point of sale) systems at merchant locations across the world and each of these POS systems will need to be connected through a **distributed network** that Visa decided to build on. If this is built on an open network like Ethereum. The scale required for this network to be achieved would not be possible and the network would become highly complicated.

**Latency**: A latency is the amount of time it takes when I initiate a transaction in an application to the transaction actually being committed to the blockchain. This amount of time is very important when you are running with flight tracking system with any airline. When you need your transactions to be immediately recorded on the network. If there is any delay in the amount of time when a transaction is initiated and the transaction is recorded onto the network, it can lead to business losses.

**Privacy**: Imagine if Paytm is built on blockchain. An application like Paytm would obviously want if any user wants to join the application, only can join the application after having gone through a ***Know Your Customer(KYC)*** sort of a process. So that after you join the network, the network knows who you are and this is a requirement by the regulatory bodies that govern the space that applications like Paytm operate.

**Restricted Access**: You would also want Paytm that these transactions that happened on the network and that the balances of each of the users are kept completely private. Private from the users inside of the network and private from anybody outside of the network.

These are the primary requirements that enterprises have that currently are unable to be solved by the public or permissionless blockchain.

### Now let's look at Hyperledger

**Hyperledger** is an **open-source** umbrella project intended to support the development of blockchain-based **distributed ledgers** and to foster the development of cross-industry blockchain technology. Its purpose was to build enterprise-ready blockchain solutions. It was started in **December 2015** by the **Linux Foundation** and is supported by big industry players such as IBM, Intel and SAP.

There are numerous **projects/frameworks under the Hyperledger umbrella** that provide blockchain frameworks for different use cases.  These frameworks were designed to solve specific use cases. Some of these frameworks are as follows:

* **Fabric**: It is designed for developing enterprise-grade, permissioned blockchain networks. Hyperledger Fabric provides a modular and flexible architecture, making it well-suited for a wide range of use cases, especially those requiring privacy, confidentiality, and scalability.
    
* **Sawtooth**: It is a variation in the blockchain environment and is similar to Fabric, but differs with regard to the consensus processes and the architecture around which it is built.
    
* **Indy**: It is specifically designed for building secure, privacy-focused, and self-sovereign identity solutions. Unlike traditional identity systems where organizations control and manage your identity, Hyperledger Indy empowers individuals to have control over their personal information and digital identity.
    
* **Iroha**: Iroha aims to simplify the development of applications that require a **distributed ledger** and to make it accessible to a broader range of developers and organizations.
    
* **Hyperledger Transact**: A development framework for writing blockchain smart contracts that are portable across various platforms.
    

Apart from the frameworks mentioned above, there are a few other frameworks in Hyperledger. Under its umbrella, Hyperledger also hosts tools for specific purposes. Some of the Hyperledger tools are as follows:

* **Composer**: This tool helps to easily build applications over the Hyperledger Fabric network.
    
* **Caliper**: It allows measuring the activities and performance of some of the frameworks hosted on the Hyperledger consortium.
    
* **Explorer**: It allows viewing of the data hosted on the Hyperledger network.
    

**Hyperledger**'s diverse set of projects caters to various use cases and industries, including supply chain management, finance, healthcare, identity management, and more. Each project has its unique features and capabilities, and organizations can choose the most suitable one for their specific blockchain application requirements. For the most up-to-date information on Hyperledger projects, you can refer to the [official Hyperledger website](https://www.hyperledger.org/).