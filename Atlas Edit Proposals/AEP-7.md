# AEP-7: Securing MKR Holder Airdrop of SPK & Subsequent Stars

## Preamble

```
AEP#: 7
Author(s): GFX Labs
Contributors:
Status: Rejected-Misaligned
Date Proposed: 2025-02-18
Date Ratified:
Forum URL: https://forum.sky.money/t/aep-6-securing-mkr-holder-airdrop-of-spk-subsequent-stars/26010
```

## Motivation

This Atlas Edit Proposal aims to clarify for MKR holders their portion of Star tokens, 25%, and the vesting schedule through which they will receive them. No specific technical implementation is prescribed, allowing flexibility in implementation details.

MKR holders fund the development of the initial product a Star manages, MKR holders allocate funds or governance powers to the Star, and MKR holders deserve a stake in Stars after bearing that risk and outlay of resources. 

MKR holders have *conservatively* spent $5m and 2.4k MKR to develop the first likely Star, Spark, and have provided more than $1b in liquidity to SparkLend. MakerDAO (and later Sky) governance has acted in the role of venture capital, and tokenholders deserves a return on that investment in Spark and all subsequent Stars funded with governance capital and risk-sharing.

Simultaneously, the MKR holder vesting schedule is more conservative than the farming emissions schedule, preventing immediate selling by existing MKR holders relative to farmers. The net effect is a marginally slower rate of Star token inflation, because MKR holder vesting pushes some emissions further into the future in an effort to give MKR holders longer-term incentives. This also preserves the original intent for farming rewards to dominate emissions early in the Star's history, since they follow a halving-style emissions schedule.

## Edited Atlas Documents

Sections shall be amended as below (changes in **bold** or ~~strikethrough~~):

Section A.4.5
This Article governs the emissions of Star tokens. For the reward mechanisms that are multichain, the rate of distribution is balanced across each SkyLink destination deployment to attempt to target an equal Reward Rate per supplied USDS or Activated SKY.

Star Token Emissions:

The genesis emissions of Star Tokens happens over a period of 10 years, with half of the emissions happening in the first 2 years, and the emission rate halving every 2 years from then on. The Star Token genesis emissions are split across 3 types of recipients: USDS holders, SKY holders that Activate (no exit fee) and SKY holders that Seal (locks the SKY behind an exit fee). Each type of recipient share the total Star Token emission rate among their own type.

Year 1 and 2:
Total: ~~2~~ **1.375** billion Star Tokens/year.
USDS Token Rewards: 1.4 billion Star Tokens/year.
SKY Activation Rewards: 300 million Star Tokens/year.
SKY Seal Rewards: 300 million Star Tokens/year.

Year 3 and 4:
Total: ~~1 billion~~ **687.5 million** Star Tokens/year.
USDS Token Rewards: 700 million Star Tokens/year.
SKY Activation Rewards: 150 million Star Tokens/year.
SKY Seal Rewards: 150 million Star Tokens/year.

Year 5 and 6:
Total: ~~500~~ **343.75** million Star Tokens/year.
USDS Token Rewards: 350 million Star Tokens/year.
SKY Activation Rewards: 75 million Star Tokens/year.
SKY Seal Rewards: 75 million Star Tokens/year.

Year 7, 8, 9 and 10:
Total: ~~250~~ **171.875** million Star Tokens/year.
USDS Token Rewards: 175 million Star Tokens/year.
SKY Activation Rewards: 37.5 million Star Tokens/year.
SKY Seal Rewards: 37.5 million Star Tokens/year.

**MKR Holder Airdrop**

**MKR Holder Airdrop: 2.5 billion Star Tokens.**

**Addresses holding MKR, or having staked MKR in the governance contract, on the date of a Star token generation event are entitled to a pro-rata share of 2.5 billion Star Tokens. These tokens linearly vest over 10 years.**

Bootstrapping emissions:

Contributor token grants: 1 billion Star Tokens.

Contributor token grants are managed by Star governance controlled processes, subject to milestones and performance deliverables.

Liquidity bootstrapping: 1 billion Star Tokens.

Liquidity bootstrapping tokens are managed by Star governance controlled processes, subject to transparency and reporting of what is happening with the assets. After a finite period of time the liquidity bootstrapping program must be wound down and all remaining assets from the program must be returned to Star control.

## Pull Request of Edits

TBD
