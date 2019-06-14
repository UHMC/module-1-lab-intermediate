# Module 1 - Intermediate Lab: Visualizing the technical aspects of Bitcoin
## Background
In 2009, Bitcoin was invented by an anonymous person or group and released as open-source software capable of supporting peer-to-peer digital financial transactions without the need for a central authority. In modern times, there have been many new cryptocurrencies using the same or similar mechanisms, each with their own style and features. This lab will allow the reader to explore the world of Bitcoin in a visual way. 

## Meta Information

| Attribute | Explanation |
| - | - |
| Summary | This lab will explore Bitcoin transactions and network statistics visually.|
| Topics | Bitcoin, transactions, blockchain, decentralization, visualization |
| Audience | CS1 and above. |
| Difficulty | Intermediate |
| Strengths | Familiarizes the reader with Bitcoin as a technology. |
| Weaknesses | Technical details and displays may be hard to grasp on initial exposure. |
| Dependencies | A computer with internet access and a suitable browser. |
| Variants | This lab is focused on Bitcoin, but a similar tour could be constructed for other systems such as Ethereum. |

## Assignment Instructions (15 Minutes)
1. Our first stop is the book this lab and many others are based on, which the reader may find useful in a quest for a deeper understanding of Bitcoin, [Mastering Bitcoin 2nd Edition][BitcoinBook]. Although a print version exists, the authors have made the entire text conveniently open-source and available on GitHub. [Here's a link to the first chapter.][BitcoinBookChapter01]
2. Bitcoin's value is what most people know about Bitcoin. Its exponential increase in value made speculators flock to the cryptocurrency like they discovered fire. [Here's a visualization on world currencies (like the USD or JPY) being spent at exchanges to buy Bitcoin.][FiatLeak] and [here's a graph showing the number of transactions over Bitcoin's inception.][BTransacsAll]
	* [Here's a visualization of unconfirmed transactions][VisualUTransacs]
	* and [here is a VR way of looking at transactions happening around the globe][BitcoinVR]
3. Bitcoin in its simplicity is just a ledger. This ledger becomes bigger and bigger as more and more transactions are created. Blockchain size is a measure of how big this ledger is. [You can see a graph of the size of the Bitcoin blockchain size here.][BlockchainSize]
4. Bitcoin transactions are placed in a pool of unconfirmed transactions. Bitcoin uses miners to pick unconfirmed transactions to add to the blockchain. These miners race to find the solution of a mathematical problem in order to get a reward in Bitcoins. Once this solution is found, the transactions picked by the miner are added to a block that will be placed on the overall blockchain. [You can see the average number of transactions per block here.][AvgTransacsBlock]
	* [Here's a graph of the difficulty of the mathematical problem that the miners must solve.][Bdifficulty]
	* [Here's a graph of the reward that these miners get from solving the mathematical problem.][Breward]
5. The backbone of the Bitcoin network is made up of what are called nodes. You can see a couple of maps [here][BnodesLive] and [here][BnodesMap].

## Credits
Dr. Debasis Bhattacharya  
Mario Canul  
Saxon Knight  

[BitcoinBook]: https://github.com/bitcoinbook/bitcoinbook
[BitcoinBookChapter01]: https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch01.asciidoc
[VisualUTransacs]: https://dailyblockchain.github.io
[BnodesLive]: https://bitnodes.earn.com/nodes/live-map/
[BnodesMap]: https://bitnodes.earn.com/nodes/network-map/
[FiatLeak]: https://fiatleak.com 
[BitcoinVR]: https://bitcoin-vr.github.io
[BTransacsAll]: https://www.blockchain.com/charts/n-transactions?timespan=all
[BlockchainSize]: https://www.blockchain.com/charts/blocks-size?timespan=all
[AvgTransacsBlock]: https://www.blockchain.com/charts/n-transactions-per-block
[Bdifficulty]: https://www.blockchain.com/charts/difficulty?timespan=all
[Breward]: https://www.blockchain.com/charts/miners-revenue?timespan=all
