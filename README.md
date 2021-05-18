<p align="center">
<img src="https://www.hicetnunc.xyz/og-image.jpg" alt="alt text" width="400">
</p>


# Hicetnunc API Guide
> A guide for using various Tezos APIs to build web experiences and tools for hicetnunc.xyz.

#### Table of Contents  
- [Introduction](#hicetnunc-api-guide)  
- [General Information](#general-information)  
- [Tezos APIs](#tezos-api)  
- [Code Examples](#code-examples)  
- [Contact](#contact)  

#### Roadmap

1)  ~~Release initial Better Call Dev Nodejs examples and Github Readme~~
2)  Add simple html web demo that populates a table with message respose data
3)  Implement rate-limiting to outgoing messages using Bottleneck library
4)  Add TZKT.IO API and compare against Better Call Dev for performance

#### Hic et nunc Resources
- [Hic et nunc Tools](hicetnunc.tools/)
- [Hic et nunc Discord](https://discord.gg/g7VQt5pJ)
- [Hic et nunc Github](https://github.com/hicetnunc2000/)

#### Tezos Resources
- [Tezos Block Explorer](http://tzkt.io/)
- [Better Call Dev API](https://better-call.dev/)
- [TZKT API Docs](https://api.tzkt.io/)

# General Information

<p align="center">
<img src="https://user-images.githubusercontent.com/1003196/118697952-db4f6100-b7dd-11eb-8dd1-d8494295d749.png" alt="alt text" width="700">
</p>

#### What is Hic Et Nunc?

[Hic et nunc](hicetnunc.xyz/) is a decentralized NFT marketplace built on the Tezos blockchain. It allows users to create, sell and interact with Tezos NFT's called OBJKTS that can hold a single artwork, 3d model, image, video, etc. When a user uploads their content to hic et nunc, the actual asset file is uploaded to [IPFS](https://ipfs.io/), a decentralized storage network. The user inputted metadata is uploaded and stored in the Tezos blockchain. 

#### Decentralized System

A decentralized system is one where one entity does not have full control over the decision making, additions and maitenance of the system. A decentralized system is inherently communal, serving groups of interconnected relevant parties that want to transact with trust. In many cases decentralization is impossible to reach, a best attempt at a utopian life. 

#### Blockchain 

A blockchain is a database that is built specifically to run on decentralized p2p networks and requires a set of 'checks and balances' to read, write and interact with. There are many different types of blockchains, some of them store financial data like Bitcoin. Others like Ethereum, Tezos and IPFS store files, application data, etc. 

Depending on the implementation, a blockchain can be both decentralized or centralized. Decentralization lends itself to certain ideas and for now the most common implementation of a decentralized blockchain is a cryptocurrency.

#### Cryptocurrency 

A cryptocurrency is a digital medium to transact value on network not owned by a single entity or nation-state. If you are curious as to why that might be needed, you might be in the wrong place. Please refer to the [Bitcoin White Paper](https://bitcoin.org/bitcoin.pdf) and Dr. Daniel Kim's [video](https://www.youtube.com/watch?v=aC9Uu5BUxII) on monetary policy, inflation, central banking, Bitcoin and Monero.

#### NFT

An NFT stands for 'non-fungible-token' and was originally created as one of many smart contract types to use on the Ethereum network. Unlike a currency, an NFT is a receipt that uses a private key to verify your assocation to certain files, items and events that happen on the blockchain. It is your digital backpack that lets you store and collect moments and digital blockchain goods. 

#### Hicetnunc

Hicetnunc is a open source movement that created the Tezos NFT specification called an 'OBJKT.' Unlike other NFT platformns, hicetnunc uses Tezos, which is a proof-of-stake blockchain with significantly less fees and environmental impact caused by mining. Hicetnunc.xyz allows you to create, collect and interact with the Tezos blockchain.

# Tezos API

In order to get metadata on a Tezos Wallet Address or hic et nunc OBJKT ID you must interact with a Tezos blockchain explorer API. This guide focuses on the two most popular Tezos Blockchain Explorer APIS:

- [Better Call Dev API](https://better-call.dev/)
- [Tezos Block Explorer](http://tzkt.io/)

# Code Examples
View more in depth documentation inside of each example's folder:
 
- [Better Call Dev Node.js Examples](/node)  
- [Website Example](/web)  
- ~~[TZKT Node.js Examples]~~ (coming soon)

# Contact
Created by [@ianpetrarca](https://www.twitter.com/ianpetrarca) - tz1LobSdhfUqYpMojXWHQLJPhFLEzUEd9JAn
