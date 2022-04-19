---
setup: |
    import Layout from '../../layouts/BlogPost.astro'
project: Byte Masons
title: Byte Masons AMA & the fBEETS Wars 04.12.22
publishDate: 18 Apr 2022
author: JacksWiths
twitterUrl: https://twitter.com/JacksWiths
description: Before the locking mechanism for fBEETS should is released, the @ByteMasons held an AMA to discuss their current strategy, and talk about the future. Coverage by JacksWiths.
logo: /assets/logos/byte-masons.jpeg
---

Few weeks before the locking mechanism for fBEETS should be released, the @ByteMasons held an AMA to discuss their current strategy, and talk about the future.

Featuring @Crypto*A_S @tess3rac7 @KevinBarker1111 @0xBebis* @bitSAMSoN and JJJJJJJJJ

@beluga_fi already started accumulating $BEETS, @Liquid_Driver is slowly leaking some alpha. Where does the @Reaper_Farm stand?

**Recording:** https://www.youtube.com/watch?v=DJicD6IAN8A

**Useful info:**

-   Website : https://www.bytemasons.com/
-   Docs : https://docs.reaper.farm/
-   Discord : https://discord.gg/9eac4wwb
-   Learn program : https://learn.bytemasons.com/
-   Soon on @defiwars\_

#### Goal

People to trust us with their fBEETS to have the best deal

#### General talk on the past

Till late 2020, emissions for @beethoven_x masterchief are decided by the committee.
In January, it was put to a vote to let fBEETS holders decide how to redirect 30% of the emissions, with a two week cycle.

It turned out in a biweekly bribe game so people would vote for your pool. There is a lot of creativity in that bribe game with some flat ones, some by % of votes, caps, floors, lottery, … It takes a lot for someone to keep track and make the best out of it, even if supported by the development of some tools like https://www.beetswars.live/

@ByteMason offered a way to ensure everyone that they would participate in the bribes in the most efficient way while compounding.

#### How it works

We accumulate all the voting power of the $fBEETS in the crypt, follow the bribes and calculate to maximize the bribes, to make it easier for you. We’re just acting as mercenaries. In the last round, we collected close to $100k.

In a permissionless way, all the bribes paid to the crypt are directly auto-compounded in more $fBEETS. The rffBEETS increases its ratio of held fBEETS when compounding. usually, the ratio grows by 0.1 a day, on bribe day it can be 0.3.

In order to not have people depositing after voting to benefit from both their vote and the crypt’s bribes while not being there, we now have to lock the crypt before what is likely to be the random snapshot.

#### The technical

The crypt itself cannot vote, we had to build a smart contract that could do it in a permissionless way, and be able to understand the bribe values proposed in different tokens and rules. We are using @FinanceFirebird to estimate that value for the trade.

#### Extra benefit

During the two weeks of auto compounding, and when bribe is paid, there is no taxable event for whomever is concerned. This is the inherent advantage of the simple rf Crypt receipts. Instead of the quantity increasing which could be considered a taxable event the value is paid directly to the receipt thus avoiding a taxable event. However ensure you speak with a financial or tax advisor for advice specific to your jurisdiction as this comment is general in nature.

#### In the future

There is the possibility of using $fBEETS power within the crypt for policy voting in order to bring the best return to the users. The @ByteMasons are looking into it, but did not commit to an idea yet. One of them would be to redirect the power to the users through a snapshot of the crypt.
But that won’t be rushed, as the goal is to maintain objectivity, and the priority is to capture the financial benefits for users while they have nothing to do for it.

#### Reaction to the upcoming locking

We are excited by it, and really happy.
@Reaper_Farm aim is to remain the best place in #FTM and #DeFi to auto-compound your gains. We plan to implement a system to allow our users to keep the same benefits from the rfFBEETS crypt as today despite the new locking challenge.
We cannot give details at this stage, but we’re working on it.

#### AMA section

Can we display the APY of the bribes? As the bribe is a one time event, it is hard to display its APR, but information will be available on the Discord.!

Beluga’s strategy seemed interesting, but really different. Rewards would be used to farm in pools instead of compounding. At this stage Reaper.Farm’s goal is to help maximize users turn fBEETS into more fBEETS.

**What’s your strategy to make locked fBEETS liquid?**

Brainstorming on this new fBEETS era. Seems like we have a plan. @tess3rac7 :

Hard to keep it for myself, you can imagine.” We will share something soon, not seen yet, or at least not at the scale we see it. Won’t confirm or decline any of your ideas!

**What’s your view on the security of the crypt?**

Lots of very robust contracts. As much as possible, we try to reduce the surface area for bugs. We review them internally by at least one engineer, with a security focus program and working with security bounty programs. Then we simulate real usage like deposit, withdrawal, etc. Even panic withdrawal to be sure everyone could withdraw at once. Better release later than skipping those steps.

**When locking starts, can you ensure it’ll stay 100% liquid?**

We’ll take time and effort to make it as liquid as possible. It’s just us against technical problems. Looking for the sweet spot between best APY and liquidity.

**Can you give power to vote on other proposals than the bribes?**

We focus on maintaining objectivity. Voting for a proposal leads to opinion. It’s a bit more challenging than the sole financial aspect, but thinking about it.

**Educational content broadly through Learn**

We will try to focus more on sharing our approach and strategies, using AMAs and other content to give users access to decision making or better understanding what is happening under the hood. We hear the outcry for developer or coding content. Expect more soon, with the upcoming new Learn Alpha v2.

What we do need is to ensure we keep close with the community. Ideally we could also get more input from the community about what is missing from Learn. Please join our discord!

Our goal would be to make everyone wiser and more knowledgeable on finance in general, but mostly in crypto and DeFi.

**Could you add a section with tutorials, some videos, “how to”, about how to use DeFi?**

Yes for sure, we know people learn best in different mediums. Expect more videos and audio features on the new version of Learn as we continue to scale our operation up. If you’re seeing a gap on Learn get in touch, we want you to share their years of experiences and help distribute the knowledge. With all the unique perspectives within our community we will all see problems differently, so we would love to hear from you. We need to find how to facilitate the moving of the herd together and helping less tech-proficient players enter the DeFi space.

Special thanks to @bitSAMSoN for the review. All the educational section is of his wording. Do not hesitate to contact him if you want to learn or bring knowledge to everyone !
