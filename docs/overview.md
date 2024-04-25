# Ethereum Core Protocol Overview

Notes: The material related to Ethereum Protocol is largely based on my notes when attending the Ethereum Foundation's Ethereum Protocol Fellowship Study Group. 
Highly recommended to explore the [EPS Git Repo](https://github.com/eth-protocol-fellows/protocol-studies) and [EPS Wiki](https://epf.wiki/#/) to hear the talks from the core devlopers and get more first-hand knowledge. For example, in Week 6, Dankrad himself gave a talk about Danksharding which is really cool.

## Prehistory and Philosophy

Ethereum is deeply inspired by the following:
* UNIX Operating System: UNIX is an operating system and philosophy that has a big impact on morden computer science. The concept of modularity is important to Ethereum design.
* The Free Software movement: Open, independent, and collaborative development culture. The protocol is implemented on top of open and free software which gives the virtue of neutrality, verifiability, security, openness, permissionless, and trustless nature of Ethereum. The protocol wouldn't succeed on closed and commercial proprietary software.
* The advance of cryptography: [the asymmetric cryptography] (https://www-ee.stanford.edu/~hellman/publications/24.pdf) or Public-key cryptography eanbles digital signatures. New cryptography technologies such as Zero-knowledge proof are also inspiring innovations on Ethereum.
* Bitcoin: The first decentralized cryptocurrency has no doubt opened a new window and demonstrated the potential of blockchain technology. 

More early history and technicol details can be found in [Vitalik's Blog](https://vitalik.eth.limo/general/2017/09/14/prehistory.html)

## Ethereum Protocol Design
In 2014, 5 years after Satoshi Nakamoto's development of Bitcoin, [Vitalik Buterin](https://en.wikipedia.org/wiki/Vitalik_Buterin) published the [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/#ethereum-whitepaper). Ethereum intends to provide a blockchain with not a merely P2P cash tranaxction functionality but also a built-in fully-fledged Turing-complete programming language that can be used to create "smart contracts" that can be used to encode arbitrary state transition functions, allowing users to create any of the systems, simply by writing up the logic in a few lines of code. Regarding the application in finance, Bitcoin functions as a digital cash, while Ethereum functions as a smart contract platform where a financial system can be built on. We have already witnessed the born of decentralized exchanges, lending protocols, stablecoins, and many others based on Ethereum. 
* Yellowpaper
* Execution specs
* Consensus specs

# Protocol Implementations and Development
* execution layer (EL)
* consensus layer (CL) 

# Ethereum Ecosystem
* Layer 2
* Applications


# Reference
* https://epf.wiki/#/eps/week1?id=prehistory-and-philosophy
* https://bitcoin.org/bitcoin.pdf
* https://ethereum.org/whitepaper#ethereum-whitepaper
* https://ethereum.github.io/yellowpaper/paper.pdf
