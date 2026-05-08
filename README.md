# Blockchain Papers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of blockchain-related academic papers. Papers with 🎓 have been
peer-reviewed and presented in academic conferences.

## Table of Contents
1. [General](#general)
1. [Consensus](#consensus)
1. [Cryptography](#cryptography)
1. [Block generation and mining](#block-generation-parameters)
1. [Stake](#stake)
1. [Attacks](#attacks)
1. [Wallets](#wallets)
1. [Crime](#crime)
1. [Economics](#economics)
1. [Marketplaces and Trust](#marketplaces-and-trust)
1. [Privacy](#privacy)
1. [Sidechains, Higher layer and Scalability](#sidechains-higher-layer-and-scalability)
1. [Payment Networks](#payment-networks)
1. [Fungibility](#fungibility)
1. [Network](#network)
1. [Smart Contracts](#smart-contracts)
1. [Formal Methods](#formal-methods)
1. [Proof of work](#proof-of-work)
1. [DAG-based consensus mechanisms](#dag-based-consensus)
1. [Survey, Sociological & Anthropological](#survey-sociological--anthropological)
1. [Applications](#applications)
1. [License](#license)

---

## General

- **[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.com/bitcoin.pdf)**. Nakamoto S. '08.
- 🎓 **[SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf)**. Bonneau J, Miller A, Clark J, Narayanan A, Kroll JA, Felten EW. S&P '15.
- [Bitcoin's Academic Pedigree](http://delivery.acm.org/10.1145/3140000/3132259/p36-narayanan.pdf?ip=88.197.32.177&id=3132259&acc=OPEN&key=5641A0C343C36AC1%2E4ABAF8470B13FB25%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1541082825_ead879dbf5b3644bfed2a09e11b47834). Narayanan A, Clark J. ACM Queue '17.
- 🎓[A systematic literature review of blockchain-based applications: Current status, classification and open issues](https://www.researchgate.net/profile/Thomas_Dasaklis/publication/329136952_A_systematic_literature_review_of_blockchain-based_applications_Current_status_classification_and_open_issues/links/5c4cab1ba6fdccd6b5cb7ea1/A-systematic-literature-review-of-blockchain-based-applications-Current-status-classification-and-open-issues.pdf). Casino F, Dasaklis T, Patsakis C. T&I '18.

## Consensus

- 🎓 **[The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf)**. Garay J, Kiayias A, Leonardos N. EUROCRYPT '15.
- 🎓 [The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048.pdf). Garay J. Kiayias A, Leonardos N. '16. CRYPTO '17.
- 🎓 [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf). Pass R, Seeman L, shelat a. EUROCRYPT '17.
- [On Trees, Chains and Fast Transactions in the Blockchain](https://eprint.iacr.org/2016/545.pdf). Kiayias A, Panagiotakos G. '16.
- 🎓 "RSCoin": [Centrally banked cryptocurrencies](https://arxiv.org/pdf/1505.06895.pdf). Danezis G, Meiklejohn S. '15.
- [Anonymous Byzantine Consensus from Moderately-Hard Puzzles: A Model for Bitcoin](https://socrates1024.s3.amazonaws.com/consensus.pdf). Miller A, LaViola JJ Jr. '14.

### Classic Consensus

- 🎓 [The Byzantine Generals Problem](https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf). Lamport L, Shostak R., Pease M. '82. TOPLAS '82.
- 🎓 [Consensus in the Presence of Partial Synchrony](https://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf). Dwork S., Lynch N. '88. JACM '88.
- 🎓 [Practical Byzantine Fault Tolerance](http://pmg.csail.mit.edu/papers/osdi99.pdf). Castro M., Liskov B. '99. OSDI '99.
- 🎓 [The part-time parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf). Lamport L. '00. TOCS '98.


## Cryptography

- [On Bitcoin as a public randomness source](https://pdfs.semanticscholar.org/ebae/9c7d91ea8b6a987642040a2142cc5ea67f7d.pdf). Bonneau J, Clark J, Goldfeder S. '15.
- [Distributed Cryptography Based on the Proofs of Work](https://eprint.iacr.org/2014/796.pdf). Andrychowicz M, and Dziembowski S. '14.
- [Scalable, transparent, and post-quantum secure computational integrity](https://eprint.iacr.org/2018/046.pdf). Ben-Sasson E, Bentov I, Horesh Y, Riabzev M. '18.
- 🎓 [Bitcoin as a Transaction Ledger: A Composable Treatment](https://eprint.iacr.org/2017/149.pdf). Badertscher C., Maurer U., Tschudi D., Zikas V. '19. CRYPTO '17.

## Block generation and mining

- 🎓 [Bootstrapping the Blockchain - Directly](https://eprint.iacr.org/2016/991.pdf). Garay JA, Kiayias A, Leonardos N, Panagiotakos G. '16.
- [Speed-Security Tradeoffs in Blockchain Protocols](https://pdfs.semanticscholar.org/7de8/ff6bb85a020aa96f62dd86233fe9416550f3.pdf). Kiayias A, Panagiotakos G. '15.
- 🎓 "GHOST": [Secure High-Rate Transaction Processing in Bitcoin](https://fc15.ifca.ai/preproceedings/paper_30.pdf). Sompolinsky Y, Zohar A. FC '15.
- 🎓 [Inclusive Block Chain Protocols](http://fc15.ifca.ai/preproceedings/paper_101.pdf). Lewenberg Y, Sompolinsky Y, Zohar A. FC '15.
- 🎓 [On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Wüst K, Glykantzis V, Ritzdorf H, Capkun S. CCS '16.
- 🎓 [Smartpool: Practical decentralized pooled mining](https://eprint.iacr.org/2017/019.pdf). Luu L, Velner Y, Teutsch J, Saxena P. USENIX Security '17.

## Stake
- 🎓 [Ouroboros: A provably secure proof-of-stake blockchain protocol](https://pdfs.semanticscholar.org/1c14/549f7ba7d6a000d79a7d12255eb11113e6fa.pdf). Kiayias A, Russell A, David B, Oliynykov R. '16.
- 🎓 [ALGORAND: The Efficient and Democratic Ledger](https://arxiv.org/pdf/1607.01341.pdf). Micali S. '16.
- 🎓 "ByzCoin": [Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf). Kogias EK, Jovanovic P, Gailly N, Khoffi I, Gasser L, Ford B. USENIX '16.
- 🎓 [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC '16.
- 🎓 [Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake protocol](http://eprint.iacr.org/2017/573.pdf). Bernardo D, Gazi P, Kiayias A, Russell A. Crypto '17.
- 🎓 [Ouroboros Genesis: Composable Proof-of-Stake Blockchains with Dynamic Availability](https://eprint.iacr.org/2018/378.pdf). Badertscher C, Gazi P, Kiayias A, Russell A, Zikas V. '18.
- 🎓 [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC '17.
- 🎓 [Snow White: Provably Secure Proofs of Stake.](https://fc19.ifca.ai/preproceedings/141-preproceedings.pdf). Bentov I, Pass R, Shi E. FC '19.

## Attacks

- 🎓 **"Selfish Mining": [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243)**. Eyal I, Sirer EG. FC '14.
- **[Theoretical Bitcoin Attacks with less than Half of the Computational Power](https://arxiv.org/pdf/1312.7013.pdf)**. Bahack L. '13.
- 🎓 [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC '16.
- 🎓 [Refund attacks on Bitcoin’s Payment Protocol](http://fc16.ifca.ai/preproceedings/34_McCorry.pdf). McCorry P, Shahandashti S, Hao F. FC '16.
- [Low-Resource Eclipse Attacks on Ethereum’s Peer-to-Peer Network](https://eprint.iacr.org/2018/236.pdf). Marcus Y, Heilman E, Goldberg S. '18.
- 🎓 [Hostile blockchain takeovers](https://fc18.ifca.ai/bitcoin/papers/bitcoin18-final17.pdf). Bonneau J. FC '18.

## Wallets

- 🎓 [Bitcoin Covenants](http://fc16.ifca.ai/bitcoin/papers/MES16.pdf). Möser M, Eyal I, Sirer EG. FC '16.
- 🎓 [Enhancing Bitcoin Transactions with Covenants](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final28.pdf). O’Connor R, Piekarska M. FC '17.
- 🎓 [Hierarchical deterministic Bitcoin wallets that tolerate key leakage](http://fc15.ifca.ai/preproceedings/paper_15.pdf). Gutoski G, Stebila D. FC '15.

## Crime

- 🎓 [ZombieCoin: Powering Next-Generation Botnets with Bitcoin](http://fc15.ifca.ai/preproceedings/bitcoin/paper_15.pdf). Ali ST, McCorry P, Lee PH, Hao F. FC '15.
- 🎓 [The Bitcoin Brain Drain: A Short Paper on the Use and Abuse of Bitcoin Brain Wallets](http://fc16.ifca.ai/preproceedings/36_Vasek.pdf). Vasek M, Bonneau J, Castellucci R, Keith C, Moore T. FC '16.

## Economics

- 🎓 **[On Bitcoin and Red Balloons](https://arxiv.org/pdf/1111.2626.pdf)**. Babaioff M, Dobzinski S, Oren S, Zohar A. EC '12.
- 🎓 **[On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf)**. Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS '16.
- 🎓 [The Economics of Bitcoin Mining or Bitcoin in the Presence of Adversaries](https://www.econinfosec.org/archive/weis2013/papers/KrollDaveyFeltenWEIS2013.pdf). Kroll J, Davey I, Felten E. WEIS '13.
- 🎓 [Trends, Tips, Tolls: A Longitudinal Study of Bitcoin Transaction Fees](http://fc15.ifca.ai/preproceedings/bitcoin/paper_8.pdf). Möser M, Böhme R. FC '15.
- 🎓 [Why buy when you can rent? Bribery attacks on Bitcoin-style consensus](http://fc16.ifca.ai/bitcoin/papers/Bon16b.pdf). Bonneau J. FC '16.
- 🎓 [Game-Theoretic Analysis of DDoS Attacks Against Bitcoin Mining Pools](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_16.pdf). Johnson B, Laszka A, Grossklags J, Vasek M, Moore T. FC '14.
- 🎓 [When Bitcoin Mining Pools Run Dry A Game-Theoretic Analysis of the Long-Term Impact of Attacks Between Mining Pools](http://fc15.ifca.ai/preproceedings/bitcoin/paper_13.pdf). Laszka A, Johnson B, Grossklags J. FC '15.
- 🎓 [Incentive Compatibility of Bitcoin Mining Pool Reward Functions](http://fc16.ifca.ai/preproceedings/28_Schrijvers.pdf). Schrijvers O, Bonneau J, Boneh D, Roughgarden T. FC '16.
- 🎓 [When cryptocurrencies mine their own business](http://fc16.ifca.ai/preproceedings/29_Teutsch.pdf). Teutsch J, Jain S, Saxena P. FC '16.
- 🎓 [Incentivizing Blockchain Forks via Whale Transactions](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final26.pdf). Liao K, Katz J. FC '17.
- 🎓 [Smart Contracts Make Bitcoin Mining Pools Vulnerable](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final38.pdf). Velner Y, Teutsch J, Luu L. FC '17.
- 🎓 [Mixing Coins of Different Quality: A Game-Theoretic Approach](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final40.pdf). Abramova S, Schöttle P, Böhme R. FC '17.
- 🎓 [Decentralized Prediction Market without Arbiters](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final29.pdf). Bentov I, Mizrahi A, Rosenfeld M. FC '17.
- 🎓 ["Zeus": Analyzing Safety of Smart Contracts](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf). Kalra S, Goel S, Dhawan M, Sharma S. NDSS '18.
- 🎓 [How to Use Bitcoin to Design Fair Protocols](https://eprint.iacr.org/2014/129.pdf). Bentov I, Kumaresan R. CRYPTO '14.
- 🎓 [The Gap Game](http://delivery.acm.org/10.1145/3250000/3243737/p713-tsabary.pdf). Tsabary I., Eyal I. ACM CCS '18.

## Marketplaces and Trust

- 🎓 [Measuring the Longitudinal Evolution of the Online Anonymous Marketplace Ecosystem](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-soska-updated.pdf). Soska K, Christin N. USENIX '15.
- 🎓 [Escrow protocols for cryptocurrencies: How to buy physical goods using Bitcoin](http://www.jbonneau.com/doc/GBGN17-FC-physical_escrow.pdf). Goldfeder S, Bonneau J, Gennaro R, Narayanan A. FC '17.
- 🎓 [Trust Is Risk: A Decentralized Financial Trust Platform](http://fc17.ifca.ai/preproceedings/paper_37.pdf). Thyfronitis Litos OS, Zindros D. FC '17.
- [Trust in decentralized anonymous marketplaces](http://dspace.lib.ntua.gr/bitstream/handle/123456789/43147/pseudonymous-trust-2.pdf?sequence=1). Zindros D. '15.
- [Money as IOUs in social trust networks & a proposal for a decentralized currency network protocol](http://library.uniteddiversity.coop/Money_and_Economics/decentralizedcurrency.pdf). Fugger R. '04.
- [The Ripple protocol consensus algorithm](https://ripple.com/files/ripple_consensus_whitepaper.pdf). Schwartz D, Youngs N, Britto A. '14.
- [The stellar consensus protocol: A federated model for internet-level consensus](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.93&amp=&rep=rep1&amp=&type=pdf). Mazières D. '15.
- 🎓 [There’s No Free Lunch, Even Using Bitcoin: Tracking the Popularity and Profits of Virtual Currency Scams](http://fc15.ifca.ai/preproceedings/paper_75.pdf). Vasek M, Moore T. FC '15.
- 🎓 [Challenges and Opportunities Associated with a Bitcoin-based Transaction Rating System](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_5.pdf). Vandervort D. FC '14.

## Privacy

- 🎓 [Zerocoin: Anonymous distributed e-cash from bitcoin](http://ieeexplore.ieee.org/iel7/6547086/6547088/06547123.pdf). Miers I, Garman C, Green M, Rubin AD. S&P '13.
- 🎓 [Zerocash: Decentralized anonymous payments from bitcoin](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956581.pdf). Sasson EB, Chiesa A, Garman C, Green M, Miers I, Tromer E, Virza M. S&P '14.
- "Monero": [CryptoNote v2.0](https://cryptonote.org/whitepaper.pdf). Saberhagen N. '13?
- 🎓 [Rational Zero: Economic Security for Zerocoin with Everlasting Anonymity](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_12.pdf). Garman C, Green M, Miers I, Rubin A. FC '14.
- [Mixcoin: Anonymity for bitcoin with accountable mixes](https://eprint.iacr.org/2014/077.pdf). Bonneau J, Narayanan A, Miller A, Clark J, Kroll JA, Felten EW. '14.
- [TumbleBit: An untrusted Bitcoin-compatible anonymous payment hub](https://pdfs.semanticscholar.org/a4ce/62a44770a33d1a19b5553f080d4f12e9e55d.pdf). Heilman E, Alshenibr L, Baldimtsi F, Scafuro A, Goldberg S. '16.
- [Blindly Signed Contracts: Anonymous On-Blockchain and Off-Blockchain Bitcoin Transactions](http://fc16.ifca.ai/bitcoin/papers/HBG16.pdf). Heilman E, Baldimtsi F, Goldberg S. FC '16.
- 🎓 [Coinshuffle: Practical decentralized coin mixing for bitcoin](http://crypsys.mmci.uni-saarland.de/projects/CoinShuffle/coinshuffle.pdf). Ruffing T, Moreno-Sanchez P, Kate A. ESORICS '14.
- 🎓 [Quantitative analysis of the full bitcoin transaction graph](https://eprint.iacr.org/2012/584.pdf). Ron D, Shamir A. FC '13.
- 🎓 [How Did Dread Pirate Roberts Acquire and Protect His Bitcoin Wealth?](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_2.pdf). Ron D, Shamir A. FC '14.
- "MoneroLink": [An Empirical Analysis of Linkability in the Monero Blockchain](http://monerolink.com/monerolink.pdf). Miller A, Möser M, Lee K, Narayanan A. '17.
- 🎓 [Provisions: Privacy-preserving proofs of solvency for Bitcoin exchanges](https://eprint.iacr.org/2015/1008.pdf). Dagher GG, Bünz B, Bonneau J, Clark J, Boneh D. CCS '15.
- 🎓 [Increasing Anonymity in Bitcoin](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_19.pdf). Saxena A, Misra J, Dhar A. FC '14.
- 🎓 [Blindcoin Blinded, Accountable Mixes for Bitcoin](http://fc15.ifca.ai/preproceedings/bitcoin/paper_3.pdf). Valenta L, Rowan B. FC '15.
- 🎓 [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf). Kosba A, Miller A, Shi E, Wen Z, Papamanthou C. SP '16
- 🎓 [Could Network Information Facilitate Address Clustering in Bitcoin?](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final11.pdf). Neudecker T, Hartenstein H. FC '17.
- 🎓 [Blind signatures for untraceable payments](http://blog.koehntopp.de/uploads/Chaum.BlindSigForPayment.1982.PDF). Chaum D. CRYPTO '83.
- 🎓 [Exchange Pattern Mining in the Bitcoin Transaction Directed Hypergraph](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final17.pdf). Ranshous S, Joslyn A, Kreyling S, Nowak K, Samatova N, West C, Winters C. FC '17.
- 🎓 [Confidential Assets](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final41.pdf). Poelstra A, Back A, Friedenbach M, Maxwell G, Wuille P. FC '17.
- 🎓 [Mixing Confidential Transactions: Comprehensive Transaction Privacy for Bitcoin](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final6.pdf). Ruffing T, Moreno-Sanchez P. FC '17.
- 🎓 [Switch Commitments: A Safety Switch for Confidential Transactions](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final23.pdf). Ruffing T, Malavolta G. FC '17.
- 🎓 [CoinParty: Secure Multi-Party Mixing of Bitcoins](https://www.martinhenze.de/wp-content/papercite-data/pdf/zgh+15.pdf). Ziegeldorf, J.H., Grossmann, F., Henze, M., Inden, N. and Wehrle, K. CODASPY '15.
- [Data-Driven De-Anonymization in Bitcoin](http://e-collection.library.ethz.ch/eserv/eth:48205/eth-48205-01.pdf). Nick J. Diss. ETH-Zürich, '15.
- 🎓 [Deanonymisation of Clients in Bitcoin P2P Network](https://arxiv.org/pdf/1405.7418.pdf). Biryukov A, Khovratovich D, Pustogarov I. CCS '14.
- 🎓 [Transferable Anonymous Payments via TumbleBit in Permissioned Blockchains](http://ceur-ws.org/Vol-2334/DLTpaper5.pdf). Ferretti C, Leporati A, Mariot L, Nizzardo L. DLT '19.

## Sidechains, Higher layer and Scalability

- [Enabling Blockchain Innovations with Pegged Sidechains](https://blockstream.com/sidechains.pdf). Back A, Corallo M, Dashjr L, Friedenbach M, Maxwell G, Miller A, Poelstra A, Timón J, Wuille P. '14.
- 🎓 [Proofs of Proofs of Work with Sublinear Complexity](http://fc16.ifca.ai/bitcoin/papers/KLS16.pdf). Kiayias A, Lamprou N, Stouka AP. FC '16.
- 🎓 [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. USENIX '16.
- 🎓 [On the Malleability of Bitcoin Transactions](http://fc15.ifca.ai/preproceedings/bitcoin/paper_9.pdf). Andrychowicz M, Dziembowski S, Malinowski D, Mazurek Ł. FC '15.
- 🎓 [On Scaling Decentralized Blockchains](http://fc16.ifca.ai/bitcoin/papers/CDE+16.pdf). Croman K, Decker C, Eyal I, Gencer AE, Juels A, Kosba A, Miller A, Saxena P, Shi E, Sirer EG, Song D. FC '16.
- 🎓 "Elastico": [A secure sharding protocol for open blockchains](https://www.comp.nus.edu.sg/~prateeks/papers/Elastico.pdf). Luu L, Narayanan V, Zheng C, Baweja K, Gilbert S, Saxena P. CCS '16.
- 🎓 [Improving Authenticated Dynamic Dictionaries, with Applications to Cryptocurrencies](http://fc17.ifca.ai/preproceedings/paper_34.pdf). Reyzin L, Meshkov D, Chepurnoy A, Ivanov S. FC '17.
- 🎓 [Service-Oriented Sharding for Blockchains](http://fc17.ifca.ai/preproceedings/paper_73.pdf). Gencer AE, Van Renesse R, Sirer EG. FC '17.
- [Non-Interactive Proofs of Proof-of-Work](https://eprint.iacr.org/2017/963.pdf). Kiayias A, Miller A, Zindros D. '17.
- 🎓 [Proof-of-Stake Sidechains](https://eprint.iacr.org/2018/1239.pdf). Gaži P, Kiayias A, Zindros D. S&P '19.
- 🎓 [Proof-of-Work Sidechains](https://eprint.iacr.org/2018/1048.pdf). Kiayias A, Zindros D. FC WTSC '19.
- [FlyClient: Super-Light Clients for Cryptocurrencies](https://eprint.iacr.org/2019/226.pdf). B Bünz, L Kiffer, L Luu, M Zamani. '19.
- [PolyShard: Coded Sharding Achieves Linearly Scaling Efficiency and Security Simultaneously](https://arxiv.org/pdf/1809.10361.pdf). Li S, Yu M, Avestimehr S, Kannan S, Viswanath P. '18.
- 🎓 [ForkBase: An Efficient Storage Engine for Blockchain and Forkable Applications](http://www.vldb.org/pvldb/vol11/p1137-wang.pdf). Wang S, Dinh TT, Lin Q, Xie Z, Zhang M, Cai Q, Chen G, Ooi BC, Ruan P. PVLDB '18.

## Payment Networks

- 🎓 [A Fast and Scalable Payment Network with Bitcoin Duplex Micropayment Channels](https://pdfs.semanticscholar.org/c8d2/b0c1f9b1ca739c340e9dc4a2ff71b5bfbb2e.pdf). Decker C, Wattenhofer R. SSS '15.
- [The bitcoin lightning network: Scalable off-chain instant payments](https://www.weusecoins.com/assets/pdf/library/Lightning%20Network%20Whitepaper.pdf). Poon J, Dryja T. '15.
- "Deployable Lightning": [Reaching The Ground With Lightning](https://github.com/ElementsProject/lightning/raw/master/doc/deployable-lightning.pdf). Russell R. '15.
- 🎓 [Teechan: Payment Channels Using Trusted Execution Environments](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final21.pdf). Lind J, Eyal I, Pietzuch P, Sirer EG. FC BITCOIN '17.
- 🎓 [Revive: Rebalancing Off-Blockchain Payment Networks](https://eprint.iacr.org/2017/823.pdf). Khalil, R., & Gervais, A. CCS '17.
- [NOCUST – A Non-Custodial 2nd-Layer Financial Intermediary](https://liquidity.network/NOCUST_Liquidity_Network_Paper.pdf). Khalil R, Gervais, A. '18.
- [Counterfactual: Generalized state channels](https://l4.ventures/papers/statechannels.pdf). Coleman J, Horne L, Xuanji L. '18.
- [Sprites and State Channels: Payment Networks that Go Faster than Lightning](https://arxiv.org/pdf/1702.05812.pdf) Miller A, Bentov I, Kumaresan R, Cordi C, McCorry P. '17.
- 🎓 [Perun: Virtual payment hubs over cryptocurrencies](https://eprint.iacr.org/2017/635.pdf) Dziembowski S, Eckey L, Faust S, Malinowski D. IEEE S&P '19.
- 🎓 [General State Channel Networks](https://eprint.iacr.org/2018/320.pdf) Dziembowski S, Faust S, Hostáková K. CCS '18.
- [Bolt: Anonymous Payment Channels for Decentralized Currencies](https://eprint.iacr.org/2016/701.pdf) Green M, Miers I. '16.
- [Flare: An Approach to Routing in Lightning Network](https://bitfury.com/content/downloads/whitepaper_flare_an_approach_to_routing_in_lightning_network_7_7_2016.pdf). Prihodko P, Zhigulin S, Sahno M, Ostrovskiy A, Osuntokyn O. '16.
- [On the Difficulty of Hiding the Balance of Lightning Network Channels](https://eprint.iacr.org/2019/328.pdf). Herrera-Joancomartí J, Navarro-Arribas G, Ranchal-Pedrosa A, Pérez-Solà C, Garcia-Alfaro J. '19.
- [Pisa: Arbitration Outsourcing for State Channels](https://eprint.iacr.org/2018/582.pdf). McCorry P, Bakshi S, Bentov I, Meiklejohn S, Miller A. '18.
- 🎓 [Concurrency and Privacy with Payment-Channel Networks](https://eprint.iacr.org/2017/820.pdf). Malavolta G, Moreno-Sanchez P, Kate A, Maffei M, Ravi S. CCS '17.
- [eltoo: A Simple Layer2 Protocol for Bitcoin](https://blockstream.com/eltoo.pdf). Decker C, Russell R, Osuntokun O. '18.
- [SoK: A Taxonomy for Layer-2 Scalability Related Protocols for Cryptocurrencies](https://eprint.iacr.org/2019/352.pdf). Jourenko M, Kurazumi K, Larangeira M, Tanaka K. '19.
- [SoK: Off The Chain Transactions](https://eprint.iacr.org/2019/360.pdf). Gudgeon L, Moreno-Sanchez P, Roos S, McCorry P, Gervais A. '19.
- [Nitro Protocol](https://eprint.iacr.org/2019/219.pdf). Close T. '19.
- 🎓 [Two-Party State Channels with Assertions](https://fc19.ifca.ai/wtsc/StateAssertions.pdf). Buckland C, McCorry P. FC '19.
- [Anonymous Multi-Hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Malavolta G, Moreno-Sanchez P, Schneidewind C, Kate A, Maffei M. NDSS '19.

## Fungibility

- 🎓 [Towards Risk Scoring of Bitcoin Transactions](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_15.pdf). Möser M, Böhme R, Breuker D. FC '14.

## Network

- 🎓 [The Bitcoin P2P network](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_3.pdf). Donet Donet JA, Perez-Sola C, Herrera-Joancomart J. FC '14.
- 🎓 [Empirical Analysis of Denial-of-Service Attacks in the Bitcoin Ecosystem](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_17.pdf). Vasek M, Thornton M, Moore T. FC '14.
- 🎓 [Eclipse Attacks on Bitcoin's Peer-to-Peer Network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf). Heilman E, Kendler A, Zohar A, Goldberg S. USENIX '15.
- 🎓 [Hijacking Bitcoin: Routing Attacks on Cryptocurrencies](https://arxiv.org/pdf/1605.07524v2). Apostolaki M, Zohar A, Vanbever L. S&P '17.
- 🎓 [Stressing Out: Bitcoin “Stress Testing”](http://fc16.ifca.ai/bitcoin/papers/BHMW16.pdf). Baqer K, Yuxing Huang D, McCoy D, Weaver N. FC '16.
- 🎓 [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS '16.
- [Information Propagation in the Bitcoin Network](http://www.tik.ee.ethz.ch/file/49318d3f56c1d525aabf7fda78b23fc0/P2P2013_041.pdf). Decker C., Wattenhofer R. IEEE P2P '13.

## Smart Contracts

- "Ethereum": [A next-generation smart contract and decentralized application platform](https://www.weusecoins.com/assets/pdf/library/Ethereum_white_paper-a_next_generation_smart_contract_and_decentralized_application_platform-vitalik-buterin.pdf). Vitalik Buterin. '14.
- [Ethereum: A secure decentralised generalised transaction ledger](http://gavwood.com/paper.pdf). Wood G. '14.
- 🎓 [Fair Two-Party Computations via Bitcoin Deposits](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_10.pdf). Andrychowicz M, Dziembowski S, Malinowski D, Mazurek Ł. FC '14.
- 🎓 [Step by Step Towards Creating a Safe Smart Contract: Lessons and Insights from a Cryptocurrency Lab](http://fc16.ifca.ai/bitcoin/papers/DAKMS16.pdf). Delmolino K, Arnett M, Kosba A, Miller A, Shi E. FC '16.
- 🎓 [EthIKS: Using Ethereum to audit a CONIKS key transparency log](http://fc16.ifca.ai/bitcoin/papers/Bon16a.pdf). Bonneau J. FC '16.
- 🎓 "Oyente": [Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf). Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS '16.
- 🎓 [The Ring of Gyges: Investigating the Future of Criminal Smart Contracts](http://www.initc3.org/files/Gyges.pdf). Juels A, Kosba A, Shi E. CCS '16.
- [Town crier: An authenticated data feed for smart contracts](https://eprint.iacr.org/2016/168.pdf). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS '16.
- 🎓 [A Smart Contract for Boardroom Voting with Maximum Voter Privacy](http://fc17.ifca.ai/preproceedings/paper_80.pdf). McCorry P, Shahandashti SF, Hao F. FC '17.
- 🎓 [Constant-deposit multiparty lotteries on Bitcoin](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final39.pdf). Bartoletti M, Zunino R. FC '17.

## Formal Methods

- 🎓 [Automated Verification of Electrum Wallet](http://fc16.ifca.ai/bitcoin/papers/TVR16.pdf). Turuani M, Voegtlin T, Rusinowitch M. FC '16.

## Proof of work

- "Proof-of-work": [Pricing via processing or combatting junk mail](https://web.cs.dal.ca/~abrodsky/7301/readings/DwNa93.pdf). Dwork C, Naor M. '92.
- [Hashcash - A Denial of Service Counter-Measure](http://www.hashcash.org/papers/hashcash.pdf). Back A. '02.
- 🎓 [Cuckoo Cycle: a memory bound graph-theoretic proof-of-work](http://fc15.ifca.ai/preproceedings/bitcoin/paper_12.pdf). Tromp J. FC '15.
- 🎓 [PieceWork: Generalized Outsourcing Control for Proofs of Work](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final24.pdf). Daian P, Eyal I, Juels A, Sirer EG. FC '17.
- 🎓 [Permacoin: Repurposing bitcoin work for data preservation](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956582.pdf). Miller A, Juels A, Shi E, Parno B, Katz J. Permacoin. S&P '14.

## DAG-based consensus

- [SPECTRE: A Fast and Scalable Cryptocurrency Protocol](https://eprint.iacr.org/2016/1159.pdf).
Sompolinsky Y, Lewenberg Y, Zohar A. '16.
- "PHANTOM": [A Scalable BlockDAG protocol](https://eprint.iacr.org/2018/104.pdf). Sompolinsky Y, Zohar A. '18.
- [Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV). Team Rocket. '18.
- [Scaling Nakamoto Consensus to Thousands of Transactions per Second](https://arxiv.org/pdf/1805.03870.pdf). Li C, Li P, Zhou D, Xu W, Long F, Chi-Chih Yao A. '18.
- [Blockchain-Free Cryptocurrencies: A Framework for Truly Decentralised Fast Transactions](https://eprint.iacr.org/2016/871.pdf) Boyen X, Carr C, Haines T. '16.
- [DAGcoin Whitepaper](https://dagcoin.org/whitepaper.pdf) Ribero Y, Raissar D. '15.
- [Byteball: A Decentralized System for Storage and Transfer of Value](https://byteball.org/Byteball.pdf) Churyumov A. '16.

## Survey, Sociological & Anthropological

- 🎓 [Issues in Designing a Bitcoin-Like Community Currency](http://fc15.ifca.ai/preproceedings/bitcoin/paper_2.pdf). Vandervort D, Gaucas D, St Jacques R. FC '15.
- 🎓 [The Bitcoin Market Potential Index](http://fc15.ifca.ai/preproceedings/bitcoin/paper_14.pdf). Hileman G. FC '15.
- 🎓 [Cryptographic Currencies from a Tech-Policy Perspective: Policy Issues and Technical Direction](http://fc15.ifca.ai/preproceedings/bitcoin/paper_16.pdf). McReynolds E, Lerner A, Scott W, Roesner F, Kohno T. FC '15.
- 🎓 [The Other Side of the Coin: User Experiences with Bitcoin Security and Privacy](http://fc16.ifca.ai/preproceedings/33_Krombholz.pdf). Krombholz K, Judmayer A, Gusenbauer M, Weippl E. FC '16.
- 🎓 [An analysis of Bitcoin OP_RETURN metadata](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final32.pdf). Bartoletti M, Pompianu L. FC '17.

## Applications

- [Blockstack Technical Whitepaper](https://blockstack.org/whitepaper.pdf). Muneeb A., Ryan S., Jude N, Michael F. '17
- [Storj A Peer-to-Peer Cloud Storage Network](https://storj.io/storjv3.pdf). Shawn W., Tome B., Josh B., James P., Gordon H., Patrick G., Philip H., Chris P. '18
- [IPFS - Content Addressed, Versioned, P2P File System](https://github.com/ipfs/papers/raw/master/ipfs-cap2pfs/ipfs-p2p-file-system.pdf). Benet J. '15
- [BigchainDB: A Scalable Blockchain Database](https://www.bigchaindb.com/whitepaper/bigchaindb-whitepaper.pdf). McConaghy T, Marques R, Müller A, De Jonghe D, McConaghy T, McMullen G, Henderson R, Bellemare S, Granzotto A. '17
- 🎓 [Commitcoin: Carbon dating commitments with bitcoin](https://eprint.iacr.org/2011/677.pdf). Clark J, Essex A. FC '12.
- [OpenTimestamps: Securing Software Updates using the Bitcoin Blockchain Financial Cryptography and Data Security](https://github.com/opentimestamps/). Todd P, Halpin H. (FC Poster '17)
- 🎓 [Decentralized trusted timestamping using the crypto currency bitcoin](https://arxiv.org/pdf/1502.04015.pdf). Gipp B., Meuschke N., Gernandt A. iConference 2015
- 🎓 [Fair and Robust Multi-Party Computation using a Global Transaction Ledger](https://eprint.iacr.org/2015/574.pdf). Kiayias A., Zhouh S., Zikas V. EUROCRYPT '16.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


This list is released into the public domain.
