---
description: Our minting contract is specially designed to help our users save gas fees!
---

# 🍃 ERC721A Minting

## TLDR

* ERC721A is an implementation of IERC721 with significant gas savings for minting multiple NFTs in a single transaction.
* The Pigskin Pals NFT Minting contract will enable minting multiple NFTs for **essentially the same cost of minting a single NFT.**
* In addition to the 3 software engineers on our team that have audited this contract, we have paid for external consultancy services to ensure our minting contract is safe and exploit-free.
* The gas savings in the table below translates to a reduced cost in USD, though the exact USD amount may vary as gas fees and the price of Ethereum also may vary.

![Comparing gas costs from OpenZepplin's ERC721ENumerable vs ERC721A](<../.gitbook/assets/Screen Shot 2022-05-18 at 3.50.43 PM.png>)



## Why?

Gas prices on Ethereum have been high since the NFT marketplace took off in 2021. Due to the high amount of transactions that need to be processed and the demand for minting NFTs, we want to ensure that our users do not need to spend a fortune in order to play our game. Our mission is to build a community of people who are passionate about fantasy football and love to play our game!

## How?

This new implementation of a minting contract saves gas by reducing reduntant metadata storage, updating the owner's balance once per batch mint rather than each individual mint. For more information on implementation details, please visit [https://www.erc721a.org/](https://www.erc721a.org/)
