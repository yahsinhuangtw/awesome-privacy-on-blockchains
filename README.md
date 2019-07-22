# Awesome Privacy on Blockchains
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

- [Awesome Privacy on Blockchains](#awesome-privacy-on-blockchains)
  * [High-level articles](#high-level-articles)
  * [Talks and Lectures](#talks-and-lectures)
  * [Layer 1](#layer-1)
  * [Layer 2](#layer-2)
    + [Mixers](#mixers)
    + [Confidential Transactions](#confidential-transactions)
    + [Payment/State Channels](#payment-state-channels)
    + [Plasma](#plasma)
    + [MPC Platforms for Privacy-Preserving smart contracts](#mpc-platforms-for-privacy-preserving-smart-contracts)
  * [Alternate Blockchain designs](#alternate-blockchain-designs)
    + [Blockchains with private smart contracts](#blockchains-with-private-smart-contracts)
    + [Using Zk-Snarks](#using-zk-snarks)
    + [Using other cryptographic primitives](#using-other-cryptographic-primitives)
  * [Privacy-Preserving PoS Protocols](#privacy-preserving-pos-protocols)
  * [Privacy Preserving Light Client Designs](#privacy-preserving-light-client-designs)
  * [Enhancements](#enhancements)
  * [Instantiations](#instantiations)
    + [Proof of Concepts](#proof-of-concepts)
    + [Wallets](#wallets)
  * [Network layer privacy for blockchains](#network-layer-privacy-for-blockchains)
  * [Analyses on Anonymity and Privacy in blockchains](#analyses-on-anonymity-and-privacy-in-blockchains)
  * [De-anonymization Techniques](#de-anonymization-techniques)
  * [Privacy coins](#privacy-coins)
    + [Monero](#monero)
    + [Zcash](#zcash)
    + [Zcoin](#zcoin)
    + [Dash](#dash)
    + [Grin/Beam](#grin-beam)
  * [People to Follow](#people-to-follow)
  * [Misc](#misc)
  
## High-level articles
- [Privacy in Cryptocurrencies: An Overview](https://medium.com/@yi.sun/privacy-in-cryptocurrencies-d4b268157f6c)
- [Privacy in Cryptocurrencies: Mixing-based Approaches](https://medium.com/@yi.sun/privacy-in-cryptocurrencies-mixing-based-approaches-ce08d0040c88)
- [Zeth & Nightfall: the differences in approach](https://medium.com/clearmatics/zeth-nightfall-the-differences-in-approach-62ce33472683)
- [Blockchain Research Newsletter: Zether and ZEXE](https://blockchainresearch.substack.com/p/blockchain-research-newsletter-2)
- [In-depth overview of Privacy in Bitcoin](https://en.bitcoin.it/wiki/Privacy)

## Talks and Lectures
- [Alessandro Chiesa on Zerocash at CESC2017](https://www.youtube.com/watch?v=84Vbj7-i9CI&source=post_page---------------------------)
- [Bitcoin and Anonymity](https://www.youtube.com/watch?v=glyQy_e5LmM)
- [Satoshi has no clothes: failures in on-chain privacy](https://www.youtube.com/watch?v=9s3EbSKDA3o)
- [The state of Privacy in Cryptocurrencies](https://www.youtube.com/watch?v=AJGLhaUV8QM)

## Layer 1
- [Increasing Anonymity in Bitcoin](https://download.wpsoftware.net/bitcoin/wizardry/horasyuanmouton-owas.pdf)

## Layer 2 
### Mixers
- [Zeth](https://arxiv.org/pdf/1904.00905.pdf)
- [Mobius](https://eprint.iacr.org/2017/881.pdf)
- [MixEth](https://eprint.iacr.org/2019/341.pdf)
- [ShareLock](https://eprint.iacr.org/2019/563)
- [CoinJoin](https://en.bitcoin.it/wiki/CoinJoin)
- [JoinMarket](https://en.bitcoin.it/wiki/JoinMarket)
- [MixCoin: Anonymity for Bitcoin with Accountable Mixes](https://eprint.iacr.org/2014/077.pdf)
- [CoinParty](https://www.martinhenze.de/wp-content/papercite-data/pdf/zmh+16.pdf)
- [TumbleBit](https://eprint.iacr.org/2016/575)

### Confidential Transactions
- [Confidential Transactions](https://people.xiph.org/~greg/confidential_values.txt)
- [Zether](https://crypto.stanford.edu/~buenz/papers/zether.pdf)
- [Aztec Protocol](https://github.com/AztecProtocol/AZTEC/blob/master/AZTEC.pdf)
- [Nightfall](https://github.com/EYBlockchain/nightfall/blob/master/doc/whitepaper/nightfall-v1.pdf?source=post_page---------------------------)

### Payment/State Channels
- [BOLT](https://acmccs.github.io/papers/p473-greenA.pdf)
- [Blindly Signed Contracts: Anonymous on-Blockchain and Off-blockchain Bitcoin Transactions](https://eprint.iacr.org/2016/056)
- [Anonymous Multi-Hop Locks for Blockchain Scalability and Interoperability](https://eprint.iacr.org/2018/472.pdf)

### Plasma
- [ZEXE on Plasma MoreVP](https://devpost.com/software/zexe-on-ethereum)


### MPC Platforms for Privacy-Preserving smart contracts
- [Enigma](https://enigma.co/enigma_full.pdf)

## Alternate Blockchain designs
### Blockchains with private smart contracts
- [Zexe](https://eprint.iacr.org/2018/962.pdf)
- [RingCT](https://eprint.iacr.org/2015/1098.pdf)
- [One-time, zero sum ring signature](https://github.com/cfromknecht/OZcoin/blob/master/whitepaper/zerosum.pdf)
- [Hawk](https://eprint.iacr.org/2015/675.pdf)
- [Arbitrum](https://offchainlabs.com/Arbitrum-USENIX.pdf)
- [ZkVM](https://github.com/stellar/slingshot/blob/main/zkvm/README.md)
- [Ekiden](https://arxiv.org/abs/1804.05141)

### Using Zk-Snarks
- [Zerocash](http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf)
- [Zerocoin](http://zerocoin.org/media/pdf/ZerocoinOakland.pdf)
- [Accountable Privacy for Decentralized Anonymous Payments](https://eprint.iacr.org/2016/061.pdf)

### Using other cryptographic primitives
- [QuisQuis](https://eprint.iacr.org/2018/990.pdf)
- [MimbleWimble](https://download.wpsoftware.net/bitcoin/wizardry/mimblewimble.pdf)
- [Cryptonote](https://download.wpsoftware.net/bitcoin/wizardry/cryptonote-whitepaper.pdf)
- [Lelantus](https://lelantus.io/lelantus.pdf)
- [One-out-of-Many Proofs](http://discovery.ucl.ac.uk/1502142/1/Groth_764.pdf)
- [ZkLedger](https://eprint.iacr.org/2018/241.pdf)
- [Cryptonote+](https://eprint.iacr.org/2019/021.pdf)

## Privacy-Preserving PoS Protocols
- [Ouroborous Crypsinous](https://eprint.iacr.org/2018/1132.pdf)
- [Proof of stake protocols for privacy aware blockchains](https://eprint.iacr.org/2018/1105.pdf)

## Privacy Preserving Light Client Designs
- [ZLiTE](https://eprint.iacr.org/2018/1024.pdf)
- [Neutrino](https://github.com/lightninglabs/neutrino)
- [BITE](https://www.usenix.org/system/files/sec19fall_matetic_prepub.pdf)


## Enhancements
- [Bulletproofs](https://eprint.iacr.org/2017/1066.pdf)

## Instantiations
### Proof of Concepts
- [MixEth Repo](https://github.com/seresistvanandras/MixEth)
- [Miximus](https://github.com/barryWhiteHat/miximus)
- [RingToken](https://github.com/sontol/RingToken)
- [Laundromat](https://github.com/blackyblack/laundromat)

### Wallets
- [Wasabi Wallet](https://wasabiwallet.io/)
- [Samourai Wallet](https://samouraiwallet.com/)

## Network layer privacy for blockchains
- [Dandelion](https://arxiv.org/pdf/1701.04439.pdf)
- [Dandelion++](https://arxiv.org/pdf/1805.11060.pdf)

## Analyses on Anonymity and Privacy in blockchains
- [Anonymity Properties of the Bitcoin P2P Network](https://arxiv.org/pdf/1703.08761.pdf)
- [A Survey on Security and Privacy Issues of Bitcoin](https://arxiv.org/pdf/1706.00916.pdf)
- [An empirical analysis of traceability of the monero blockchain](https://arxiv.org/pdf/1704.04299.pdf)
- [Obfuscation in Bitcoin: Tecniques and Politics](https://arxiv.org/pdf/1706.05432.pdf)
- [The price of anonymity: empirical evidence from a market for Bitcoin anonymization](https://watermark.silverchair.com/tyx007.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAk0wggJJBgkqhkiG9w0BBwagggI6MIICNgIBADCCAi8GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMkVUudbfGyrLDOnpmAgEQgIICABYGt3mQkv26M8bkZ6fgufnqyC2cbLUCRY_YdLqfUy3PNSoHbc4i3eZN7oBaT3dF6uElybwVydRPTSaXogFAZccx1RAXULpCfUF7K8MlnVJOYsMe8pCodQWXfAQPvQAxtEXvnPpxSfCQqEOBnHL_bGFBn1JCb23e7-H3XI4swOf8hccHCHqPDN5raiNikGHnVtKb6IpU8GC585YbQRNysZA0X3mj98zhyHv8Rnz0Wa45aKcHdg7cccQ7tEyT81ZP9G9TOdH3fMUm7NlratQrahznsSRw-pEIHjIeeLspBSMGa0PNTBrbebL0i3-XwNsKCLwX6iOP6oKZJPYNn8l-D89EcRB9QR2dC0U3-2G77owEv2T9tW1hxxpQjAAvggjORParcrbwn4fzQr0OM4qED1im8UcAvbT2kbXhUTAxkLXoiYmqIagN5MaKCYjv3otiouEq7yYYYfDFkPFj47wMiq5GGcURg0xh8l_Wl4xqUDSX5rtHWJCVEmdXKJzz-Y7lJ9GN9sBvLXZ9T1za3DIAX6_m093a-z9d_XBL4Z6n8oUzy5DEUYZD1T-z2ONSInbYdHXHJfUW62ZdslmM-21qzL1QOP2BxRc5om5H3YFCi_3Yr8uIm316kgM3YiqtCkc7ARPn14QY6q1EuJpg_5fZntRbv0HMd-MW3HSHA3GqBV_T)
- [Anonymous Alone? Measuring Bitcoin's Second-Generation Anonymization Techniques](https://informationsecurity.uibk.ac.at/pdfs/MB2017_AnonymousAlone.pdf)
- [An Empirical Analysis of Anonymity in Zcash](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kappos.pdf)

## De-anonymization Techniques
- [Tracing Transactions Across Cryptocurrency Ledgers](https://arxiv.org/pdf/1810.12786.pdf)

## Privacy coins
### Monero
- [Zero to Monero](https://ww.getmonero.org/library/Zero-to-Monero-1-0-0.pdf)
- [Mastering Monero](https://github.com/monerobook/monerobook)
### Zcash
### Zcoin
### Dash
### Grin/Beam

## People to Follow
- [Ian Miers](https://twitter.com/secparam)
- [Charles Guillemet](https://twitter.com/P3b7_)
- [Anna Kaplan](https://twitter.com/kaplannie)
- [Tux](https://twitter.com/__Tux)
- [Madars Virza](https://twitter.com/MadarsV)
- [Daniel J Bernstein](https://twitter.com/hashbreaker)
- [David Wong](https://twitter.com/cryptodavidw)
- [Chelsea H. Komlo](https://twitter.com/chelseakomlo)
- [Deidre Connolly](https://twitter.com/durumcrustulum)
- [Izaak Meckler](https://twitter.com/izmeckler)
- [Justin Ehrenhofer](https://twitter.com/JEhrenhofer)
- [Aaron Kumavis](https://twitter.com/kumavis_)
- [Phil Daian](https://twitter.com/phildaian)
- [Matthew Green](https://twitter.com/matthew_d_green)
- [John Adler](https://twitter.com/jadler0)
- [BarryWhiteHat](https://twitter.com/barrywhitehat)
- [Mikerah](https://twitter.com/badcryptobitch)

## Misc
- [Zero-Knowledge Started Pack](https://ethresear.ch/t/zero-knowledge-proofs-starter-pack/4519/2)
- [Zero Knowledge papers](zkp.science)
- [Awesome Zero-Knowledge Proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)


