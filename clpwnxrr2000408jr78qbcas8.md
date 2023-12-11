---
title: "Basics of Blockchain"
seoTitle: "Basics of Blockchain"
seoDescription: "Blockchain is a decentralized, immutable ledger technology that securely records transactions across a network of computers, ensuring transparency."
datePublished: Fri Dec 08 2023 13:28:48 GMT+0000 (Coordinated Universal Time)
cuid: clpwnxrr2000408jr78qbcas8
slug: basics-of-blockchain
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1702040842516/c817f13e-61d1-4770-b37e-0c619c2046f6.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1702040867806/876c53f8-ba63-45c2-b672-ab4823488166.jpeg
tags: blockchain, web3, wemakedevs, wemakedevs-hashnode, basics-of-blockchain-technology

---

If we ever try to learn or understand the blockchain we read some buzzwords like Distributed Ledger, Immutable ledger, decentralized ledger, bitcoin, transactions, cryptocurrency and many more. So, today we will set the foundation of all Blockchain concepts that every blockchain enthusiast should know. Considering all the hype and exciting buzzwords around Bitcoin and Blockchain in general, it becomes important to understand the characteristics of blockchain against our current technologies, before considering blockchain adoption as a solution.

Before we move on to understanding the current structure followed for transactions over various organizations, let's first look at various types of current database systems. A database is nothing but a structured set of information that can be accessed, updated and modified efficiently and simply.

### **We classify databases into three types**:

* Centralized
    
* Decentralized
    
* Distributed
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702012080468/b8bd50d8-f203-4d33-9251-d1dc25aa8201.webp align="center")

Let's imagine a different scenario to explain the types of databases - Centralized, Decentralized, and Distributed. This time, we'll explore the world of a book retailer named Ram.

1. **Centralized Database System (Single Warehouse):**
    
    * Suppose Ram is an entrepreneur who starts a book business. He set up various bookstores in the city to sell the books. He created a warehouse to store all the books and supply them as per the requirements of the bookstores. You can map this scenario to the centralized database system. Similar to the single warehouse storing all the books, a central database stores all the data.
        
2. **Decentralized Database System (Multiple Warehouses in Different Cities):**
    
    * As his business expanded, he ventured out to multiple cities by setting up various bookstores. Now, Ram realised that having one warehouse would not suffice his requirements, so he set up warehouses in all the cities. He created one warehouse in each city he ventured into. All his book was stored there and distributed from there to the bookstore in one city. Here this can be mapped to the decentralised database system. Multiple warehouses hold the merchandise, and all the bookstores fetch the book from these warehouses. Similarly, in a decentralised database system, all the information is not stored in one place but in multiple places or databases.
        
3. **Distributed Database System (Warehouse for Each Book Category):**
    
    * Further, as the demand increased, Ram set up one warehouse for each bookstore, considering the cost of transportation and the nature of the market. Now every bookstore has its own warehouse to store and retrieve the books. You can map this scenario to the distributed database systems. In a distributed database system, the data is shared across the entire network.
        

The above example shows that any database can be classified as a centralised, decentralised or distributed database.

A distributed database can be summed up as a stretched version of a decentralised database. The mode of decision-making determines the main difference between the two systems:

* where or how is the **decision** made
    
* how the information is **shared** across the participating nodes
    

In the decentralised database, there is no single point where the overall decision is made. Every node in the system makes its own decision, and the system behaviour is the sum of those responses. Also, a single node may or may not have complete information about the system as a whole depending on the architecture.

Distributed databases are best described as a system where data processing is shared across all the nodes. However, system decisions may still be made centrally using all of the system's information.

Listed below are the critical points of differentiation between the three types of systems we encountered so far.

| Feature | Centralised | Decentralised | Distributed |
| --- | --- | --- | --- |
| **Security** | Low; Most vulnerable to data security issues | Moderate; Data can be rebuilt from parallel | Highest; It isn't easy to lose data completely |
| **Overheads and Costs** | Low; Redundancy is minimized | Substantial processing overheads to ensure | Massive overheads to ensure appropriate coordination among multiple nodes |
| **Response Speed** | Bottlenecks can cause response speed to reduce significantly | Quick response speed depending on the distribution of data | Fastest response rates |
| **Points of Failure / Maintenance** | Single point of failure; Easy to maintain | A limited number of points of failure; Maintenance more complex than centralised systems | Multiple points of failure; Difficult to maintain |
| **Stability** | Highly unstable; if the central server fails, the entire network collapses | Stability is better than  centralised systems; the network can continue to operate at a reduced level | The highest level of stability; single node failure doesn’t affect the network |
| **Scalability** | Low scalability | Moderately scalable | Infinitely scalable |
| **Ease of Setup** | Easy to set up | Difficult to set up | Difficult to set up |

### Existing System

Now let's understand a crucial component of any business: an ‘**intermediary**’.

An **intermediary**, generally, is an individual or an organisation that is involved between two parties in a transaction or a conversation. Traditionally, the significance of intermediaries lies in establishing trust among unknown parties. However, there are a number of disadvantages to using intermediaries, including costs associated with the transaction, inefficiencies in workflow, and security issues.

Let's consider some other real-world examples that you are already familiar with. Imagine there is a salaried employee named Akshay. So, Akshay earns a salary and acts as a surplus creator for the economy. Akshay has been working for a few years and now has saved plenty of money. On the other hand, our entrepreneur Ram who is running the bookstore business wants to expand his business more. To expand his business Ram wants to borrow money. At this point, we have two people who could help each other but are both unknowns. This is where an intermediary body is required. In this case, the intermediary body is the bank. So, the bank brings the trust equation in this scenario. People like Akshay deposit money in the bank and the bank lends that money to businesses or other loan seekers.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702041830728/32f9e84b-3294-464f-b091-6adbbe3d7c3c.png align="center")

Now the question is how these banks keep our data secure and provide services to us. Each and every bank has its own centralised database. The interaction between a consumer and the bank is captured in the bank's system but it is a centralised system that is created, maintained and controlled by the bank where a consumer has the view access and certain transaction rights(Netbanking, Mobile Banking etc) which the bank gives.

Now let's understand what are the disadvantages we experiencing as of now because of this centralised way of storing data which is not really transparent and not really accessible to individual retail customers like us.

### Idea of Satoshi Nakamoto

If you look at scenarios like this because of the way of storing the data in a centralized database and controlled by a centralized authority there are certain systemic disadvantages we experience today in our daily life or what we used to experience. It became very visible starting from the financial crisis in 2008 onwards.

**Disadvantages:**

* **Isolation(Lack of transparency)**: The intermediary will have a separate deal with the other party unknown to the one trusted.
    
* **Complete authority of one party**: If the Intermediary system wants to shift its data to another server, data discrepancy might occur.
    

We have seen several examples in part that banks have charged huge amounts of fines. Most of the cases are unilateral decisions which are made by the banks only because of the authority they have the data stored in their centralized database. We also have seen financial crimes by individuals. businesses or sometimes by the banks themselves.

If you take the example of the 2008 financial crisis, there were some bad decisions were made by the banks which created economic distress(recession, unemployment etc). The entire globe had to suffer because of the bad decisions taken by the few bodies. This actually made **Satoshi Nakamoto** think about an alternative by which we can reduce the weaknesses which are present in our current system.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702041978095/60ca88df-5b14-447d-9aa3-0a47f719c916.png align="center")

After the 2008 financial crisis, Satoshi Nakamoto started thinking and his main **objective** was:

* Remove the human bias from the system
    
* Increase transparency in the system
    
* Trust for everyone(individuals and institutions)
    

The **outcome** of his thought process was:

* Replace humans with machines/computers to remove human bias
    
* Trust by computers ensures that original terms & conditions are met
    
* Bring digital identities for humans/institutions
    

So essentially it means that he wanted to create an ecosystem where everyone(individuals and financial institutions) could come into the ecosystem where their digital identities for everyone(individuals and financial institutions) and machines are there to make the decisions according to the contracts/T&Cs and the entire system with complete transparency and trust between the participants. So, what he did was he took some existing technologies or tools which were already available in the market and combined all these multiple technologies and made an ideal solution which can fix the problems which we face in the current system.

### Pre-existing Technolgies

Now let's look at the existing technologies which Satoshi Nakamoto used to bring the ideal solution which will take away the weaknesses of the current system.

1. **Digital Signature(Digital Identity)**: Digital Signature is very similar to the physical signatures that we use on a physical document. It tells that yes, I vouch for what is written above. This is just a digital representation of the same signature. There are two kinds of signatures in the market
    
    1. Symmetric(Single key):
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701876282629/f2f8f88b-5c36-44c6-a18b-75f168139c15.png align="center")
        
        A symmetric digital signature is a kind of cryptographic signature that is generated and verified using the same secret key. Both the signing and verification procedures need this key.
        
        Let's assume that we have a **sender** and a **receiver** of data. When the receiver is going to receive some data which is coming from the sender, the Receiver wants to make sure that the data is actually sent by the sender. In Symmetric Digital Signature the key is to put the signature on the document(encrypts the document) and send it. When I say encrypts the document it means if someone steals the data in between the communication channel, they wouldn't really understand what this data is, unless they don't get that key. When the data reaches the receiver, the receiver needs to decrypt the data to read that and to decrypt receiver needs the key. In a symmetric digital signature, we only have one key to encrypt and decrypt the data. It means the sender who has originally signed the document has to pass it to the key to the receiver by a secure channel. This is the reason why this symmetric key is not very popular.
        
    2. Asymmetric(Two keys):
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701876311142/51efd42b-c9ab-4946-8183-39406ae99242.png align="center")
        
        In Asymmetric Digital Signatures, a pair of public and private keys is used. A message encrypted with a public key can only be decrypted with the corresponding private key of the public-private key pair and vice versa. The public key of each participant is shared across the network and the private key is held secret only with the individual.
        
        <table><tbody><tr><td colspan="1" rowspan="1"><p><strong>Private Key</strong></p></td><td colspan="1" rowspan="1"><p><strong>Public Key</strong></p></td></tr><tr><td colspan="1" rowspan="1"><p>Key only with the owner</p></td><td colspan="1" rowspan="1"><p>Available to everyone</p></td></tr><tr><td colspan="1" rowspan="1"><p>Sign something as your own vouching</p></td><td colspan="1" rowspan="1"><p>Encrypt data to be accessible to somebody else</p></td></tr></tbody></table>
        
2. **Hashing**: Hashing is the method of transforming any given key or a string of characters into another value. This is usually represented by a shorter, fixed-length value or key that represents and makes it easier to find the original string. To understand the hash function better, go to [**this link**](https://passwordsgenerator.net/sha256-hash-generator/) enter any string of characters in the below box and check the generated hash output. The string you enter can be any random string, e.g.: “I am very curious about hashing.” As you would’ve noticed, the hash function is a mathematical function that can take in **any length of input** and convert it to an **output of a fixed length**.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702030324615/4d28075c-2bc6-4651-85a7-569d996605a8.png align="center")
    
    **Properties of Hashing**
    
    * One way
        
    * Fixed Length Output
        
    * Avalanche effect
        
3. **Merkle Tree**: Merkle tree is a data structure used in computer science and cryptography to efficiently verify the integrity and consistency of data. It's a tree structure constructed using cryptographic hash functions and is commonly used in distributed systems like blockchain.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701889288756/863ae110-92fa-47ff-8b2a-d482faf836cf.png align="center")
    
    Imagine you have a large amount of data that you want to verify efficiently. Instead of checking each piece of data individually, a Merkle tree hashes the data in a hierarchical structure. Here's a simplified explanation of how it works:
    
    1. **Data Division**: The data is divided into fixed-size blocks (often called leaves in the Merkle tree context). Each block of data is hashed individually using a cryptographic hash function like SHA-256.
        
    2. **Pairwise Hashing**: These hashes are then paired and hashed together (concatenating the hashes of two blocks and hashing them). This process continues until there's only one hash remaining. This final hash is called the root hash or the Merkle root.
        
    3. **Construction of the Tree**: The process of hashing pairs of hashes continues upward until a single root hash is obtained. This forms a binary tree structure, where each level above the leaves represents a higher-level hash of the hashes below it.
        
    4. **Verification**: To verify the integrity of the data, you only need the root hash. If someone provides you with a specific piece of data from the original dataset along with the Merkle path (the series of hashes from that data block up to the root), you can efficiently verify its authenticity by reconstructing the Merkle path and hashing the data through the same path. If the final hash matches the root hash, it confirms the integrity of that specific piece of data.
        
        Merkle trees are commonly used in distributed systems (like blockchain) to efficiently prove that a particular transaction or piece of data is included in a block without needing the entire block's data. They enable fast verification and validation of information, particularly in scenarios where only a small part of a large dataset needs to be verified.
        
4. **Hash Cash**: Hash cash is basically proof of work the sender of an email has to do before sending an email. The sender has to calculate the email data hash and ensure that the calculated hash satisfies a particular condition. This limits the scope of spam emails. Please keep this technique in mind. This is because this is now being used in Blockchain Technology for something known as mining of blocks.
    
5. **TCP/IP Protocol**: The communication protocols known as TCP/IP, or Transmission Control Protocol/Internet Protocol, are used to link network devices on the internet. An intranet or extranet is a private computer network that uses TCP/IP as a communications mechanism.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702040154720/5380ee0c-3f77-4532-9c17-8e080813cccb.png align="center")
    
6. **Peer to Peer:** Every machine in a P2P network functions as a node for file sharing. There isn't a single central server in this network since every node serves as a server. This makes it possible to share enormous volumes of data. Each node has an equal share of the tasks. Every linked node in the network has the same burden. Every node in the network must stop functioning independently for the network to fail. This is a result of each node operating separately.
    

So whatever we have discussed so far, Satoshi Nakamoto combined all of this and created an ideal system, which is suitable for the business ecosystem. Blockchain utilizes a distributed system by employing a network of nodes, each maintaining a complete copy of the ledger. Transactions are verified and added to the blockchain through a consensus mechanism, enabling decentralization and eliminating the need for a central authority. Digital signatures(private and public keys) ensure the authenticity and integrity of transactions by uniquely linking them to their respective senders, allowing participants to prove ownership without revealing sensitive information.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702036181435/a73b6137-01da-4866-a1c4-6b65f67d3244.png align="center")

If any transactions happen between any two or more organisations/individuals. This transaction gets proposed to the network and it gets flooded in the network. In the image below assume that the same transaction came to the node N5 from N4 and N3 twice. However, in the ledger, it will be added only once because each node has a **transaction pool**. Whenever a transaction comes in, the node checks that if the transaction is already there or not. If the transaction is not present in the transaction pool only then does the transaction get added to that node.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702036692729/8ca744a8-1a0c-4f85-aad7-0c7fb2bf5544.png align="center")

Once the transaction happens and they have the data in their transaction pool, there are certain nodes in the network which are called miners/validators. These miners/validators are responsible for converting the pool of transactions into a block. Hash pointers connect blocks in a chain, linking each block's hash to the previous one, creating an immutable record of transactions. The peer-to-peer nature of blockchain networks allows nodes to communicate directly, sharing data and validating transactions without intermediaries. The TCP/IP protocol facilitates this communication by defining how data is transmitted across the network, ensuring reliable information exchange. Additionally, Merkle trees enable efficient verification of data integrity by organizing hashes in a hierarchical structure, minimizing the need to traverse the entire blockchain for validation, thus enhancing scalability and security.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1702030011922/fd081260-1a57-4a0b-b74a-20dab79aa5af.gif align="center")

If you compare this scenario with the centralized system which we have discussed above(bank). The bank database was used to maintain everything and it was getting returns only. Where a consumer did not have any control or awareness of what was happening. But in blockchain, every node has its own individual copy(a shared database across all the participants of the network) and it makes it completely transparent and trust without a central authority.

Thus we can see that blockchain technology is an amalgamation of pre-existing technologies and ideas, which was built to address the lacunae of the then-current systems. It does so rather elegantly and in a way that enables each individual user to not only see the system but also contribute meaningfully to it.