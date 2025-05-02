# Oraichain Lottery by PanteraStaking

![PanteraStaking Logo](./panterastaking_logo.png)

## A Rewarding Experience for Our Delegators

At PanteraStaking, we believe in giving back to our community. The Oraichain Lottery is our way of thanking loyal delegators with additional rewards, creating an exciting incentive program that encourages long-term staking.

---

## How the Lottery Works

Our lottery employs a transparent, fair two-phase system designed to reward consistent delegators:

### Phase One: Eligibility Snapshot
- Each day/week (depending on frequency), we capture a snapshot of all eligible delegators
- Your address is included if you meet all eligibility requirements (see below)
- This creates a verifiable record of eligible participants

### Phase Two: Winner Selection
- Later in the same period, we check if you've maintained your stake
- A winner is randomly selected from accounts that remained eligible
- The winner receives a special reward without unstaking any tokens!

This two-phase approach ensures fairness by requiring participants to maintain their stake throughout the entire lottery period.

## Eligibility Requirements

To participate in the lottery, delegators must:

- Delegate at least **100 ORAI** to the PanteraStaking validator
- Maintain this delegation throughout the lottery period
- Not be currently blacklisted from a recent win
- Not be part of the permanent blacklist (see below)

## Blacklist Mechanism

Our lottery implements two types of blacklists to ensure fair distribution:

### Temporary Blacklist
- Winners are temporarily blacklisted for a set period (default: 7 days)
- This gives more delegators the opportunity to win over time
- Blacklisted delegators still earn normal staking rewards
- Blacklisted delegators' stakes contribute to the reward pool for other participants

### Permanent Blacklist
- Addresses from the Foundation Delegation Campaign (FDC) are permanently excluded
- This ensures rewards go to community delegators rather than foundation-related accounts
- The permanent blacklist helps maintain fairness for individual stakers

## Reward Calculation

Winning rewards come from a fascinating source: **commission from blacklisted delegators**!

Here's how it works:
1. We collect the commission earned from all blacklisted addresses
2. 50% of this commission goes to the lottery winner
3. The exact amount varies based on:
   - Total stake of blacklisted addresses
   - Current network APR (currently ~15%)
   - Validator commission rate (3%)

This creates a self-sustaining reward system where previous winners help fund future rewards.

## How to Participate

Participation is automatic for all eligible delegators! Simply:

1. Delegate at least 100 ORAI to PanteraStaking validator:
   `oraivaloper1uhcwtfntsvk8gpwfxltesyl4e28aalmq9v9z0x`
2. Maintain your delegation
3. Wait for the random drawing

No registration or additional steps required!

## Lottery Schedule

The lottery runs on two different frequencies:

- **Daily Lottery**: Smaller, more frequent rewards
- **Weekly Lottery**: Larger rewards drawn every Monday

Both lotteries follow the same eligibility rules and winner selection process.
As of today, the lottery is running only on a daily frequrncy.

## Why Delegate to PanteraStaking?

- **Extra Rewards**: Earn normal staking APR plus lottery opportunities
- **Fair System**: Two-phase verification ensures a level playing field
- **Transparency**: All lottery results published publicly in this repository
- **Community Focus**: We give back to our delegators
- **Professional Validation**: Secure, reliable validator with high uptime

## Recent Winners

Check the `latest_winner.json` file in this repository for our most recent lucky delegator!

---

*The Oraichain Lottery by PanteraStaking runs independently of the Oraichain network and is a validator initiative to reward our loyal delegators.*

*Questions? Visit [panterastaking.com](https://panterastaking.com) or contact us via [telegram](https://t.me/PanteraStaking_Official)*
