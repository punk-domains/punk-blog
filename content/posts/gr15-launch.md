---
title: "Support Punk Domains in Gitcoin Round 15"
date: 2022-09-07T11:32:22+02:00
cover:
  image: https://blog.punk.domains/img/gr15/cover.jpg
images: ["https://blog.punk.domains/img/gr15/cover.jpg"]
---

A new Gitcoin round has started today and it will last until 22 September. We are happy to announce our participation in Gitcoin Round 15! (Link to our Gitcoin grant: https://gitcoin.co/grants/4830/punk-domains)

## What is Gitcoin?

Gitcoin is a platform on which **anyone can donate** to web3 projects and help them **fund their development**.

But not only that! Gitcoin and its sponsors then **add additional funds to your donation**. This sponsor matching can be 5x, 10x, or even 100x of what you donate.

So in the end, your $10 donation can become a $100 or even a $1000 donation with the help of Gitcoin sponsors. How awesome is that?

## Why projects seek funding on Gitcoin?

There are many web3 projects that either can’t get VC funding, or don’t want to get it.

Being independent from VCs helps you **focus on building what your users want**, instead of focusing on making VCs rich.

If we want the web3 ecosystem to be truly decentralized and permissionless, we need projects that are **completely open-source and independent**, without big players pulling the strings in the background.

## Punk Domains and Gitcoin

So far we have participated in Gitcoin rounds 13 and 14. In Round 13 we raised slightly less than $3k. In Round 14 we’ve raised around $15k from Gitcoin donors. (A huge thanks again to everyone who donated!)

Before GR13 we’ve built and launched **version 1 of the Punk Domains protocol**, which included the [Standard Factory smart contract](https://github.com/punk-domains/punk-contracts/blob/main/contracts/factories/standard/PunkTLDFactory.sol), the [Standard TLD contract](https://github.com/punk-domains/punk-contracts/blob/main/contracts/factories/standard/PunkTLD.sol), and the [smart contract that coordinates](https://github.com/punk-domains/punk-contracts/blob/main/contracts/PunkForbiddenTlds.sol) which domain extensions have already been registered. 

Besides smart contracts we’ve also developed the **frontend** which is accessible via https://punk.domains.

## Achievements after Gitcoin Round 13

After GR13 we've **launched browser extensions** for all major browsers: [Chrome, Brave, Firefox, Edge, and Opera](https://punk.domains/#/browser). If a punk domain has a URL associated with it, the extension will redirect the user to it. The extension also helps users search punk domains on block explorers.

We have launched the [Flexi smart contracts](https://github.com/punk-domains/punk-contracts/tree/main/contracts/factories/flexi) which make **domain extensions even more powerful**, because they can now have custom images, and feature new contract roles.

After GR13, **the first 3 web3 communities** got their **own domain extensions** running on top of the Punk Domains protocol:

- **Layer2DAO** ([.L2 domains](https://punk.domains/#/partners/l2dao)), 
- **KlimaDAO** ([.klima domains](https://www.kns.earth/)), 
- **Smol Brains NFT community** ([.smol domains](https://smol.domains/)).

Funds from GR13 mainly covered the costs of smart contract deployments and some other smaller running costs (web hosting etc.).

## Achievements after Gitcoin Round 14

Funds raised in GR14 helped us focus more on the project. Two team members now work almost full-time on the Punk Domains protocol.

After this round we've developed a **tiered pricing smart contract** for domain extensions. [This contract](https://github.com/punk-domains/punk-contracts/blob/main/contracts/nft/angel/PunkAngelMinter.sol) sets domain prices based on domain name length. 

Another important development was the **Resolver smart contract**. While each domain contract has an in-built resolver, it is important to have a "global" [resolver contract](https://github.com/punk-domains/punk-contracts/blob/main/contracts/resolver/PunkResolverV1.sol) which can resolve all punk domains in one place. This makes Punk Domains integrations to other products **easier and more durable**, while still being **completely on-chain**.

We have launched the Punk Domains protocol on two new networks: **BSC**, and the **Ethereum L1 mainnet** (due to a request from a web3 community that has their project running solely on Ethereum L1).

**Three new web3 communities** have launched their domain extensions through the Punk Domains protocol: 

- **HUWA web3 community** ([.huwa domains](https://punk.domains/#/partners/huwa)), 
- **Lufroloc NFT community** ([.ppl domains](https://ppl.domains/#/)), 
- **The Wild Bunch community** ([.wildbunch domains](https://twb.punk.domains/#/)).

## Plan after GR15

After Gitcoin Round 15, we’ll focus on building **Web3 Social websites for our partners** (web3 communities and DAOs). Web3 Social is the **next big frontier** that we’re heading to in the next couple of years. 

Right now, Web3 Social **feels like DeFi in 2019**. Not many people know about it, but a lot is brewing under the surface. We will definitely **not miss that train**.

Besides web3 social, we’ll **continue onboarding new DAOs and web3 communities** to Punk Domains. Hopefully, funds raised in GR15 will help us hire an additional developer, because the interest from web3 communities is growing every month.

Last but not least, we’ll further **improve our browser extensions** and deploy Punk Domains on some **new EVM chains**, like Aurora and Arbitrum Nova.

## Punk Domains Mission

Our **mission** is to help **build Web3 Social** where web3 domains are the integral part, serving as **usernames** and **digital identities**. 

We want to **enable any web3 community** and its users to **get and truly own their domains**. In addition, we'll provide these communities with Web3 Social frontend templates (built on top of social graphs such as [Orbis](https://orbis.club) and Lens), so that they can quickly spin out their own Web3 Social websites.

We believe it's high time for the crypto community to start focusing on non-financial use cases, and build a **new kind of social network** which **fixes the mistakes** of traditional social media.

All our work is public on Gitcoin and we consider it as **public good** (anyone can fork it or build on top of it): https://github.com/punk-domains. **Let's build the new world together!**
