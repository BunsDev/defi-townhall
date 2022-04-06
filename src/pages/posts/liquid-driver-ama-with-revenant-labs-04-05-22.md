---
setup: |
    import Layout from '../../layouts/BlogPost.astro'
project: Liquid Driver
title: Liquid Driver AMA with Revenant Labs 04.05.22
publishDate: 06 Apr 2022
author: JacksWiths
twitterUrl: https://twitter.com/JacksWiths
description: The Revenant Labs team joined the Liquid Driver Pirates for a great AMA! Get the alpha in this brief recap by community member JacksWiths. Audited by NJRedDot.
logo: /assets/logos/liquid-driver.png
---

The Revenant Labs / Credit team joined the Liquid Driver Pirates for a short but great AMA!
Recording is available <a href="https://odysee.com/@LiquidDriver" target="_blank">here</a> and below a brief recap:

#### The past

After a sad exploit that affected @RevenantLabs (StakeSteak at the time), the team decided to keep working for their goal. They decided to make it up to their users by distributing tokens that grants a share of any new project tokens developed by them.

#### Creditum

You deposit your assets and can mint $cUSD. The strategy is to make cUSD being what $fUSD was meant to be : you can lock your assets and mint a stable to keep your money working. It’ll mostly stay on #FTM ecosystem.

#### Singularity

Was the main topic of the conversation; as they just released their highly awaited <a href="https://revenant-labs.medium.com/what-is-singularity-fa1294f7e640" target="_blank">medium article</a> (for the high level explanation) and <a href="https://docs.revenantlabs.io/singularity/" target="_blank">doc</a> (for technical details) the previous day.

**tldr?**

#### The Goal

Create an alternative AMM to offer very low slippage/fees based on a strong oracle feed, which doesn’t exist yet on #FTM. Also implementing a single asset liquidity provider position to eliminate impermanent loss.

#### The Idea

Got inspired by @Platypusdefi and there recently launched stableswap platform on #Avalanche. After working on the concept and multiple exchanges, Revenant Labs decided to improve this model so it can be used with volatile assets.

#### The Model

Individual liquidity pools are divided into tranches, allowing to swap any asset within them. Each pool has a collateralization ratio and deposit/withdrawal fees are adjusted based on it to maintain healthy pools. That fee also prevents some exploits. Only few millions of TVL for each traded asset should be enough to ensure that on most of the trades

#### What’s in it for the liquidity provider?

When depositing, you’ll receive an interest bearing token. The pool being single sided, you won’t suffer impermanent loss on your asset.

#### What’s in it for the swapper?

As usual, the bigger the swap, the bigger the slippage. Although, it is expected to be even lower than with Curve Finance. The fees are expected to be among the lowest on Fantom, with a cap at 0.15%

#### What about competitiors?

Will not be a competitor to usual DEX as @SpookySwap, @Spirit_Swap, @beethoven_x or @ProtoFiProtocol because it won’t be able to offer swaps on every token, as it is based on oracle feeds. Would work only for a high volume of coins.

#### How about Oracle and safety?

Actually in talks with chainlink to reduce the tolerance with higher frequency feed than 27s, that may not prove to be enough for volatile assets.Singularity will also be fed using CEX pricing. The team is actively working on their own oracle.

#### Oracle risk mitigation

Because of that necessary security, only the team will be able to add new assets. If the oracle isn’t accurate, there is an arbitrage risk. During the beta period (starting this week), the team will closely monitor those. Dummy tokens will be used.

#### What after the beta?

On official launch, the contract will be immutable. No risk for users that the team changes them on the way down. Hence the time taken to make it all perfect beforehand. The team members assure they’ll provide some of the initial liquidity themselves.

#### What about token emissions?

There is no emission planned right now. The release of a token isn’t the main priority. (welcome $RVNT) One point being, the team doesn’t want any aping before everything works smoothly.

The most important being to make the protocol as secure as possible in the first time. When time will come, it will most likely include a fee capturing system. Be patient, and use the product for what it is!

#### The economic vision

The @RevenantLabs team plans to build on the foundation of $cUSD and Singularity in the future. Many more projects to come, complementing each other to the benefit of an organic growth for the Revenant ecosystem. You like puzzles? I do. $cUSD will be paired with most stable pairs in order to let it grow as it deserves !

#### The educational vision

A big focus will be put on educational content for all levels (from who discovers DeFi to who’s an expert at it) by the use of podcasts, articles, and games proposed to the community. Participation will be incentivized, and more even sharing knowledge.

#### The means

In order to achieve that, the team is currently expanding with a few new members joining recently, bringing it to a total of 10. There will be more coordination and specialization among them.

The $LQDR pirates were really happy to host the first AMA about Singularity and wish the wind will blow the right way!

PS: thanks to NJRedDot for reading & correcting what I misunderstood!
