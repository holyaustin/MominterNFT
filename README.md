# Mominter : : Decentralized Video Moment Minter for Nebula Testnet Blockchain

A DApp to allow the user(host) to mint moments as NFT using the contracts deployed on Mantle Hyperscale performance. On Mantle chain, we experience high throughput with unrivaled security with Ethereum's roll-up technology.

![Mominter](https://bafkreibsvdrhg4xrmdeujrz33smda7rziayuzpxb5cggcp4o5633sn4c2a.ipfs.nftstorage.link/)

## Introduction

Mominter is a web3 video project with the aim of helping creators publish exciting video Moments as NFTs  and share them easily while owning their content and possibly making money from it. This project intends to build a web3 Moment Gallery for everyone around the globe. Users can use the Huddle01 video streaming to record presentation and mint them while storing the Video files on IPFS and Metadata on Nebula Testnet Blockchain.
Contents can also be streamed live through Huddle01 Live Presentation SDK streams. We use the open zeppelin ERC721 standard, Files are store to IPFS / Filecoin using NFT.Storage and  file metadata URI stored on Nebula Testnet. Upon retrieval, . Lighthouse was used to used for encryption and most important, the Access control of Light hoise was used to grant access to member with the membership NFT, Huddle for conference meeting and XMTP for chat and interaction.

## Web 3.0 technologies Used

Frontend: NextJS, postcss, tailwindcss, Theme

Web3 technologies: LightHouse, Huddle01,  IPFS/filecoin, Livepeer (livepeer.js), Web3Modal,  Nebula Testnet,
Backend: Solidity, Node.js

Blockchain deployed to:  Nebula Testnet

## Description

This project was made using several technologies. The front-end was designed using a server-side-rendering javascript tech known as NextJS. the latest version of Next was used because of how fast it was to build the project.  IPFS / Filecoin's NFT.Storage was used to store user's video on their decentralized storage. videos of various news can be viewed on demand. They can share these Videos to anyone through a sharing mechanism that is easy to copy out the sharing IPFS URL. Huddle01 for video streaming and CONFERENCE MEETING. Huddle01 was used for conference meeting.

The smart contract uses ERC-721 specification to hold metadata URI, ethers.js was used to interact with the smart contract. The contract was deployed to Nebula T testnet blockchain. The entire project demo was hosted to Vercel.

## Live DApp hosted on

Live Dapp on Vercel: - <https://mominter4-mantle.vercel.app//>

Deployed to Polygon Chain:
  Mantle Testnet deployed Address = "0x085446624cA30579532B12B7EAeD211B1E6Ac1de"

  <https://explorer.testnet.mantle.xyz/address/0x085446624cA30579532B12B7EAeD211B1E6Ac1de>

 Youtube video link: <https://youtu.be/kZvxCGMPci8>

## Getting Started

First, run the development server:

```text
clone the repo https://github.com/holyaustin/Mominter4Mantle
# next is to 
npm install
# then
npm run dev
# or
yarn dev
```

Open [http://localhost:3014](http://localhost:3014) with your browser to see the result.

## How to run this project locally

Try running some of the following tasks:

Fork this repo using

git clone <https://github.com/holyaustin/Mominter.git>

cd soldier-ant-colony

npx hardhat node

npx hardhat run scripts/deploy.js --network localhost

npm run build

## How to deploy to Filecoin  blockchain, update hardhat.config

npx hardhat run scripts/deploy.js --network testnet

https://testnet.u2uscan.xyz/address/0xe078fe7A93017F8e18c1C52E79632d0B94c56c26

## Connect with me and send me a mail

E-mail - <holyaustin@yahoo.com>

stay connected on twitter @holyaustin

<https://live-par-1-abr-cdn.livepush.io/live_abr_cdn/emaIqCGoZw-6/index.m3u8>

## Verify Contract
npx hardhat verify --network nebulas 0xe078fe7A93017F8e18c1C52E79632d0B94c56c26

Successfully submitted source code for contract
contracts/Genic.sol:FileNFT at 0xe078fe7A93017F8e18c1C52E79632d0B94c56c26
for verification on the block explorer. Waiting for verification result...

Successfully verified contract FileNFT on the block explorer.
https://testnet.u2uscan.xyz/address/0xe078fe7A93017F8e18c1C52E79632d0B94c56c26#code