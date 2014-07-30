Decentral : A Decentralized Offchain Banking System
======================================================
   Authors: Uwe Cerron, Leo Shao
uwecerron@gmail.com,lshao30@gmail.com

### Abstract
In the absence of trust opportunities can be lost. A typical solution involves trusting a third party to mediate a transaction across parties for a fee becoming the single point of failure throughout the whole process [1].  A purely offchain peer to peer network may allow for cryptocurrency transactions to be traded trust free from one user to another without having transactions be registered in the blockchain. Multiple signature technology  may allow for the network to perform the roles of a decentralized arbiter and notary, combined with the ability to issue tokens representative of such funds it may provide a trust free mechanism for trade and investment. 

The decentralized offchain network allows for the identification and distribution of cryptocoins and metacoins definitions within the network and will only track the last state of ownership of the coins, through this only the last transaction to withdraw coins from the network will be recorded in the blockchain. Through multisignature technology the network can act as an autonomous escrow agent of multiple cryptocurrencies. Nodes within the network may choose any cryptocurrency integrated within the network as a payment fee for their escrow service. Due to the representation of cryptocoins as tokens for access to services through decentralized applications we believe the decentral tokens or “credits” may prove to be a generic token collecting the escrow node’s cryptocurrency of choice for payment. Without the need for access to the blockchain, Decentral offers the opportunity of offchain transactions, smart contracts and tokens can be traded with the properties of  anonymity, fungibility, the ability to store and accumulate value of a single or a bundle of tokens which with the advent of decentralized applications may represent access to public goods.

I.History
-----------

Bitcoin, the first decentralized cryptocurrency network has been a major accomplishment of concepts that originated since the 80s. Bitcoin introduced the concept of a proof of work blockchain, which provides a decentralized consensus protocol to organize transactions and uses proof of work as a mechanism to confirm them, but Bitcoin does not come without challenges. Since its inception Bitcoin has been plagued with scams and badly managed services, currently there is no way to prevent these scams. These are problems that need to be solved if blockchain based cryptocurrencies are to gain mainstream adoption.

As of today there are no decentralized systems in place that can allow for offchain trust free exchange of services without single points of failure, users of the service cannot obtain the guarantee that the service provider may not run with the user’s money, m of n multi-signature transactions solves this problem by requiring at least m key signatures out of n private keys to be needed in order to spend the funds. It is clear that the Bitcoin ecosystem is trending towards a trust free transactions ecosystem, a trust free entity is needed to escrow funds impartially without the risk of collusion. 

So far, there are no trust free mechanisms for which to ensure a return on bitcoin deposits without the risk a centralized services has. Decentral aims to be more than an escrow network, we strongly believe that by decentralizing a financial system main functions which include the redistribution of wealth by pooling and investing with the funds or tokens representing the funds would help Bitcoin achieve mainstream adoption. The system would be implemented as a decentralized offchain transaction system to address blockchain based cryptocurrencies need for speed, micro payments through no or low transaction fees and offer a possible investment framework through bitcoin backed tokens.

Currently, multi signature services include digitally signing contracts and transactions usually as a third party, providing an extra layer of security for transactions, others plan to use it as mediators in the event of a dispute between the buyer and the seller. The arbitration aspect of their role would be to decide the fair outcome of a dispute[4]. However, the system still depends on a centralized entity or service to work as a third party. In this paper we present a network of nodes ready to perform trust free transactions.


II.Architecture
----------------

The Decentral network will integrate multiple cryptocurrencies. As a result, each node will have an option to charge its escrow fee in the desired cryptocurrency of choice. For now, the Decentral Network will aim to integrate with Bitcoin. Each Decentral node will store a colored coin definitions table which will be located in the bitcoin blockchain, this way each node becomes a decentralized asset definition for the colored coins protocol. Ideally we plan on implementing an infinite divisible protocol where the 1 satoshi per token atomicity is no longer in place, but for now the Decentral Network will adopt the EPOBC color kernel.

Using the Bitcoin’s blockchain scripting capabilities, the Decentral network can create a special transaction and post it on the Bitcoin network with special instructions that may require 7 out of 10 decentral network nodes to spend this transaction, with each Decentral Node storing a private key you would need more than 3 nodes being offline or hacked before being unable to move the funds. For security purposes, an emergency withdrawal address must be implemented in order for the depositors to recoup their funds, by using the nlocktime feature of the Bitcoin protocol which allows for any transaction to be accepted after x amount of time, the funds will be transmitted to the withdrawal address automatically by the blockchain should more than n nodes become compromised or go offline. 
For metacoins on top of the Bitcoin blockchain we have chosen to focus on colored coins technology for now. Colored Coins technology provides a way to tokenize bitcoins by coloring transaction outputs, the decentral network will store color definitions located in the blockchain. Colored coins does not possess the economic barrier to entry of requiring the purchase of a generic metacoin to buy the issued underlying asset unlike other metacoin protocols issued on top of bitcoin, this makes it an attractive protocol to issue new metacoins or tokens on top of the Bitcoin platform.


III.Proof of Trust
------------------

Nodes cannot be trusted to self report the amount of funds they posses. The network must be able to audit and prove that the node is solvent. Using a variant of Gmaxwell’s proof of solvency proposition the network must be able to prove every node is solvent [2]. The requirements for proof of trust are not computationally expensive, but they must be dependent on the amount of trust a node can provide. A node’s trust must be composed on it’s availability, solvency and security. Trusted nodes will be rewarded with fees from incoming and outgoing transactions.

Proposal for guarantee 
In order for a Decentral node to provide a guarantee that it won’t run away with a depositor’s money they must deposit their own funds which will be held in escrow by the pool, this way should the node lose the funds for any reason the depositor gets reimbursed. The Decentral network requires a proof of funds for each and every node, should a node have less bitcoins than they are supposed to, they will automatically lose their deposit. The amount of  money that must go in and out a server must not exceed the deposit at any point in time. 


IV.Incentives
--------------

Since the network will be comprised of specialized servers, we need to create an incentive for users to participate on the network. As more nodes connect to the network the difficulty of earning fees per server vary depending on the quantity of transactions. Our aim is to establish a free market ecosystem where the node’s fees are determined by the market, thus we expect the present value of credits, which represent the node’s stream of payments, be determined following the time value of money principle.

I.Tokens as Credits

Each node is capable of charging a fee on incoming and outgoing transactions, the credits represent access to all streams of payments from a decentral node.  Inherently its value will depend on the amount of payments a node receives. Credits may be traded for the cryptocurrency of choice in order to expand the node’s earning capabilities.

II. Tokens as checks

The token may be traded offchain. Providing cheaper and faster transactions when compared to standard bitcoin.The token will allow offline usage in a similar manner to a check. The user could have a local checkbook on his phone. When said user wants to buy something locally he could just send message with the appropriate information. Whether or not the money exists will be up to the merchant to verify no different than when paying at any store, the merchant must make sure that he gets the money.

III. Other uses

A  user choosing to create a gambling application could issue a smart contract that was open and properly scrutinized. Anyone could then choose to invest into the application and make the contract only retrievable at the end of the year. This contract could then be tokenized and sold in pieces at any time. The application could be hosted on decentralized networks like maidsafe.


V.Conclusion 
-------------

We have proposed a system where electronic transactions can happen offline. Throughout the paper we described and presented the potential an offline escrow entity can have  on cryptocurrencies. The universal token presented in this paper have all the properties of chaumian cash and added the property for accumulation of wealth throughout time.


References
----------
[1]Justus Ranvier , Lex-Cryptographia,http://bitcoinism.blogspot.com.es/2013/12/lex-cryptographia.html, 2013 
[2]Olivier Lalonde, Proof of Solvency, https://github.com/olalonde/proof-of-solvency, 2014
[3] Digital Cash, http://www.cs.bham.ac.uk/~mdr/teaching/modules06/netsec/lectures/DigitalCash.html
[4]Dr. Washington Sanchez, Separation of Notary and Arbitration Services on OpenBazzaar,https://gist.github.com/drwasho/f1e0a9f5826f5cc4186e, 2014
[5]Mike Hearn,Micropayment Channels, https://bitcoinj.github.io/working-with-micropayments
