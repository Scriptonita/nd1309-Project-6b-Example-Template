# Project 6 - Ethereum Dapp for Tracking Items through Supply Chain

## The contract address

SupplyChain:

https://rinkeby.etherscan.io/address/0x6e6f6915711768d9caa7ce8d3fe7b1f30e411c2e  
Complete Deploy log: './rinkeby-deploy-log.txt'

- transaction hash: 0xaed5d5c99f7227b966f2277c39b6155a76a3f50819a615a683e660f410a5de0d
- Blocks: 0 Seconds: 8
- contract address: 0x6E6f6915711768d9Caa7ce8D3fe7B1f30E411c2e
- block number: 6484179
- block timestamp: 1589418125
- account: 0xEd7EbF089f0D67308ADfeE24df299d73e3752942

Transactions:

1. Harvested: 0xf8f46b80ad11dae0bda39048624520b1283af970a722a89ae52a8894299937de
2. Processed: 0x89958f73c0d349cc740eada39df5f2569a08c54fc79ee61358b107aef7be36c2
3. Packed: 0x1c67a29c087030041e83560a4ca83ea8a5c5ccdc090e76fc9b4411dfca014560
4. ForSale: 0x468ddb04834ac0466dc93de27f27092cb8295091cc436aab7391cd491a6dd69e
5. Sold: 0x8d9c4d7ada35410f4eccdd4dee99e09ed10427519fdcfb97a1615a5b21e86495
6. Shipped: 0x93a3f17e3bc2887807b2f388a7a10e26806dd1eab26f9cb1ebc8fb143aadd5a0
7. Received: 0x1209d63b1200a5b108fbed483980b682df0bca3aad736bb262565f67b11b85bb
8. Purchased: 0xd10c937a7e87be14f32e8a64132dcc4f0dc97a7aef1468bb3be756dfb86095e5

Replacing 'SupplyChain'  
https://rinkeby.etherscan.io/address/0x7D958570A001C00b3Ff4492d367e04Ee48B47EA8  
Complete Deploy log: './rinkeby-deploy-log-updated.txt'

- transaction hash: 0x26617cac4a90047f5d687896f5c45865050f7ea3bd4a74916884e3d7594978d2
- Blocks: 1 Seconds: 13
- contract address: 0x7D958570A001C00b3Ff4492d367e04Ee48B47EA8
- block number: 6506519
- block timestamp: 1589753225
- account: 0xEd7EbF089f0D67308ADfeE24df299d73e3752942

Transactions:

1.- Hasvested: 0x4e10d59d4c41c82790d9898988f7df47c5625673effb423cf57e98c5af2d2394
2.- Processed: 0xf6d62d914215236c1691f20a46dd1a3bb33af10ef2e302fabd1eb99d548debad
3.- Packed: 0x2c8f6b142957e19858668bab8f41988a7e79a25415952fea70a0149dc53dee66
4.- ForSale: 0x4a4f82e845be2269c49374968da6e9f641757814b06a753d9ab21d92af65c330
5.- Sold: 0xc78821e90f77b71ecd6e3634a1b401d1273d74fb9a10aa78e88389c77f955026
6.- Shipped: 0x5dc75337eed5d63bb66d1a54c89006363c682cb2ad75d68c07f7cddcb3366d1b
7.- Received: 0x5eba662e2c8d2bcce62c055fcba86dc0758bc9a1b0e5bb8b65f607cd250f5bde
8.- Purchase: 0x92ca8d97f0c4e817d5014766c9476bbb4eeafd4af8f9f392eed306dea3f35d84

## If libraries were used, include why these libraries were adopted.

- truffle-assertions: To avoid the error in tests with event.watch()
- @truffle/hdwallet-provider: It is needed to deploy in Rinkeby network as a Wallet provider.

## If IPFS is used, include how IPFS is used in this project.

At the begining we are not adding IPFS.

## Program version numbers (This information will help your reviewer troubleshoot your project if any issues arise):

v1.0.1

## node version number

v10.19.0

## Truffle version number

v5.1.19

## web3 version number

web3@1.2.1
transaction_history
