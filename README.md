# TokSwap Guide

### Introduction

Welcome to an automated on-chain marketplace based entirely on smart contracts. Our goal is to help developers and users achieve a fast value exchange in the world of Elastos.

Since this project is cloned from the Uniswap V2 code, you can read about it on the official Uniswap website or other related introductory articles on the web, TokSwap is identical to Uniswap V2 from an operational point of view.

##### Reference

Uniswap Doc: https://uniswap.org/docs/v2/

##### Contracts

UniswapV2 Factory ： [0xFc09C4A466A4FBa6bE80009cee63E24C2F168371](https://escscan.elaphant.app/address/0xfc09c4a466a4fba6be80009cee63e24c2f168371/transactions)

wELA ：[0x517E9e5d46C1EA8aB6f78677d6114Ef47F71f6c4](https://escscan.elaphant.app/address/0x517E9e5d46C1EA8aB6f78677d6114Ef47F71f6c4/transactions)

Uniswap V2 Router ：[0x1FF9598aBCBbC2F3A9B15261403459215b352e2b](https://escscan.elaphant.app/address/0x1FF9598aBCBbC2F3A9B15261403459215b352e2b/transactions)

### Roles

It has two roles: Trader and Market maker.

##### Trader

You can trade Tokens in TokSwap and anyone who engages in buying or selling can be considered a trader.

##### Market maker

Those who offer trading pairs in the TokSwap pool will also share a 0.3% commission on the amount traded. Market makers who provide liquidity will receive LP Token as proof.

### How to add LP token to your wallet

You can find your pool information in [info.tokswap.net](https://info.tokswap.net), at the bottom of the page you can see the contract address of the pool, it is the contract address of your LP Token, when you add a custom token in your wallet, you can paste this address to import it to your wallet..

### How to add your token to TokSwap

Here's our Token List.
https://tokswap.net/tokswap_tokenlist.json

There are two ways to add your token to TokSwap.

1. Submit an issue to this repository and provide your token's description information, you can see the format in the above tokenlist. 

2. Configure your token information in Cryptoname. This is done as follows.

Create an extended key called "elatoken" in Cryptoname, and convert your token from json to string, fill in the "value" field, and submit it. Then you can enter your Crytptoname in TokSwap and you're ready to go.

##### Raw Token Info
```
{
    "chainId": 20,
    "address": "0x677d40ccc1c1fc3176e21844a6c041dbd106e6cd",
    "name": "Elaphant",
    "symbol": "ELP",
    "decimals": 8,
    "logoURI": "https://elaphant.app/favicon-32x32.png"
}
```

##### Online Conversion Tool
https://tools.knowledgewalls.com/jsontostring

##### After conversion
```
"{\"chainId\":20,\"address\":\"0x677d40ccc1c1fc3176e21844a6c041dbd106e6cd\",\"name\":\"Elaphant\",\"symbol\":\"ELP\",\"decimals\": 8,\"logoURI\":\"https:\/\/elaphant.app\/favicon-32x32.png\"}"
```

##### Examples of "Elaphant"
https://elaphant.elastos.name/elatoken











