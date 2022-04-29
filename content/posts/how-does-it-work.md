---
title: "How does it work?"
date: 2022-02-28T12:05:14+02:00
---

Let's take a more technical overview of Punk Domains. The main Punk Domains engines are TLD Factory contracts.

![](/img/architecture.png)

### TLD Factories

Each factory has a TLD template that defines its business logic. Currently, there's only one factory contract which allows for one-time TLD and domain purchases. This means that these domains never expire (holders can hold them forever).

In the future, new TLD factories will be added, each with a different business logic and each with its own mix of one-time and/or renewable TLDs/domains rules (and perhaps new business models that we haven't thought yet about).

### Restricted TLD names

TLD factories need to communicate in order to avoid TLD collision (meaning two factories producing the same TLD).

In order to prevent collisions, there's a contract called `PunkForbiddenTlds`, which has a list of already used or restricted TLD names (`.eth` is an example of a forbidden TLD name, because it's used in ENS).

### TLD contracts

A TLD needs to be purchased (minted) from a TLD Factory for a certain price. There needs to be a (high enough) price to avoid spamming and squatting.

(Note that a TLD Factory can temporarily restrict new TLD mints to the factory owner only.)

A TLD contract can be owned by anyone. The TLD owner can set domain prices and can stop domain sales anytime they want.

- Example of a TLD: `.web3`
- Example of a domain: `techie.web3`

The factory owner can set a royalty for each domain purchase, but the royalty can never exceed 50% of the domain price (in reallity it will be much lower).

The TLD owner cannot confiscate domain from its holder, just like Factory owner cannot confiscate a TLD from its owner. Factory owner can only set a royalty in the TLD contract and nothing else.

### Domains

A domain can only be held by one address, but one address can hold many domains.

A domain can hold many pieces of data:

- The holder's address (by default).
- Profile picture (an NFT that the user owns).
- URL (like user's homepage or similar; this comes handy together with the Punk Domains browser plugin).
- Other custom data such as a Twitter handle, description, etc.

All the data is stored on-chain. Each domain is an ERC-721 NFT and can be sold on NFT marketplaces.

### Additional resources

- [Docs](http://docs.punk.domains/)
- [GitHub](https://github.com/punk-domains)
- [Discord](https://discord.gg/8dSrwrAQeu)
- [Twitter](https://twitter.com/PunkDomains)
