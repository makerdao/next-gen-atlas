# AEP-4: Ensuring Equal Treatment of DAI & USDS Holders

## Preamble

```
AEP#: 4
Author(s): GFX Labs
Contributors:
Status: Rejected-Misaligned
Date Proposed: 2025-02-13
Date Ratified:
Forum URL: https://forum.sky.money/t/aep-3-ensuring-equal-treatment-of-dai-usds-holders/25983
```

## Motivation

Because it is both bad business and poor user experience to do otherwise, this proposal updates the Atlas to ensure DAI holders are treated *pari passu* with USDS holders. This is mostly the case in borrow rates and collateralization ratios, leaving primarily the Savings Rate to be corrected.

## Edited Atlas Documents

Sections shall be amended as below (changes in **bold** or strikethrough):

Section A.3.2.2.2
The ~~Dai~~ Savings Rate (”~~D~~SR”) is the rate ~~Dai holders~~ users can earn on their Dai **or USDS** in the Dai Savings Rate **and Sky Savings Rate** smart contracts.

**Section A.3.2.2.2.1**
**The yield offered to users through savings rate modules must always treat USDS and DAI users equally. This does not prohibit temporary marketing rewards or subsidies that are delivered outside the savings rate modules.**

~~Section A.3.2.2.3
The Sky Savings Rate (”SSR”) is the rate USDS holders can earn on their USDS in the Sky Savings Rate smart contracts.~~

~~Section A.3.2.2.3.1
The Sky Savings Rate is determined based on the Dai Savings Rate and the USDS Spread parameter using the following formula:Sky Savings Rate = Dai Savings Rate + USDS Spread~~

~~Section A.3.2.2.3.2
The current value of the USDS Spread is 1%.~~

## Pull Request of Edits

TBD
