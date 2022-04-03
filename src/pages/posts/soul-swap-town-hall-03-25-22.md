---
setup: |
    import Layout from '../../layouts/BlogPost.astro'
project: Soul Swap
title: Soul Swap Town Hall 03.25.22
publishDate: 27 Mar 2022
author: difool0x
twitterUrl: https://twitter.com/difool0x
description: Record breaking protocol owned liquidity and tons of new features and updates! Get the download on this week's Soul Swap town hall!
logo: /assets/logos/soul-swap.png
---

### What are all the tokens in the SoulSwap ecosystem?

-   Soul (SOUL)
-   Seance (SEANCE)
-   Luxor (LUX)
-   Lumen (LUM)
-   Wrapped Lumen (WLUM)

On the SoulSwap side there is SOUL and SEANCE. SEANCE only applies when doing manual staking. SEANCE is a receipt token so you can retrieve SOUL when staked and want to get it back. SEANCE does not apply to new auto vault.

On the Luxor side there is LUX and SOR. You can stake LUX in exchange for rewards in LUM. LUM can be wrapped to mint WLUM (wrapped Lumen). SOR is our new algorithmic stable coin.

Wrapping LUM gives you the benefit of the rebase without creating a tax event by giving you more of that token. It works with a ratio. The ratio decides how much LUM each wrapped LUM is worth. Wrapped LUM is worth more and more LUM over time.

### Record Breaking Protocol Owned Liquidity

Goal is to build a sustainble exchange by acquiring Protocol Owned Liquidity (POL).
Team is doing different things to acquire liquidity for long term:

-   Bonds
-   Buyback & burn (BAB)
-   Accumulating SOUL / FTM liquidity

BAB happening every day in order to accumulate more SOUL. Part of BAB goes to purchasing SOUL and pairing it with FTM, then giving that liquidity to the DAO. Thus the DAO is always accummlating SOUL / FTM pair liquidity. Based off of transaction fees from swaps that invovle ecosystem tokens (SOUL, SEANCE, LUX, LUM, wLUM).

Record braking POL, going higher and higher...

-   51% POL on SOUL side
-   16% on LUXOR side
-   Total of 67% total POL

Effectively 2/3 exchange liquidity is owned by protocol. Which means that if every user decides to quite, the worst impact would be 1/3 of liquidity.

Although TVL is lower vs other projects, what is beenficial is we have reassurance of knowing that this is our floor. The lowest liquidity that we can expect to have is the amount of liquidity that protocol owns. In USD as of today is $1.5m POL, which can fluctuate based on price of assets.

BAB transaction can be seen in the pinned post, the last tweet made for announcing each town hall. This burn was for 11,800 SOUL and can be seen here:

[Proof of Burn](https://ftmscan.com/tx/0xc0d074220f420ffff8ccd0d747dfee7a2388901343049722d74ff51da1e488d1)

### New Features

A number of new features were added this week:

-   Auto vault
-   Luxor Dashboard
-   Drop down menus
-   Sidebar menu

### Auto Vault

Now able to stake SOUL to accumulate more SOUL whereby the SOUL is harvested and then reallocated. This way every time someone interacts with contract they are helping you by enabling you to reinvest your harest. This powers a higher return on this pool vs farms. There is about 170% difference between these two options at the moment.

The "Downside" is that you dont get SEANCE for particpating in the auto vault. With Luxor your able to do a number of other things, which makes that a nice option to have. However, some people aren't very interested in SEANCE.

This allows them to have exposure to returns without having to deal with SEANCE. Remeber you need to have SEANCE in order to unstake SOUL from the traditional manual vault.

### Luxor Dashboard

You are now able to view all the key metrics for Luxor easily accessbile on SoulSwap interface. Find it via Luxor dropdown or via the sidebar (both new features on onterface) and click on "Overview".

Luxor has a yellow sun icon, click on Overview with dropdown, you'll see overview of Luxor economy, incuding marketcap, backing price, supply, emissions rate, Luxor price, protocol balance from treasury and distribution of that in terms of how much of the treasury is composed of liquidty vs reserves vs investments.

Also you ahve access to marketcap price and supply for SOR, as well as underlying collateral distribution.

What is interesting is that SOR has consistently been above peg price of $1, currently sitting at $1.03 per SOR.

Additionally, you have information for wrapped Lumens. Ratio tells you how much Luxor each wrapped Lum is worth. Again, wrapped Lumen increases your exposure to Lumen without increasing your Lumen balance. It is a virtual way of accounting.

### In-progress Updates

-   Atomic trades
-   Algorithmic live auctions
-   Luxor staking on SoulSwap frontend
-   Cross-chain exchange
-   Documentation updates
-   Medium article
-   SOR staking

Atomic trades are fully tested and optimized, so it costs signigicantly less gas.

Finished algorithmic live auctions. Something like Tombheads, but an automated version. Still needs testing. Finished recently, also optimized.

Thinking of a fully automated version as well. Current version is manual where someone becomes auctioneer, can add themselves and create auction room. People can put NFTs in that room, where the auctioneer chooses which ones to add. Don't think anyone has done yet. Definetely community driven. Without community doesnt work.

There is now the ability to stake LUX on SoulSwap frontend. Only a few more things needed to add on to that frontend, includes wrapping process, have wrapping on there so that you dont have to leave experience, and also ability to claim any tokens that were once in warm up contract.

So there's a warm up period of 21 rebases, effecitvley 7 days. Have to wait 7 days to withdraw and have additional rewards. This is reflected on frontend, only thing thats inaccesssible now is abilty to claim or forfeit those rewards. Will make that extrmely easy.

Also working on cross-chain dex, enable us to execute trades from one chain to another. Able to be on Fantom and execute trade that is ETH from Fantom to AVAX on Avalanche, or FTM on Fantom to UNI token on Ethereum, etc.

Working on documentation updates. Adding new features to docs and integrating them into SoulSwap frontend so that you don't have to leave page when reading the "How-tos". These are mini tutorials for new users. Only downside is it takes you off site. Going to have these integrated to the UI.

Medium article coming out next week will go into depth about all the new features that are included with SoulSwap incuding auto staking contract, as well as SOR and its utility.

SOR staking opportunity coming so that you can use SOR to stake and recieve rewards. Has yet to be determined in terms of exact mechanisms used for that rewarding process. Includes the token rewards, if DAI, FTM or LUX. Also might be some external requirements such as requiring certain amount to stake or hold certain amount of LUM.

Also have ability to interact with SOR stable coin. Accessible via [soul.sh/luxor/sor](soul.sh/luxor/sor). You can to mint, redeem, and claim. All fees associated go direclty to LUXOR treasury, which adds to reserves, which increases price for Luxor token.

Essentially When you mint SOR with DAI, the contract automatically purchases LUX off the market, in order to have layer of backing for SOR.

20% of SOR's backing is in Luxor. Can see that visually by accessing the Luxor dashboard, will show you what % of SOR token is backed by each of these aspects, DAI, Luxor, SOR collateral.

Will be laid out more clearly in upcoming article. Articles will also be integrated in frontend.

Also will be updates to Luxor in contracts for the bonds, includes features such as auto compounding, boosted dicount options, and a rising price floor that will enable Luxor to be worth a valuation greater than $1 each, instead a diff number determined very soon.
