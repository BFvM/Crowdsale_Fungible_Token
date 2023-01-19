# Fungible_Token_Crowdsale_Project
Creating a fungible token with Soldity, Ethereum and OpenZepplin

This challenge required the creation of a ERC_20 compliant fungible token that can be minted using a Crowdsale contract within the OpenZepplin Solidity library.

It enables users to send ether in return for KaseiCoin (KAI) tokens. The minting and distribution process is automated in a single transaction.

# Techology Used in This Challenge
This project uses python version 3.9.12 with:

- Solidity
- Remix IDE
- MetaMask
- Ganache
- OpenZepplin

# Project Details
**1. Coding required files**

Solidity files for KaseiCoin and KaseiCoinCrowdsale were created and deployed as shown below:

![1_KaseiCoin_compile_confirmation](https://user-images.githubusercontent.com/110360757/213431607-8b53306f-796f-4c73-aa89-e3c0098c54bb.png)

![2_KaseiCoinCrowdSale_compile_confirmation](https://user-images.githubusercontent.com/110360757/213431695-c81d91e6-3993-467c-80bd-14d14ac8f4b4.png)

 **2. Deployment, contract and minting**

Once complied, contracts and addresses for KaseiCoinCrowdsaleDeployer, KaseiCoinCrowdsale and KaseiCoin were set up and deployed.

A test mint of 100 WEI was executed, followed by 5 separate ETH amounts.

https://user-images.githubusercontent.com/110360757/213433536-d8757beb-4f46-4ac5-9aff-06897ec23e8e.mov

**3. KaseiCoin Confirmation**

Confirmation of minting was verifified in the KaseiCoin Contract

![4_KasieCoin_Supply](https://user-images.githubusercontent.com/110360757/213434109-8a8886c9-7ca0-4079-b250-6acabf736484.png)

And in the Ganache Accounts

![5_Ganache_transaction_confirmation](https://user-images.githubusercontent.com/110360757/213434160-192642e3-e2cd-4ed8-a8be-2c4779409e51.png)


