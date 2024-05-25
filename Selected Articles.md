# Selected Articles

**What is CKB?**

Common Knowledge Base (CKB) is a public blockchain inspired by Bitcoin's core principles of Proof of Work (PoW) and the UTXO model. CKB's foundational goal is to enable billions of users to be "[First-class Citizens](https://medium.com/nervosnetwork/first-class-asset-ff4feaf370c4)” on the blockchain, interacting in peer-to-peer networks with least trust assumptions and ease.

Through [NC-Max consensus](https://eprint.iacr.org/2020/1101), [Cell model](https://docs.nervos.org/docs/basics/concepts/cell-model/) (generalized UTXO) and [RISC-V based VM](https://docs.nervos.org/docs/basics/concepts/ckb-vm/), CKB enables itself with high-degree modularity and programmability. It understands and speaks the languages of all existing and future heterogeneous blockchains, allowing developers and communities to build fully interoperable and highly scalable cross-chain ecosystems.

CKBbyte token ($CKB) is used as the native token serving a dual purpose: it facilitates transactions but more importantly represents storage rights on the blockchain. Owning one CKByte entitles the holder to one byte of data storage on Nervos. This design is pivotal in aligning network values and transaction/assets values on the blockchain.

CKB mainnet was launched in 2019 and had its first halving in 2023. The network was secured by ASICs [from 2020](https://medium.com/coinmonks/is-decentralized-asic-production-possible-eb5caece672c).

**CKB in a Nutshell**

[https://x.com/xcshuan/status/1767101459659669615?s=20](https://x.com/xcshuan/status/1767101459659669615?s=20)

**Github**: [https://github.com/nervosnetwork](https://github.com/nervosnetwork)

**Website**: [www.nervos.org](http://www.nervos.org/)

**Explorer**: [https://explorer.nervos.org/](https://explorer.nervos.org/)

**CKB as a BTC L2**

[CKB Eco Fund](https://ckbeco.fund/) and [Cell Studio](https://cell.studio/), together with other teams in the ecosystem kicked off the "BTCKB" initiative in January and re-pitched CKB as a Bitcoin L2. [**Bitcoin Renaissance: Why & How** -  [Jan Xie](https://twitter.com/busyforking) @ Bitcoin Singapore - [[Slides](https://docs.google.com/presentation/d/1xGSQ2L_jNMMYtdzixQg8D1VElfB3lIoEikFPhiLlcLw/edit?usp=sharing)] [[Article](https://docs.google.com/document/d/1qJvnLmuf85z-UdcQR2-gpUKhCSlXJ1Ts4G3HPac3qs0/edit)]]

Comparing to other BTC L2s, CKB is more decentralized/secure (POW consensus) and ecosystem compatible - CKB has similar data structure as it's based on an extension of Bitcoin’s UTXO and similar UX because users can use Bitcoin addresses and wallets to access CKB (native account abstraction).

**Key Components of the “BTCKB” initiative**

1. RGB++, a new Bitcoin asset standard [[RGB++ Lightpaper](https://talk.nervos.org/t/rgb-protocol-light-paper-translation/7790)], [[RGB ++ SDK](https://github.com/ckb-cell/rgbpp-sdk?tab=readme-ov-file#rgb-sdk)] released on April 3.

2. [UTXO stack](https://cointelegraph.com/press-releases/utxo-stack-pioneering-bitcoin-layer2-solution-secures-major-seed-funding), an Bitcoin L2 framework backed by OK ventures and Bitcoin Magazine’s venture arm. ETA Q2 2024.

3.The team is also working on "CKB lightning" to connect pieces together.

**Roadmap** -  [https://twitter.com/ckbcell/status/1763521124741357973](https://twitter.com/ckbcell/status/1763521124741357973)

***Relevant Links:***

- *ELI5 of RGB++: [https://twitter.com/0xblessed_/status/1778910759398891663](https://twitter.com/0xblessed_/status/1778910759398891663)*
- [RGB++ ecosystem projects](https://www.notion.so/RGB-Ecosystem-c66589a3bcb9430c8ca392b4231fd1d0?pvs=21)
- [Deep dive into RGB++ security](https://talk.nervos.org/t/a-deep-dive-into-rgb-security-analysis-translation/7816)
- [Isomorphic Binding: The Heartbeat of Cross-Chain Synchronization in RGB++](https://mirror.xyz/zhixian.eth/2xAcBzO28RueHTaNFMU2MTaM1jFT0MoV0ZtXb7madxk)

**CKB Network States:**

- Nov 19, 2023 - CKB’s first halving reduced real inflation from 7.9% to 3.7%. [Link](https://cryptopotato.com/nervos-community-gears-up-for-first-ckb-halving/) & [mining hash rate growth](https://explorer.nervos.org/charts/hash-rate)
- Unique Addresses Used - 3.75M [[link](https://explorer.nervos.org/charts/address-count)] It grew 600k from 3.15M in the last 3 months.
- Average daily on-chain transactions count [[link](https://explorer.nervos.org/charts/transaction-count)]
- Assets Locked in Nervos DAO is 9.19 billion CKB, with deposit to circulation ratio at [20.65%](https://explorer.nervos.org/charts/circulation-ratio)

**CKB Is An Ideal Bitcoin Layer 2**

As a monetary system, Bitcoin is inherently layered. But what should a Bitcoin monetary layer 2 look like? It should be an integral part of the entire system, sharing the same foundational values and design decisions. Ideally, it would be interconnected with layer 1, allowing for free BTC flow between layers, and offering a consistent user experience for both users and developers.

CKB is the ideal monetary layer 2 for Bitcoin. CKB shares Bitcoin values, e.g. PoW not PoS, UTXO not Account, decentralization over TPS, no issuance manipulation, etc. With Cell, an extended UTXO model, CKB can provides more decentralized use cases for Bitcoiners while maintaining a consistent user and developer experience. Imagine operating CKB applications with a Bitcoin wallet, rotating addresses for privacy, and managing UTXOs under dust limit / minimum capacity constraints - all underpinned by the same foundational principles.

Moreover, CKB is an excellent experimental ground for Bitcoin, provides an enhanced UTXO model with stronger programming capabilities while upholding Bitcoin's core values and design philosophy. This means CKB faces challenges akin to those of Bitcoin, with optimal solutions potentially benefiting both. The ability to use customized cryptographic primitives on CKB empower developers and researchers to explore their most innovative ideas. On CKB, it's easier to test new ideas like covenant (CTV), PSBT and Intents, which, if successful, could be integrated back into Bitcoin Layer 1.

Importantly, a monetary layer 2 doesn't need to share security with Bitcoin. Multiple monetary layer 2s can form a more decentralized, resilient, and loosely connected monetary system with Bitcoin at its core. This system wouldn't have a single point of vulnerability in terms of security, and it would offer consistent user experience without liquidity fragmentation seen elsewhere. Because Bitcoin is money, it only needs to provide monetary functions, not everything else. Because UTXO is the first-class citizen here, accounts are abstracted away and managed off-chain.

[**CKB, Version Control and Blockchain Evolution**](https://talk.nervos.org/t/ckb-version-control-and-blockchain-evolution/4819)

I’m Linus’s fan. This guy created an open-source operating system running everywhere, co-authored a book which is one of my favorites, and built a distributed version control system used by almost every developer everyday. I switched to Git the moment I met it, fascinated by its speed and elegance. A [version control system 5](https://en.wikipedia.org/wiki/Version_control) is what developers use to manage source code, so they can keep the track of code updates, share modifications with friends and colleagues, rollback to a previous bug-free version when something new goes wrong, etc. Git made life much more enjoyable, I hope CKB can do the same.

![https://talk.nervos.org/uploads/default/original/2X/7/796a7f7edb66d84889944fb1f590024d9dfc9b21.jpeg](https://talk.nervos.org/uploads/default/original/2X/7/796a7f7edb66d84889944fb1f590024d9dfc9b21.jpeg)

## CKB is Git

Git inspires the idea of the Cell model and CKB. Although Git is invented out from Linus’s eager desire for the convenience of Linux kernel development, people use it whenever they want to organize something, from notes to blog posts to pictures. It’s a knowledge base with excellent history tracking support. A git knowledge base is called a ‘repository’, it maintains an immutable append-only object database (does it ring a bell?) internally. The basic storage unit in Git is Blob (binary large object) which is just an object contains the data people stores in the repository, just like a cell in CKB. A blob object is created for each version of each file. Whenever you create a new file, you create a new blob. Whenever you modify an existing file, you create a new blob with modified content, leave the old blob untouched (sounds familiar?). Every blob is hashed and the blob hash is used as the identifier to reference a blob. After a few hours of work you created some new files and modified some existing files, you commit all the changes into the repository, synchronize the new commit to peers and call it a day. A commit is the basic history point in Git, the repository history consists of a series of commits, from the genesis of the repository to its latest update. A commit is a version of the repository at some certain time, including version metadata like author, timestamp, parent commit, and reference to a tree of blobs. Just like the block header keeps the metadata for each update of a blockchain, by writing down miner address, timestamp, parent hash, and the root of the transaction merkle tree. You and your colleagues keep extending the history of a git repository to get paid like miners keep extending the history of blocks to get block reward.

A git repository can have forks too. People work on different forks, but which fork is the “right” one is chosen by the repository maintainer, not by consensus. Git is a distributed system without consensus, relies on ad-hoc peer-to-peer communication such as ssh or email for data exchange. The resemblance between Git and blockchain means, with cautiousness we should be able to incorporate the idea of Git without introducing conflicting design choices into a blockchain, so the blockchain or smart contract developer can enjoy some of the proven merits of Git. **That’s what CKB looks like under the cover, a sole huge Git repository with real p2p network, global consensus, and enhanced blobs, being constantly updated by a swarm of anonymous.**

[ckbisgit-git858×531 25.4 KB](https://talk.nervos.org/uploads/default/original/2X/a/a9cc4d26da3044915c02cdd44542f769dd33a321.png)

![https://talk.nervos.org/uploads/default/optimized/2X/a/a9cc4d26da3044915c02cdd44542f769dd33a321_2_690x427.png](https://talk.nervos.org/uploads/default/optimized/2X/a/a9cc4d26da3044915c02cdd44542f769dd33a321_2_690x427.png)

*Figure 1. This is not a blockchain.*

## Name The Cell You Like

At the core of both Git and CKB is data objects (blob/cell) and hash references. A hash reference is the inherent name of an object, a magic wand you can wield to extract the value of data. If you can speak an object’s name, you can harness its power. On CKB the code and user data of a smart contract are separated, so the hash reference allows you to name a piece of code or user data directly, make them [first-class objects 1](https://talk.nervos.org/t/first-class-asset/1293) in the system. This fine granularity creates a flexible and powerful programming model. Here’re some examples.

### Code/Data Reuse

Because a cell is a referencable storage unit, code/data reuse on CKB is easy. Suppose there’s some shared code/data stored in the cell `0xbeef#1` (the output `1` of transaction `0xbeef`). To reuse it, first load the cell `0xbeef#1` as a transaction dependency (`cell_deps`), then read data from it with `ckb_load_cell_data` syscall, as the [default lock script demonstrated 1](https://github.com/nervosnetwork/ckb-system-scripts/blob/master/c/secp256k1_helper.h#L40-L66). Once the data in cell `0xbeef#1` is loaded into VM memory, it can be treated either as code or data, depends on your need. This way CKB works like a shared repository of code and data for smart contracts running on it. Isn’t it cool if we can [build a smart contract by combining existing secure legos 2](https://talk.nervos.org/t/rfc-swappable-signature-verification-protocol-spec/4802/2)? There’s no need to copy the code from somewhere on Github and deploy the same code again and again, which is a waste of both your time and on-chain space. The analysis of Ethereum contracts [[1] 2](https://www.researchgate.net/publication/332799463_Characterizing_Code_Clones_in_the_Ethereum_Smart_Contract_Ecosystem) [[2] 2](https://security.cse.iitk.ac.in/sites/default/files/17111011.pdf) shows 95%~99% of them are duplicates.

[Screenshot_20200707_1810391145×509 80.7 KB](https://talk.nervos.org/uploads/default/original/2X/b/bda6126f10349dfc0c5c72f32be5ed089bb3adde.png)

![https://talk.nervos.org/uploads/default/optimized/2X/b/bda6126f10349dfc0c5c72f32be5ed089bb3adde_2_690x306.png](https://talk.nervos.org/uploads/default/optimized/2X/b/bda6126f10349dfc0c5c72f32be5ed089bb3adde_2_690x306.png)

*Figure 2. Most duplicated smart contracts on Ethereum.*

### Dependency-Kill Resistance

In the above code/data reuse example, you don’t need to worry that someone modifies the code/data stored in the dependency cell because cells are immutable, i.e. there’s no way to modify it. But what if the dependency cell owner simply remove it from CKB? Wouldn’t that make my smart contract unusable?

That’s true on Ethereum. If you have been in this space long enough you probably know the [accidental bust of 280 million USD 6](https://medium.com/hackernoon/what-caused-the-latest-100-million-ethereum-bug-and-a-detection-tool-for-similar-bugs-7b80f8ab7279) in 2017. The whole tragedy is triggered by the accidental deletion of an Ethereum smart contract which is used by many other smart contracts. The deletion caused all dependent smart contracts dysfunction and all assets stored in them froze.

Such an accident is no big deal on CKB, as anyone who keeps a copy of the code (e.g. those runs full node or sophisticated light client) can deploy the same code on-chain again and the code hash reference will still work. Just use the new dependency cell to construct your transactions. No one would be hurt, everything would be fine.

![https://talk.nervos.org/uploads/default/original/2X/0/07f309521c9149e8c40410dd9b758a7460ebc4ae.png](https://talk.nervos.org/uploads/default/original/2X/0/07f309521c9149e8c40410dd9b758a7460ebc4ae.png)

*Figure 3. Recover from dependency kill.*

Actually we can exploit this intentionally to achieve “use-then-deploy”. Suppose you want to use a new customized lock script (a smart contract) to protect your cells. Rather than the usual deploy-then-use flow, you can use it without deploy. Just put the code hash of your new lock script (the implementation) in cell locks (the usage), then those cells are guarded by the new lock, effective immediately.

The deployment of the actual lock script code can be delayed until the moment you want to unlock those cells. To unlock, first, you deploy the script code on-chain, then send another transaction to unlock those cells as usual. After cells are unlocked you can delete the deployed code and claim occupied CKBytes back to reduce unnecessary storage cost. An extra benefit of use-then-deploy is better privacy - no one knows what’s the logic of this new lock is before you unlock it.

## Evolve CKB

Now you understand the similarity between CKB and Git and the benefits. A more interesting question is if CKB is a git repository can we use CKB to manage the code of CKB?

Yes! That’s why some CKB core functions like [transaction signature verification 2](https://github.com/nervosnetwork/ckb-system-scripts/blob/master/c/secp256k1_blake160_sighash_all.c) and [Nervos DAO 1](https://github.com/nervosnetwork/ckb-system-scripts/blob/master/c/dao.c) are implemented as a smart contract. Take transaction signature verification for example - it is a core function of almost every blockchain and hardcoded in the native language (e.g. written in C in Bitcoin, Go in go-ethereum). To upgrade the blockchain a new software version must be distributed and deployed on majority nodes (soft-/hard-fork), which requires tremendous coordination effort. For CKB, the transaction signature verification can upgrade like other smart contracts, by deploying a new version on-chain. That gives CKB the same long-term upgradability proposed by [Tezos 2](https://tezos.com/).

We can do even better. On CKB [each user holds his/her own data 2](https://medium.com/nervosnetwork/the-smart-contract-risk-in-defi-c28e53b92f03) so a contract is more like a 2-party agreement between the user and CKB and individuals can make independent choices. If you use a contract by its [code hash 1](https://github.com/nervosnetwork/rfcs/blob/master/rfcs/0022-transaction-structure/0022-transaction-structure.md#upgradable-script), it means “I agree to this specific version of this contract”. You don’t need to worry that the developers upgrade the contract code someday, as the code hash of new contract will be different and your lock/type will still refer to the old one instead of the new one. After a new version is deployed, it coexists with old versions in the system. If you use a system contract by its code hash, the new version will not affect you, and you can decide independently whether to upgrade or not. If the answer is yes you can update all cells to use the new version. Otherwise, just do nothing and stay with the old version.

This is a friendly guarantee to holders who may not be online frequently, as they can be assured the contract attached to their cells at creation time will never be changed. **Your assets will be always locked in the way you specified when you lock it. That’s the ultimate guarantee for SoV users and why CKB assets are different from assets on other blockchains.** It’s the same guarantee Bitcoin provides to holders by following a soft-fork only approach. The only downside is you bear the “too-late” risk when there’s a security upgrade. So for convenience, some people may still prefer to always stay with the latest version because they trust the dev team and don’t bother with contract review and manual upgrade, in which case they use the [`type id` 1](https://xuejie.space/2020_02_03_introduction_to_ckb_script_programming_type_id/) to reference contracts. Roughly speaking `type id` is like `HEAD` in Git, an updatable reference always points to the current version. **By providing both options - reference by code hash and reference by type id - the right to choose appropriate upgrade strategy is given back to users.** It’s always good to have options. We can have different choices, no one would be coerced to upgrade.

[ckbisgit-evolution691×671 20.1 KB](https://talk.nervos.org/uploads/default/original/2X/8/8797232a152a2e7cf16a50eb46b710c319f0bb7f.png)

![https://talk.nervos.org/uploads/default/optimized/2X/8/8797232a152a2e7cf16a50eb46b710c319f0bb7f_2_514x500.png](https://talk.nervos.org/uploads/default/optimized/2X/8/8797232a152a2e7cf16a50eb46b710c319f0bb7f_2_514x500.png)

*Figure 4. System script upgrade.*

In the long term, CKB will be more and more abstract and modular, more core functions will be extracted and implemented in the on-chain smart contracts. In its complete form, we should be able to upgrade CKB without soft-/hard-forks. A missing piece to that is how we, the community, decide to upgrade a system contract or not, or what’s CKB’s governance model? More accurately, how we decide to upgrade the `type id` of a system contract. Today CKB uses the same off-chain governance model as Bitcoin and we still rely on soft-/hard-forks. To enable a new version of system script for people using its `type id` reference, a hard-fork is required to update the `type id` reference to point to the new version, because the code cell is locked by an [unlockable lock 3](https://explorer.nervos.org/address/ckb1qgqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqhzeqga) (check its code hash). It is an intentional choice not to use a multi-signature lock controlled by the core team because the upgrade of system script should follow a governance decision made by the community.

As we stated in [position paper 4](https://github.com/nervosnetwork/rfcs/blob/master/rfcs/0001-positioning/0001-positioning.md#47-governance), although there’re many interesting proposals we haven’t seen a viable governance model yet. Once we figured out the right governance model, the unlockable lock can be replaced with a “governance lock” that allows the system smart contracts to be upgraded with community consent, e.g. the result of votes. Before that, we’ll stick with the imperfect off-chain governance model for a while, but the backbone for CKB governance and evolution is already there.

# UTXO，A Different Expectation for the Bitcoin Ecosystem

By Jiaji Song, Researcher of Guosheng Securities; Heyi Ren, Researcher of Guosheng Securities.

# Abstract

As we all know, Bitcoin does not have the smart contract capabilities of Ethereum. Unlike Ethereum's ERC20 contracts,  Bitcoin has a UTXO model that enables applications built on the Bitcoin UTXO architecture to naturally share security with the main chain, bringing much anticipation to the market. This model may create an ecosystem different from Ethereum's Layer 2, which is also eagerly awaited by the market.

Compared to Ethereum, UTXO is Bitcoin’s most distinctive accounting model, so

the Bitcoin Layer 2 (L2) ecosystem is expected to develop differently from Ethereum's.

As industry competition intensifies and technology advances, Ethereum's Layer 2 has developed rapidly in recent years, and the overall control of Ethereum's on-chain gas fees amid a thriving ecosystem has been achieved. However, the Bitcoin ecosystem is still very nascent.

The recent rise of inscriptions, Runes, and other Ordinals applications has provided a possibility for building applications based on UTXO. The inscriptions and Runes activities in 2023 have brought active on-chain transactions, laying the foundation for exploring the potential of UTXO.

The Taproot upgrade further enhances the potential for Bitcoin ecosystem development.

As the  most significant upgrade since the activation of Segregated Witness (SegWit), the Taproot upgrade aims to further improve the Bitcoin network's privacy and efficiency.

The most notable change of the Taproot upgrade is that it allows multiple complex signatures (such as multi-signature wallets) to be aggregated and verified together, rather than being verified separately. By aggregating signatures, the network's performance is faster, the fees are lower, and block space is saved. Taproot provides a new way to execute Bitcoin transactions by enhancing user privacy and flexibility, which will greatly improve Bitcoin's scalability.

Nervos CKB’s Cell is like a smarter UTXO. If Bitcoin's UTXO is a box holding a paper ledger, then a Cell is like replacing the paper ledger with an Excel spreadsheet. Nervos CKB inherits Bitcoin's UTXO architecture and has created the Cell Model—a generalized UTXO model for state storage that maintains UTXO’s simplicity and consistency. In CKB, all states are stored in Cells, computations are done off-chain, and transactions are verified and posted on-chain by nodes. Unlike Bitcoin's UTXO, a Cell can contain various data types, such as CKBytes, tokens, JavaScript code, or JSON strings, which broadens the capabilities of Cells and thus extends the potential of UTXO—for instance, enabling smart contracts (even customized ones like issuing NFT tokens, limiting token supply, and setting conditions to meet unique needs).

Will the uniqueness of UTXO also foster a unique ecosystem? The in-depth exploration of Bitcoin’s UTXO by Ordinals and Runes has made asset deployment based on UTXO possible, and Nervos CKB’s upgrade of UTXO further liberates computational power. These developments hint at the unique potential applications of UTXO, which seem more interesting and have become a new expectation in the industry. Looking at the development of Ethereum, from the ERC20 standard that led to ICOs to the development of AMMs that energized DeFi, and the emergence of NFTs and the metaverse, its ecosystem paradigm has gradually become richer. However, this process was not achieved overnight; it was fraught with twists and turns. Bitcoin’s recent innovations have initially received significant market attention, a good sign indicating strong market confidence and expectation for the potential of UTXO. However, as the hype comes quickly, it cools down swiftly too. After the emergence of Runes, the enthusiasm for Ordinals naturally declined. Currently, both Ordinals and Runes are still in the stage of competing for "mints." Minting is just the beginning; the more important tasks are how to develop applications and enrich the ecosystem moving forward. The situation with Nervos CKB is similar, as its current ecosystem applications can be seen as a simple "copy" of Ethereum's ecosystem.

Risk warning: The development of blockchain is not as expected; regulatory policy remains uncertain; The implementation of Web3 business model may not be realized as expected.

# 1. Core Points

Bitcoin's UTXO itself does not possess smart contract capabilities, and currently, Bitcoin has not yet developed an ecosystem as rich as Ethereum's. With the exploration of UTXO potential through the Ordinals protocol, Nervos CKB, and others, new applications such as inscriptions and Runes are gradually becoming the focus of industry attention. Applications built on the UTXO architecture naturally share security with the main chain, which also brings much anticipation to the market, potentially creating an ecosystem unlike Ethereum's Layer 2. This is also a market expectation.

This article analyzes several typical UTXO application models and provides an outlook on the Bitcoin ecosystem.

# 2. The Spring of UTXO, Potential Growth for BTC L2 Ecosystem

## 2.1 UTXO-based BTC L2 is Expected to Foster a New Ecosystem

The principle of blockchain requires decentralized nodes to reach consensus and confirm, inevitably leading to decreased efficiency. Therefore, handling tasks (transfers or executing smart contracts) is naturally not as fast as centralized nodes, a typical impossible trinity problem (security, scalability, decentralization cannot be optimized at the same time). From the perspective of enhancing scalability, a second-layer network (Layer2, L2) is a widely adopted solution. Under the rapid development of Ethereum L2 in recent years, the thriving ecosystem has overall controlled the on-chain gas fees, while the Bitcoin network ecosystem is still very nascent. The on-chain transactions brought about by inscriptions in 2023 and Runes this year can be seen as a rapid increase in the fees of the Bitcoin network (see Figure 2).

[https://lh7-us.googleusercontent.com/5cOgkqe-9rGIa3AwE43foU3wd3JO3pOLLCVtg4iuSy55Xa3NpZi8YXVZdonbJgtfoL5eyJjc6mNKPxtU5MTp9RO3t8HzqhpRoFCV8d2Y-iFSKTrgh7t0W9szZrjsLSruFELpkbyhKLj4TBlj93qgkdA](https://lh7-us.googleusercontent.com/5cOgkqe-9rGIa3AwE43foU3wd3JO3pOLLCVtg4iuSy55Xa3NpZi8YXVZdonbJgtfoL5eyJjc6mNKPxtU5MTp9RO3t8HzqhpRoFCV8d2Y-iFSKTrgh7t0W9szZrjsLSruFELpkbyhKLj4TBlj93qgkdA)

[https://lh7-us.googleusercontent.com/5LojzJpI8hUqBp0TnrrNKxqKlqJlPvFzk2QhMZB2ffe7ig-od6teZMEgHJshqSGNCJgcf0QSPa3rgNPeEitq3WNvmaJ_g9WQiG5oeyjmX18GHFfMn5Bv0ID774mFWGu4RiqTQVSvOoygpBWJcrJZWPs](https://lh7-us.googleusercontent.com/5LojzJpI8hUqBp0TnrrNKxqKlqJlPvFzk2QhMZB2ffe7ig-od6teZMEgHJshqSGNCJgcf0QSPa3rgNPeEitq3WNvmaJ_g9WQiG5oeyjmX18GHFfMn5Bv0ID774mFWGu4RiqTQVSvOoygpBWJcrJZWPs)

The UTXO model makes every satoshi of Bitcoin "non-fungible," promising an ecosystem different from Ethereum's. Since Bitcoin has no accounts, the outputs created by Bitcoin transactions are not simply public key addresses but scripts. To understand this, consider a transaction where Bob pays Alice 1.5 BTC. In this transaction, Bob's output script would include Alice's public key hash. The script means that whoever can provide a signature to run the script containing Alice's public key can spend the 1.5 BTC of this transaction. Obviously, only Alice's private key can create a signature that will pass this script's verification, ensuring that no one else can impersonate Alice to spend these funds. In other words, the BTC in a UTXO is not recorded in someone's account as a balance—each transaction initiator creates a lock for these BTCs through a script, and only the owner has the key—of course, some Bitcoin transfers may have inputs (transfer initiators) and outputs (transfer recipients) composed of multiple historical UTXOs, similar to assembling different denominations of banknotes. One benefit of this approach is that all transfer transactions are viewed from the perspective of BTC circulation, and different UTXOs can undergo parallel transactions, as UTXOs are strictly distinguished from each other. It can also be understood that the UTXO mechanism completely records the transfer history of all parts of BTC (the smallest unit is "satoshi", sats), and each satoshi is like a coin, getting a stamp every time it transfers. Compared to Ethereum, UTXO is Bitcoin's most characteristic data model, so Bitcoin L2 is expected to present an ecological model different from Ethereum's.

The upgrade further enhances the development potential of the Bitcoin ecosystem. We all know that the Bitcoin Taproot upgrade is the most important upgrade since the activation of Segregated Witness (SegWit). Taproot aims to further improve the network's privacy and efficiency. The most significant change in the Taproot upgrade is allowing the aggregation and verification of multiple complex signatures (such as multi-signature wallets) together rather than individually. By aggregating signatures, the network performs faster, costs less, and saves block space. Taproot enhances user privacy and flexibility, providing a new way to execute Bitcoin transactions and greatly improving Bitcoin's scalability.

[https://lh7-us.googleusercontent.com/X2D6g6__NR4wjXd4qSb-psdkDWp1bqZ7gy9YbGCEe3tnklivjvZ8fs5A69vflJuPBBp6w6P21kwmtHaywB8rnksLOKLDKOuYzb8PtapElYQNL3c63T1PQsKNbFILMXNawXu_J3u_JSNNB1GVfwxvf5U](https://lh7-us.googleusercontent.com/X2D6g6__NR4wjXd4qSb-psdkDWp1bqZ7gy9YbGCEe3tnklivjvZ8fs5A69vflJuPBBp6w6P21kwmtHaywB8rnksLOKLDKOuYzb8PtapElYQNL3c63T1PQsKNbFILMXNawXu_J3u_JSNNB1GVfwxvf5U)

With the emergence of the Ordinals protocol, inscriptions and Runes have further promoted the development of the Bitcoin ecosystem. As of May 6, the TVL of the Ethereum ecosystem exceeded 96 billion US dollars, and the Bitcoin ecosystem has experienced rapid development in the past year, with a TVL of 1.2 billion US dollars. Undoubtedly, compared with Ethereum, the development of the Bitcoin ecosystem is still in its early stages.

## 2.2 The Ordinals Protocol Further Explores New Possibilities for UTXO

Considering the development of Ethereum Layer2, Bitcoin L2 also has different technical routes. It is well known that Bitcoin does not have the smart contract capabilities of Ethereum, so the technical routes of Bitcoin's second-layer networks involve state channels (such as the Lightning Network), sidechains, Rollups, etc., mostly relying on L2 to extend smart contract capabilities. Cross-chain bridges enable asset bridging between Bitcoin's main chain and L2, which can be considered a type of sidechain. A core issue of side chains is how to achieve consensus and shared security with the main chain of Bitcoin, and interacting with Bitcoin's UTXO is an unavoidable step. The recent rise of inscriptions and Runes applications has provided a possibility for building applications based on UTXO. Applications built on the UTXO architecture naturally share security with the main chain, which also brings much anticipation to the market, potentially creating an ecosystem unlike Ethereum's L2. This is also a market expectation.

Under the UTXO model, the circulation of every satoshi (sats i.e. the smallest unit of Bitcoin) of BTC is traceable and non-fungible (perhaps the earliest form of NFT), providing a foundation for developing the Ordinals protocol and the BRC-20 ecosystem. In December 2022, Bitcoin developer Casey Rodarmor released an open-source software called ORD, running on top of the Bitcoin Core full node. Simply put, this software allows users to input any information, such as a string of text or an image, into the Bitcoin blockchain, and then bind this uploaded information to a specific satoshi, ultimately creating a satoshi with some information, also known as a Bitcoin NFT. To be more precise, the Ordinals protocol consists of two parts: Ordinals and Inscription. Fundamentally, Ordinals is a scheme for serializing Bitcoin's smallest unit, satoshis (1 BTC = 100,000,000 sats), and allows for tracking and transferring individual satoshis. Here, satoshis are serialized in the order they are mined and transferred from transaction inputs to outputs in a first-in, first-out order. Once each satoshi is numbered, content can be written into the transaction's "Segregated Witness area," and this content will be assigned to the first satoshi of the transaction output. This writing process is called inscribing, and the written content is called Inscription. The Inscriptions here can be images, text, audio/video, or even code, theoretically as long as the size does not exceed the 4MB limit of a Bitcoin block. Therefore, Inscription is very similar to NFT in its presentation form, while Ordinals is a protocol that allows people to mint something similar to Ethereum's NFTs on the Bitcoin network.

The Ordinals protocol can not only be used to issue NFTs, but also tokens—when Inscriptions are attached in JSON data format, they can be used to issue tokens. Thus, further exploration of UTXO's potential has led to the development of new asset protocols like BRC-20, promoting the development of applications such as Ordinals and Runes. Since the emergence of BRC-20, transactions on the Bitcoin blockchain have accounted for a significant proportion, indicating the unique development potential of the Bitcoin L2 ecosystem.

[https://lh7-us.googleusercontent.com/Jj1E8dMQJNFqHhIWLRg7hQMCqmf1Kd7fiIp-_Z_p5Om3mdX01J8AgyATR_L9RwSm3l7fUK8Mxxn5m2KebwOhOCWOo2lc8gLkwcMi6nxagIRnwcWf6KJZDhQXimnMrSpKlXWZ_amMtLGbz6YHRPCQaXw](https://lh7-us.googleusercontent.com/Jj1E8dMQJNFqHhIWLRg7hQMCqmf1Kd7fiIp-_Z_p5Om3mdX01J8AgyATR_L9RwSm3l7fUK8Mxxn5m2KebwOhOCWOo2lc8gLkwcMi6nxagIRnwcWf6KJZDhQXimnMrSpKlXWZ_amMtLGbz6YHRPCQaXw)

# 3.What Ecosystem Applications Will UTXO Produce?

## 3.1 The Ordinals Protocol Gives Rise to the Inscriptions and Runes Ecosystem

BRC-20 originated from a community experiment and is an attempt in the Bitcoin ecosystem. On March 9, 2023, Twitter user domodata published what he called "an interesting and experimental standard" known as BRC-20 on GitBook, based on the Ordinals protocol. It allows Inscriptions to be set in JSON data format to deploy, mint, and transfer tokens. Simply put, domodata believes that the Ordinals protocol can be used not only to issue NFTs but also tokens when Inscriptions are attached in JSON data format. Thus, BRC-20 tokens can be understood as a variant of Ordinals NFTs, where Inscriptions on NFTs are images, but on BRC-20, Inscriptions are uniformly in JSON format as text data. BRC-20 mainly provides three standards for issuing fungible tokens on the Bitcoin network: deploying (deploy), minting (Mint), and transferring (Transfer) BRC-20 tokens. Developers can complete the deployment and issuance of BRC-20 tokens by following this standard. On the GitBook homepage, domodata also provided examples of deployment, minting, and transfer.

The BRC-20 standard has rapidly promoted the development of Inscriptions, as the potential of Bitcoin blocks and UTXO has rarely been deeply explored. This is an interesting experiment based on Bitcoin UTXO, which has been embraced by the community and users.

[https://lh7-us.googleusercontent.com/bCMzLYvoaKRNuiWcC-h3KYMyzvYO1v8SDCEz1UFkYmW3Bl_mTpertkycU_i1tnB9EnPhtcyYsJcudfAX0kVSIFL473KHuvtweQJ00CrDFlc6HndS34Zm33oXKjqwBF64VAmn3EAKzlvGKZwFkYqSTgw](https://lh7-us.googleusercontent.com/bCMzLYvoaKRNuiWcC-h3KYMyzvYO1v8SDCEz1UFkYmW3Bl_mTpertkycU_i1tnB9EnPhtcyYsJcudfAX0kVSIFL473KHuvtweQJ00CrDFlc6HndS34Zm33oXKjqwBF64VAmn3EAKzlvGKZwFkYqSTgw)

Source:

[domo-2.gitbook.io](http://domo-2.gitbook.io/)

[https://lh7-us.googleusercontent.com/uZp95ENew0L5AnfG7qc2DdQ2uMp1fvMSpM5-PAahtyPhS5wT8jnlZHgNDdkDlQlVF2B9QYGJGZikKGZz8g2VYVbKwGGMZ9BwzDfIchjAk7ID3FtFsBabVX_a3kJ8oui2SW7IAxp3K6OcBe8b2g-96WQ](https://lh7-us.googleusercontent.com/uZp95ENew0L5AnfG7qc2DdQ2uMp1fvMSpM5-PAahtyPhS5wT8jnlZHgNDdkDlQlVF2B9QYGJGZikKGZz8g2VYVbKwGGMZ9BwzDfIchjAk7ID3FtFsBabVX_a3kJ8oui2SW7IAxp3K6OcBe8b2g-96WQ)

Inscriptions, based on BRC-20, explore the potential of Bitcoin UTXO, focusing on NFT assets. Naturally, asset protocols for fungible tokens (FT) will also become a new direction. At 8:09 on April 20, 2024, BTC successfully completed its fourth halving at block height 840000, reducing the mining reward for each block from 6.25 BTC to 3.125 BTC. At the same time, Bitcoin Runes were officially launched at block height 840000. Runes are an improvement on Inscriptions, allowing for more flexible and direct deployment of assets within Bitcoin UTXO, akin to an etching technique, as expressed by the Chinese term "Runes." The Runes protocol deploys token assets directly recorded information onto the Bitcoin chain: written into the OP-RETURN field of Bitcoin UTXO (Unspent Transaction Output).

The launch of Runes immediately drove a rapid increase in on-chain fees for Bitcoin. Since its launch at 8:09 on April 20, on-chain fees generated by Runes activities that day accounted for 70.1% of total Bitcoin on-chain fees, while previously, Bitcoin on-chain fees were primarily from traditional Bitcoin transfers. For block 840000, the fees generated were 37.626BTC, more than ten times the mining reward (3.125BTC)! This has been highly sought after by the market.

[https://lh7-us.googleusercontent.com/NoQexRFL4eAC8ZbD-7BoPolnBE8__DKDH_2uN1dDY8Odqxm2DOaV0v9fRjSenyBHut9ZryZj5jyhA-mYBqyz2rfEmJz6kvvR0Lo4R4iNFgm5a9XqoE2M2Xl5NdSU2EoxMkKYyHQQ0YeupDFyVTTueZk](https://lh7-us.googleusercontent.com/NoQexRFL4eAC8ZbD-7BoPolnBE8__DKDH_2uN1dDY8Odqxm2DOaV0v9fRjSenyBHut9ZryZj5jyhA-mYBqyz2rfEmJz6kvvR0Lo4R4iNFgm5a9XqoE2M2Xl5NdSU2EoxMkKYyHQQ0YeupDFyVTTueZk)

Runes have clearly made further improvements in design, issuance, and compatibility, preparing for compatibility with fungible tokens, interfacing with bridges, and DeFi applications.

## 3.2 The Evolution of UTXO: Nervos (CKB) Cell Model

Bitcoin does not use the familiar account model but instead employs UTXO (Unspent Transaction Output) to represent the flow of Bitcoin transactions. For example, if a user receives 100 BTC from someone else, this forms a 100 BTC UTXO, as if putting these 100 BTC into a box and locking it with a key that only the user's private key can unlock. In reality, these 100 BTC may be comprised of other locked UTXO boxes (for example, four 25 BTC UTXO boxes, or other combinations), meaning each operation results in an unspent output (UTXO); unlike the account model, which simply updates the state of the balance. However, Bitcoin UTXO can only store the "contained" value of its bitcoins and does not have the capability to store more data or have more scalability.

Nervos CKB inherits Bitcoin's UTXO architecture and has created the Cell Model—a generalized UTXO model for state storage that maintains UTXO’s simplicity and consistency.

In CKB, all states are stored in cells while computations are done off-chain, and nodes perform transaction verification to publish on-chain.

Unlike Bitcoin's UTXO, a Cell can contain various data types, such as CKBytes, tokens, JavaScript code, or JSON strings, which broadens the capabilities of Cells, thus extending the potential of UTXO—for instance, enabling smart contracts (even customized ones, such as issuing NFTs, limiting token supply, and setting conditions to meet unique needs).

Inspired by the Bitcoin UTXO model, the Cell model defines the behavior of each Cell within Nervos CKB and the process of updating the data it contains. Like Bitcoin UTXO, a Cell is immutable once formed: once Cells are added to the chain, no changes can be made. Updating the data within a Cell requires a process called "spending"—similar to how Bitcoin UTXO transfers are implemented by "spending." This involves using the updated data to create a new Cell, then adding it to the chain—similar to the formation of a new Bitcoin UTXO (for the spent output). Likewise, each Cell can only be spent once.

In summary, to make it easier to understand, a Cell is like a smarter UTXO. If Bitcoin UTXO is a box holding a paper ledger, then a Cell is like replacing the ledger in the box with an Excel spreadsheet.

[https://lh7-us.googleusercontent.com/3dfeflTzU9shyKO7Qp4bb6ngsSmMyu2kFad3z_cH6SVUYr9Dn-7ZSgX6uhE3PRkLs_BEwYYY6z_TI3_ofi_rBLyoO2zFXIst6Www7PshvRLhIAfgT1cyiddwKwheFd5QILMG0h4Iu4KyeLX-5y0vUFM](https://lh7-us.googleusercontent.com/3dfeflTzU9shyKO7Qp4bb6ngsSmMyu2kFad3z_cH6SVUYr9Dn-7ZSgX6uhE3PRkLs_BEwYYY6z_TI3_ofi_rBLyoO2zFXIst6Www7PshvRLhIAfgT1cyiddwKwheFd5QILMG0h4Iu4KyeLX-5y0vUFM)

[https://lh7-us.googleusercontent.com/JZESm2_yyznf5PHP-cKPMazRhu52hgAivBWO9QUuL2L9_uRWSM7KH__rvaf3nmy_rUFAl8EOayg-wj5J8TNr_crbcO9TRjpbqDlFLC-Z2XBZTjJeiLqp2gT99_gHGuRgbCz1eCHhocXPBGULEsFmHA4](https://lh7-us.googleusercontent.com/JZESm2_yyznf5PHP-cKPMazRhu52hgAivBWO9QUuL2L9_uRWSM7KH__rvaf3nmy_rUFAl8EOayg-wj5J8TNr_crbcO9TRjpbqDlFLC-Z2XBZTjJeiLqp2gT99_gHGuRgbCz1eCHhocXPBGULEsFmHA4)

It's important to note that the Cell model separates the computation and verification of smart contract execution. Computation occurs off-chain, generating new data, which is then verified on-chain by network nodes. In the Cell model, the execution of smart contracts is parallel, i.e., each transaction runs independently in its own virtual machine, with multiple virtual machines running simultaneously. Transactions in the Cell model are highly flexible and efficient, allowing multiple smart contract operations to be batched into a single transaction, thus minimizing transaction and processing fees.

[https://lh7-us.googleusercontent.com/8qJQdHEdS3b6evoc45ee4j8-0oxwfoXlMecjMGwD4BbazGycXXMqy6X_e61UuQ99NKYGZgpvXYixb8G0Zb92Tr4K2Zwc_PaMEw_dwf7aKKNgkV5-AIPH3iM0NxrhXFU9NZY5q1QdmvIKC_7hRNlEA_M](https://lh7-us.googleusercontent.com/8qJQdHEdS3b6evoc45ee4j8-0oxwfoXlMecjMGwD4BbazGycXXMqy6X_e61UuQ99NKYGZgpvXYixb8G0Zb92Tr4K2Zwc_PaMEw_dwf7aKKNgkV5-AIPH3iM0NxrhXFU9NZY5q1QdmvIKC_7hRNlEA_M)

Source:

[ckbdapps.com](http://ckbdapps.com/)

The aforementioned off-chain computation and on-chain consensus model is quite popular, such as the RGB protocol in BTC extension protocols, which involves off-chain computation and submits the consensus transaction results to the Bitcoin chain. This protocol is essentially similar to the Lightning Network. On this basis, the RGB++ protocol has been developed, utilizing one-time seals and client-side verification (CSV) technology to manage state changes and transaction verification. It isomorphically maps Bitcoin UTXOs to Nervos CKB's Cells, using the script constraints on the CKB chain and Bitcoin chain to verify the correctness of state computations and the validity of ownership changes—this benefits from seamlessly integrating UTXO's features between Bitcoin and Nervos CKB. RGB++ not only implements enhanced client-side validation, transaction folding, shared state across contracts, but also introduces Turing-complete smart contract scalability and performance extensions to Bitcoin without the need for cross-chain transactions and without compromising security.

## 3.3 Will the Uniqueness of UTXO Foster a Unique Bitcoin Ecosystem?

There was a time when Bitcoin's UTXO and Ethereum's ERC20 seemed to have a classical vs. modern difference. UTXO is both the root of Bitcoin's security and reliability (anti-double spending, traceability, etc.) and, due to scalability issues, limits the development of the Bitcoin ecosystem, which is still unable to reach the rich ecosystem scenarios of Ethereum's DeFi, NFT, and metaverse.

But if we think about it the other way, could the uniqueness of UTXO also foster a different ecosystem? The deep exploration of Bitcoin's UTXO by Ordinals and Runes has made asset deployment based on UTXO possible, and the upgrade of UTXO by Nervos CKB has further liberated computational power. These developments hint at UTXO's unique application potential, which also seems more interesting and has become a new expectation in the industry.

Looking at the development of Ethereum, from the ERC20 standard that led to ICOs to the development of AMMs that energized DeFi, and the emergence of NFTs and the metaverse, its ecosystem paradigm has gradually become richer. However, this process was not achieved overnight; it was fraught with twists and turns.

Bitcoin's recent innovations have initially received significant market attention, a good sign indicating strong market confidence and expectation for the potential of UTXO. However, as the hype comes quickly, it cools down swiftly too. After the emergence of Runes, the enthusiasm for Ordinals naturally declined. Currently, both Ordinals and Runes are still in the stage of competing for "mints." Minting is just the beginning; the more important tasks are how to develop applications and enrich the ecosystem moving forward. The situation with Nervos CKB is similar, as its current ecosystem applications can be seen as a simple "copy" of Ethereum's ecosystem.

[https://lh7-us.googleusercontent.com/0kZzrV_yQX76ClYjhLtrmZ2CVFikPxCENdZOywvkAMAiaO3-IT7U4uSJc4xmikjIyuQE_YlIQCu6CAX7-Wy25Z4w6os825I8IB3TQS_h4CqaNuW9S2-_3WoWp7F0-VwsjGaP41UPjITyCLsyfGArPSg](https://lh7-us.googleusercontent.com/0kZzrV_yQX76ClYjhLtrmZ2CVFikPxCENdZOywvkAMAiaO3-IT7U4uSJc4xmikjIyuQE_YlIQCu6CAX7-Wy25Z4w6os825I8IB3TQS_h4CqaNuW9S2-_3WoWp7F0-VwsjGaP41UPjITyCLsyfGArPSg)

[https://lh7-us.googleusercontent.com/TXCzeEFUhWEiKc9LJWPCTQyiUbeBVqtf30OYot541GJzaV9KbnznzgfaFpZUWUmItanGKyPiPgb9zyoC5usRXHFWsMC9bLv8W76DDxj52S-xInznTYsOVwUQtZGqIBT5ej43cdLfsu_CIAjPavPYqEg](https://lh7-us.googleusercontent.com/TXCzeEFUhWEiKc9LJWPCTQyiUbeBVqtf30OYot541GJzaV9KbnznzgfaFpZUWUmItanGKyPiPgb9zyoC5usRXHFWsMC9bLv8W76DDxj52S-xInznTYsOVwUQtZGqIBT5ej43cdLfsu_CIAjPavPYqEg)

We believe that the characteristics of UTXO have the potential to inspire a different ecosystem paradigm, and we look forward to the early emergence of such a "stunning" paradigm soon.

# Risk Warning

The development of blockchain technology and related projects are still in the early stages, with risks of not meeting expectations.

The actual operation of blockchain and Web3 projects involves various financial, network, and other regulatory policies. Currently, regulatory policies in various countries are still in the research and exploration stage without a mature regulatory model, posing risks of regulatory uncertainty.

Web3 infrastructure and projects are in their early stages, with risks that business models may not be realized as expected.

**Returning to Our Roots: CKB Shifts to Bitcoin Layer2 Track - Speculation or Opportunity?**

CKB has consistently maintained its foundational principles, striving to align with Bitcoin's structure while also addressing its limitations.

As ETFs gain traction, the BRC-20 ecosystem burgeons, and the narrative around Bitcoin's halving gains momentum, the market's focus seems to be shifting back to the Bitcoin ecosystem. In this context, CKB, a veteran in the public blockchain space, has been making significant strides. Following its announcement to reposition its mainnet as Bitcoin Layer2, it introduced the first-layer asset protocol RGB++. By capitalizing on the growth of Bitcoin Layer2 and combining it with its native UTXO + PoW 'BUFF', CKB has rapidly become a focal point in community discussions.

Yet, before we explore the RGB++ concept, understand why the CKB team opted for the RGB protocol, and examine their strategy for Bitcoin Layer2 development, it's essential to revisit CKB's history, background, and original vision for a more comprehensive understanding.

**Genesis Journey**

In the early months of 2018, when the Ethereum ecosystem was the center of market attention, CKB embarked on its journey. By July of that year, CKB had successfully raised $28 million, with notable investment from leading institutions like Polychain Capital, Sequoia China, Wanxiang Blockchain, and Blockchain Capital. Following this, on October 24, 2019, CKB exceeded expectations by raising $67.2 million through Coinlist. Then, on November 16, 2019, CKB's mainnet, named 'Lina', was officially launched.

The team behind CKB boasts a stellar lineup, consisting of founders who have spent years deeply immersed in the cryptocurrency sector. Olaf Carlson-Wee, the founder of Polychain Capital, has mentioned in interviews his strong confidence in the CKB team's background and expertise.

Chief Architect Jan Xie: Jan has been a key contributor to Ethereum clients Ruby-ethereum and pyethereum for an extensive period. He also collaborated with Ethereum co-founder Vitalik Buterin on developing the Casper consensus algorithm and sharding technology. Beyond this, Jan founded Cryptape, a company dedicated to the development of foundational blockchain platforms and research in consensus algorithms.

Co-founder Kevin Wang: Kevin's background includes working on enterprise data solutions at IBM's Silicon Valley lab. He co-founded Launch School, an online educational platform for software engineers. In addition, he played a pivotal role in creating Khalani, an innovative, intent-driven central solver infrastructure. Khalani stands out as a multifunctional 'collective solver,' adept at seamlessly integrating into a variety of intent-based applications and ecosystems.

Co-founder and COO Daniel Lv: Daniel co-founded the Ethereum wallet imToken and previously served as the CTO of the cryptocurrency exchange Yunbi. His contributions extend to organizing the Ruby community in China for over a decade and co-founding [ruby-china.org](http://ruby-china.org/), a notable online community platform.

CEO Terry Tai: Terry has a strong background as a core developer at the cryptocurrency exchange Yunbi. He is also recognized as a co-founder of the technology-focused podcast [Teahour.fm](http://teahour.fm/), contributing to broader discussions in the tech community.

It's quite intriguing that, despite the CKB founding team's strong connections with the Ethereum community, they opted for the Bitcoin UTXO + PoW model in developing their Layer1 architecture. This choice was driven by an acknowledgment of Ethereum's infrastructural limitations. The team realized that Ethereum's framework imposed constraints on thorough systemic reforms, making fundamental restructuring and bold innovation unattainable. As a result, the CKB team decided to diverge from Ethereum's path, endeavoring to create an entirely new blockchain.

Moreover, the motivation behind the CKB team's decision to develop a new public chain may also be gleaned from the name 'Nervos.' Derived from 'Nerve,' it echoes Charles Darwin's evolutionary theory that 'only species that adapt and flexibly adjust to changing environments can survive.' This concept suggests the idea of enabling the network to autonomously adapt and evolve at its core. Another interesting note on the name 'Nervos' relates to the co-founders' interest in eSports and anime. In the anime 'Neon Genesis Evangelion,' 'NERV' is the acronym for the 'United Nations Special Agency,' which might have also influenced their choice of name.

In order to accelerate the progress of its ecosystem, CKB began to focus on developing tools from the beginning of 2020. A series of tools were subsequently introduced, including the JavaScript/TypeScript-based framework Lumos, the Ethereum-compatible layer Polyjuice that allows the use of the account model on CKB, the cross-chain bridge Force Bridge that connects Ethereum and CKB, and the dApp development kit Tippy, among others. These tools significantly lower the barriers to developing applications. Leveraging these tools, the CKB ecosystem has launched 127 projects, encompassing various fields like DID, wallets, and inscriptions.

**Charting a Unique Course: The Innovative Aspects of CKB's Architecture**

In a context where the wider community is primarily focused on TPS (Transactions Per Second) and PoS (Proof of Stake), CKB has embarked on a distinctly different technological journey. They hold a strong conviction against making compromises on censorship resistance and the principle of operating without permissions. To uphold these values, they consciously chose to scale back L1 performance to preserve a high degree of decentralization. They've also implemented an advanced PoW (Proof of Work) algorithm and streamlined hash functions to ensure both the security and the permissionless nature of the network.

**The Concept of Layering**

The rationale behind adopting a layered architecture stems from the team's contemplation on the operational paradigm of the internet. The internet, with its layered and modular architecture, has established a relatively stable network of trust. However, its level of trustworthiness is somewhat limited, lacking intrinsic support for self-sustaining protocols. CKB envisions a cryptographic economic network infrastructure that also employs a layered and modular framework. This approach entails defining the network through an ensemble of protocols, rather than a singular protocol, and inherently supporting self-sustaining protocols. Consequently, the team committed to constructing a secure, scalable network composed of multiple layers. In this structure, Layer1 is devoted to ensuring security and decentralization, while Layer2, building upon the security foundations of Layer1, aims to achieve boundless scalability.

As for Layer1, CKB stands for 'Common Knowledge Base.' 'Common Knowledge' is understood as information universally acknowledged and recognized, known by nearly everyone and also known to be known by others. Within the blockchain sphere, 'Common Knowledge' signifies the states validated by global consensus and accepted by the entire network. This characteristic enables the consideration of cryptocurrencies stored on public blockchains as legitimate currency. Nervos CKB is designed to house all varieties of common knowledge, extending beyond just monetary assets. It includes, for instance, the storage of bespoke crypto assets like fungible tokens (FTs) and non-fungible tokens (NFTs).

The Layer 2 protocols can exploit CKB’s assurance of security to attain unlimited scalability. Ethereum, too, has acknowledged CKB’s layered architecture concept. Since 2019, Ethereum shifted its focus from its prior execution sharding research to prioritize expansion around Layer 2 solutions, a strategy that persists.

**PoW Mechanism: Ensures Decentralization**

CKB holds a strong conviction that Layer1 is the foundational layer of the cryptographic economy and, therefore, it must operate as a permissionless network. Contrarily, PoS (Proof of Stake) allocates block production based on the amount staked, which can conflict with the objectives of decentralization and neutrality. In contrast, PoW (Proof of Work) is entirely permissionless, enabling users to engage in block production simply by investing in mining equipment and electricity. Furthermore, the security aspect of PoW is notably robust. Falsifying or reconstructing a PoW blockchain is an immensely challenging task, as it necessitates recalculating the computational efforts for each block. Vitalik Buterin has contributed to this discussion with his 'weak subjectivity' concept, suggesting that PoS’s security is comparable to that of PoW.

Hence, the CKB team posits that while PoS does have performance benefits over PoW, PoW is the preferable choice when striving for maximal decentralization and security in Layer1.

**Cell Model: Achieving Scalability**

As the Bitcoin ecosystem has flourished, the debate between the account and UTXO (Unspent Transaction Output) models has resurfaced. Initially, both models were interpreted primarily in terms of asset management. However, over time, the UTXO model has continued to treat assets as its core focus (operating on a peer-to-peer basis), while the account model has evolved to facilitate contract services, with users’ assets managed within and interacting with smart contracts. This evolution has resulted in assets issued on UTXO chains being more secure than ERC-20 assets on Ethereum. In addition to enhanced security, the UTXO model boasts superior privacy features, as it changes addresses with each transaction and inherently supports parallel transaction processing. Most crucially, unlike the account model’s simultaneous on-chain computation and verification, the UTXO model relocates the computation process off-chain, requiring only on-chain verification. This simplification in application development obviates the need for on-chain optimization considerations.

CKB extends beyond adopting Bitcoin’s architectural philosophy by abstracting the UTXO model into the innovative Cell model. While maintaining Bitcoin’s consistency and simplicity, it incorporates the capability to support smart contracts. In particular, the Cell model abstracts the UTXO’s nValue field, which traditionally represents token value, into two components: capacity and data. The data field is designed to store state information, capable of housing any data type. Additionally, the Cell data structure encompasses LockScript and TypeScript fields, where LockScript mainly denotes ownership, and TypeScript can be tailored for a variety of complex functionalities.

In essence, the Cell model represents an advanced, more adaptable form of UTXO, equipping CKB with smart contract capabilities akin to those found in Ethereum. However, distinct from other smart contracts, CKB adopts an economic model focused on storing common knowledge, rather than one tailored for payment processing in decentralized computing.

**Advanced Concept of Abstraction**

In the crypto world, 'abstraction' is a familiar concept. It involves stripping away the specificities of a system to create a level of generality, thereby making the system more versatile and applicable to a broader range of scenarios. The progression from Bitcoin to Ethereum can be seen as a journey towards greater abstraction. Bitcoin’s limited programmability restricts its application development capabilities. Ethereum, conversely, introduced a virtual machine and an execution environment, paving the way for the creation of diverse applications. Ethereum’s development journey has been marked by continuous abstraction, whether it's the 'account abstraction' often discussed by Vitalik or the 'cryptographic abstraction' that comes with the addition of precompiled contracts.

In a similar vein, CKB can be viewed as an abstraction of Ethereum to a certain degree, providing smart contract developers with a wider scope for innovation and flexibility.

**1) Account Abstraction**

CKB realizes account abstraction through its Cell model. A prime example is the Nervos ecosystem wallet, UniPass, which has developed an identity authentication system based on email and phone numbers. This system allows users to log in with their email and password, much like traditional internet accounts, offering a familiar user experience. The decentralized identity service, [d.id](http://d.id/), also leveraged this feature in their development of the decentralized domain protocol .bit. This protocol takes advantage of Nervos' abstract account characteristics, enabling not only CKB users but also internet users, Ethereum users, and EOS users to seamlessly interact with applications.

**2) Cryptographic Abstraction**

At the heart of cryptographic abstraction is the use of an efficient virtual machine. CKB utilizes the CKB-VM, which leverages the features of the RISC-V instruction set. This enables developers to implement cryptographic algorithms in various programming languages, including C and Rust. An example of this in action is the JoyID wallet, developed on CKB. JoyID maximizes the benefits of Nervos CKB's customizable cryptography, facilitating wallet creation and transaction verification using biometric technologies like fingerprints, thereby eliminating the need for traditional passwords or mnemonic phrases.

**3) Execution Abstraction**

CKB's ambition is to establish a higher level of abstraction, aimed at boosting performance and increasing transaction throughput. With a higher abstraction level, the Nervos network can offload more tasks to off-chain environments or Layer 2 solutions. To illustrate, consider the XBOX, which, despite being an abstract, general-purpose platform, has some limitations, such as fixed hardware. In contrast, a PC system allows users to upgrade or change components like graphics cards, CPUs, memory, and hard drives, demonstrating a more advanced level of abstraction. CKB’s objective is akin to evolving from an XBOX-like framework to a more PC-like one, thereby accommodating a wider array of requirements and providing developers with increased flexibility and capabilities.

**Analysis of CKB’s Economic Model: Mining Rewards and Inflationary Mechanism**

CKB’s native token, referred to as CKB (Common Knowledge Byte), signifies the holder's entitlement to a segment of the blockchain's global state space. To illustrate, owning 1000 CKB tokens allows you to create a Cell encompassing 1000 Bytes of space. This space can be utilized to store various types of data, including assets, application states, or other data forms.

CKB's economic model is distinctively designed. Similar to Bitcoin, it features a mining reward halving every four years. However, it also integrates an inflation mechanism, commonly seen in mainstream PoS (Proof of Stake) currencies, with an annual increase of 1.344 billion tokens. Current data from CKBDAPPS reveals that the total issued CKB tokens amount to 44.379 billion, out of which 43.69 billion are in circulation. The detailed structure of this model is as follows:

**1) Genesis Issuance:**

The genesis block of CKB saw the release of 33.6 billion tokens. In a tribute to Satoshi Nakamoto, 8.4 billion CKB were immediately allocated to Nakamoto's address. The remaining 25.2 billion CKB were allocated to institutional investors, ecological funds, development teams, and public investors, all of which have now been fully unlocked.

**2) Primary Issuance:**

The total amount set for primary issuance is 33.6 billion tokens. Echoing Bitcoin's model, the issuance undergoes a halving every four years until the entirety of the primary issuance is mined. CKB underwent its inaugural halving in November 2023, reducing the annual issuance rate to 2.1 billion CKB. The next halving is projected for November 2027, which will further decrease the annual issuance to 1.05 billion CKB. All tokens generated from this primary issuance are designated as rewards for miners.

Regarding the specific distribution of tokens:

- 21.5% were allocated for public token sales and were fully unlocked at the time of the mainnet launch.
- 17% were designated for the ecosystem fund. At the mainnet launch, 3% of these were unlocked, with the remaining set to unlock over a period of three years.
- 15% were assigned to the Nervos team, subject to a four-year vesting schedule, with one-third becoming available at the mainnet launch.
- 14% were earmarked for a private sale held in 2018, subjected to a two-year lock-up period.
- 5% were reserved for the founding partners, locked for three years, and are not intended for circulation on the mainnet.
- 2% were set aside as reserve funds for the foundation, which were unlocked in July 2020 and are not to be circulated on the mainnet.
- 0.5% were allocated for testnet incentives, distributed to participants through mining competitions and a bug bounty program.
- The remaining 25% of the tokens have been destroyed.

3) Secondary Issuance

To safeguard miners' revenue from the impacts of halving events and fluctuations in on-chain transaction volumes, CKB has implemented the concept of 'Secondary Issuance.' This involves a fixed annual release of 1.344 billion CKB tokens. The distribution of these tokens is determined by their usage within the network:

- For Miners: Allocated in proportion to their share of state usage on the blockchain.
- For NervosDAO: Proportionate to the ratio of CKB locked in NervosDAO compared to the total token issuance.
- For the Treasury: Correlated with the proportion of CKB in circulation relative to the total issuance. Currently, as the governance mechanism is still in development, this portion of tokens is directly destroyed.

This secondary issuance functions akin to an 'inflation tax.' Essentially, if users need to store data or states on the CKB network, they are required to pay a certain amount of CKB as 'state rent' to the miners. Should they decide to cease storage, they can unlock their CKB and deposit it into NervosDAO. Holders who have no storage requirements can also deposit their CKB in NervosDAO to receive subsidies, thereby mitigating the dilutive effect of secondary issuance on the token's value.

As per data from the [CKB Explorer](https://explorer.nervos.org/nervosdao), out of the secondary issuance tokens, 11.4% are allocated for mining rewards, 19.1% for lock-up subsidies, and 69.5% are distributed to the treasury fund and subsequently destroyed.

**Network Hash Power**

CKB mining operations commenced on May 18, 2019, with the adoption of the Eaglesong hash algorithm. Post March 2020, the mining landscape has progressively shifted from utilizing CPUs, GPUs, and FPGAs to predominantly ASIC-based mining rigs. Currently, ASIC miners such as the Antminer K7 and Goldshell CK6 are predominant in the CKB mining sector (due to the lower profitability, GPU and FPGA mining rigs are less viable for CKB mining).

As of now, the network's mining hash power is recorded at 240.06 PH/s, and the mining difficulty level is at 2.31 EH. Notable mining pools that support CKB include F2Pool, Poolin, 2miners, among others.

**Ongoing Debates: Perspectives on Bitcoin Layer2's New Directions**

On February 13th, CKB co-founder Cipher unveiled the RGB expansion protocol, RGB++. This development has somewhat impacted CKB’s secondary market price and ignited debates over the authenticity of Bitcoin Layer2 solutions. Some in the community argue that RGB++, in contrast to EVM-compatible approaches, maintains the orthodoxy of Bitcoin’s UTXO model. They point out the team's deep engagement with the Bitcoin ecosystem — be it the layered architecture, UTXO abstraction, or the recent OTX protocol CoBuild Open Transaction — as true extensions and innovations of Bitcoin’s foundational principles. On the other hand, there are voices that critique CKB’s diverse focus. From the 2019-2020 collaboration with Huobi to the gaming initiatives between 2020 and 2022, neither direction resulted in significant progress, leading to suspicions that this shift towards Layer2 might be speculative. Furthermore, some core Bitcoin developers have disputed the connotation of the RGB++ name, suggesting it implies a superiority over the original RGB. CKB has released a roadmap for RGB++, and its future effectiveness and impact might only be truly determined over time.

Since the start of 2024, the competition among Bitcoin Layer2 solutions has been heating up. Despite the varied approaches, each contributes in its way to the sustainable growth and practical application of the Bitcoin ecosystem. Such competition could inspire a wealth of creative ideas and solutions. In this evolving landscape, CKB appears to remain steadfast in its original vision, continuously aligning with Bitcoin’s structure and striving to fill its gaps.

# **Bitcoin Renaissance: Why and How?**

*How to advance Bitcoin into what the market clearly wants it to be—without compromising on any of its cherished ideals.*

*By [Jan Xie](https://twitter.com/busyforking)*

[https://lh7-us.googleusercontent.com/docsz/AD_4nXfB5bXDJZNMuJshIdDLH5p6FPjFKM64wrnJoIDAfO0mdYJSBI2K9Fu3C-tNH1fXs3QuSCd4tqtRnngSuMBFyBZfoDEkqYO6ZqV1KmBxKb1bxG1hb3IW8bFbfMttQJMD3zjUx_DD2sQTSjb6rL6kxXTRJD5U?key=vCpLIl0QVfZIq9275BtXSg](https://lh7-us.googleusercontent.com/docsz/AD_4nXfB5bXDJZNMuJshIdDLH5p6FPjFKM64wrnJoIDAfO0mdYJSBI2K9Fu3C-tNH1fXs3QuSCd4tqtRnngSuMBFyBZfoDEkqYO6ZqV1KmBxKb1bxG1hb3IW8bFbfMttQJMD3zjUx_DD2sQTSjb6rL6kxXTRJD5U?key=vCpLIl0QVfZIq9275BtXSg)

While Bitcoin has achieved a formidable status as a store of value, the rise of Ordinals and inscriptions clearly demonstrated users want to use it for more than just that. Beyond simply holding, there’s a massive and rising demand for Bitcoin-based applications, fungible and non-fungible assets, and scalable payments. However, the question is: How does Bitcoin satisfy this desire while preserving the core principles it was based on?

## The Risks of Inaction

There has been great progress made gradually in the Bitcoin ecosystem, but the inability to innovate quickly has led to a concerning trend: a significant amount of BTC is continually being siphoned away from its ecosystem. Despite Lightning Network’s relative success, Ethereum now hosts more BTC than all Bitcoin Layer 2s combined. Even worse, an increasing number of BTC are held on centralized exchanges, which reintroduces the same custody risks from the fiat system that Bitcoin was originally built to mitigate.

This is a clear signal that if we, the Bitcoin community, don't offer compelling solutions, others will step in with solutions that may not align with Bitcoin's core values of decentralization and security. If we don’t act, we risk losing control over the direction in which Bitcoin and the broader crypto industry evolve.

To that point, Ethereum’s history provides a cautionary tale. As early as 2016, Bitcoin developers Peter Todd and Greg Maxwell highlighted numerous architectural issues with its design. However, the Bitcoin ecosystem’s progress over the past eight years has been relatively slow, while the broader industry has pursued questionable new solutions like Proof-of-Stake, account-based models, and sharding—all of which can undermine the decentralization and security that Bitcoin stands for.

We can no longer afford to make the same mistakes. The demand for new Bitcoin-based assets and use cases presents a pivotal opportunity. It calls for a Bitcoin Renaissance. Let's seize this moment to redirect the crypto industry towards a path that adheres to Bitcoin's values, principles, and architecture.

## The State of Play

At its core, Bitcoin was envisioned as a peer-to-peer electronic cash system, not a peer-to-contract system like most smart contract platforms, or a peer-to-sequencer system like current rollups.

Bitcoin’s brilliance lies in the Proof-of-Work consensus mechanism and the UTXO model, which offers numerous advantages over the now prevalent account-based model. Instead of recording balances, UTXOs track individual currency units, similar to how physical cash works. This enables the creation of genuine bearer assets—assets owned by whoever holds the private key.

Most importantly, Bitcoin’s emphasis is on verification, not computation, which is what blockchains excel at. Computation and complex verification should be pushed off-chain—into protocols that don’t necessarily need to be blockchains. Luckily, the Bitcoin community has proposed many novel ideas for how to do this. Peter Todd’s work on [single-use seals](https://petertodd.org/2016/commitments-and-single-use-seals) is especially notable here, as it paves the way for innovative scaling solutions based on client-side validation, including colored coins, RGB, Ordinals, and Atomicals.

The community has also explored and built various Layer 2 solutions with different consensus mechanisms, bridging solutions, and security assumptions. However, despite the richness of the ideas, the ecosystem growth over the years has been slow. This is primarily due to two reasons: Bitcoin’s lack of programmability, and its conservative ethos. It’s (intentionally) very difficult to reach a social consensus on any protocol-level changes to Bitcoin, which is also why we’re having these conversations today.

## Ushering in The Bitcoin Renaissance

If we ought to usher in a Bitcoin renaissance, we should have the following in mind: Our solutions must satisfy user’s needs without sacrificing Bitcoin’s values and without requiring soft or hard forks.

Luckily, this is all possible by leveraging the layered approach. We already have some asset issuance protocols, including Ordinals, Runes, BRC-20, and Taproot Assets on the base chain. These directly benefit and simultaneously contribute to Bitcoin’s unmatched security. However, Bitcoin’s limited programmability means that users can’t do much with these assets beyond simply holding them, which is why we need a fully-expressive programmable layer on top. This layer should serve as the financial hub for assets on the Bitcoin chain.

Then, we need a secure bridge between these two layers. We can use a typical two-way peg, but Cipher Wang’s (author of the [RGB++](https://talk.nervos.org/t/rgb-protocol-light-paper-translation/7790) protocol) new innovative solution, Universal Isomorphic Binding (UIB), is better. It employs point-to-point mapping between the UTXOs of two chains, eliminating the need for third-trusted parties, which is a giant leap compared to current bridging solutions.

Once we’ve established the programmable layer and the bridge, we can build another scalability and privacy-focused layer on top. Solutions for this include client-side-validation-based protocols, Open (partially-signed) Transactions, Nostr, Chaumian e-cash, and peer-to-peer markets. Then, we can use channels to connect all of this, and even connect Web2 and Web3—birthing the new Bitcoin-based Web5 paradigm.

Web5 means using cryptography, peer-to-peer technology, and other Web3-native solutions to fix and incorporate into Web2. It’s an entirely different paradigm than the one we’re operating in today—and there’s no better platform to build it on than Bitcoin.

Author’s bio:

Jan Xie, Chief Architect of [Nervos](http://nervos.org/), founder of [Cryptape](http://cryptape.com/).

- This article is based on Jan Xie’s talk at

[*Bitcoin Singapore*](https://btc-singapore.com/)

*on March 9th, 2024.*

[*Click*](https://docs.google.com/presentation/u/1/d/1xGSQ2L_jNMMYtdzixQg8D1VElfB3lIoEikFPhiLlcLw/edit)

*for slides.*