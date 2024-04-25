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
In 2014, 5 years after Satoshi Nakamoto's development of [Bitcoin](https://bitcoin.org/bitcoin.pdf), [Vitalik Buterin](https://en.wikipedia.org/wiki/Vitalik_Buterin) published the [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/#ethereum-whitepaper). Ethereum intends to provide a blockchain with not a merely P2P cash tranaxction functionality but also a built-in fully-fledged Turing-complete programming language that can be used to create "smart contracts" that can be used to encode arbitrary state transition functions, allowing users to create any of the systems, simply by writing up the logic in a few lines of code. Regarding the application in finance, Bitcoin functions as a digital cash, while Ethereum functions as a smart contract platform where a financial system can be built on. We have already witnessed the born of decentralized exchanges, lending protocols, stablecoins, and many others based on Ethereum. 

In 2015, Gavin Wood (also the creator of Polkadot) made the semi-formal specification in the [Yellowpaper](https://ethereum.github.io/yellowpaper/paper.pdf). Notice that the Yellwopaper keeps updating along with the protocol updates which is tracked through a process called [Ethereum Improvement Protocols](https://eips.ethereum.org/). 

The yellowpaper is general enough and mathematical in nature and doesn't rely on specific implementation details and algorithms, however not easily understandable by developers. Thus [Execution specs](https://github.com/ethereum/execution-specs) and [Consensus specs](https://github.com/ethereum/consensus-specs) are created. These specs are implemented in Python and serve as a blueprint and source of truth for all Ethereum implementations.


## Protocol Implementations and Development
* execution layer (EL)
* consensus layer (CL) 


## Reference
* https://epf.wiki/#/eps/week1?id=prehistory-and-philosophy
* https://bitcoin.org/bitcoin.pdf
* https://ethereum.org/whitepaper#ethereum-whitepaper
* https://ethereum.github.io/yellowpaper/paper.pdf
