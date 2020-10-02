# The Firekeeper Saga

The Firekeeper Saga is a game where you can **win real money** by keeping your fire up longer than others.

* **[How to win?](#how-to-win)**
* **[How much can I win?](#how-much-can-i-win)**
* **[How much can I lose?](#how-much-can-i-lose)**

## How to play

1. [Start a fire](#how-to-start-a-fire).
1. [Add WOOD tokens](#how-to-add-wood-tokens) to keep your fire up (1000 WOOD tokens = 1 minute of fire).
1. [Invite your friends](#how-to-invite-friends) to add WOOD tokens (you will split the prize pool proportionately).
1. [Receive the prize](#how-to-receive-the-prize) if your fire is the longest one (not necessarily the last one).

## How to start a fire

1. [Open our website](#our-website).
1. Click "Start fire".
1. Click "Confirm".

## How to add WOOD tokens

1. [Open your fireplace](#your-fireplace).
1. Click "Add wood".
1. Choose the amount of WOOD tokens that you want to add.
1. Click "Add".
1. Click "Confirm".

## How to invite friends

1. [Open your fireplace](#your-fireplace).
1. Click "Invite friends".
1. Copy the link.
1. Send the link to your friends.

## How to receive the prize

1. [Open your fireplace](#your-fireplace).
1. Click "Receive the prize" (only available if your fire was the longest one).
1. Click "Confirm".
1. Receive the prize in ETH to your address (you will receive a share of the prize calculated as "Your added WOOD tokens / Total added WOOD tokens")

## How to win

* [How to win as a firestarter?](#how-to-win-as-a-firestarter)
* [How to win as a firekeeper?](#how-to-win-as-a-firekeeper)

NOTE: Firestarters receive 10% of the prize pool before it is distributed between team members. So they get paid twice: 10% of the prize pool + their share of the prize pool depending on how many WOOD tokens they added.

### How to win as a firestarter

* [Start a fire](#how-to-start-a-fire) (cost: some WOOD to keep your fire up before you attract new team members).
* [Invite friends](#how-to-invite-friends).
* Invite more team members using BitcoinTalk, Telegram groups, Twitter, etc...

*(we'll put more advice on how to attract team members)*

### How to win as a firekeeper

* Choose the strongest firestarter:
  * Criteria:
    * How well he communicates with you & other team members.
    * How many team members he has already attracted.
    * How good are his plans for attracting new team members.
  * Don't simply choose the longest-running fire, because it may blow out in future if the firekeeper is too weak to attract new team members.
* [Add WOOD tokens](#how-to-add-wood-tokens) to the fireplace of the firestarter.

Security: don't send tokens directly to the firestarter, always use [the official interface](#our-website) to add tokens to the fireplace.

## How much can I win

Example #1: You can win **855 ETH** (assuming the prize pool is **10000 ETH** and you contributed 10% of the fire pool - [see formula](#prize-pool-distribution))

Example #2: You can win **1710 ETH** (assuming the prize pool is **10000 ETH** and you contributed 20% of the fire pool - [see formula](#prize-pool-distribution))

Example #3: You can win **2660 ETH** (assuming the prize pool is **10000 ETH** and you started the fire & contributed 20% of the fire pool - [see formula](#prize-pool-distribution))

See also: **[How to play](#how-to-play)**

## Prize pool distribution

Example:

* We sell all wood tokens for 10000 ETH (prize pool).
* We give 500 ETH (5%) to game creators, leaving 9500 ETH (prize pool without fee).
* We give 950 ETH (10%) to winning firestarter, leaving 8550 ETH (prize pool for team members).
* We give 1710 ETH (20%) to a winning team member who contributed 20% of the winning fireplace (prize pool for individual team member).

Formula:

```
Pool = (how much we receive for selling all WOOD tokens)
GameCreatorFee = Pool * 1.05
WinningFirestarterFee = (Pool - GameCreatorFee) * 1.1
WinningTeamMemberFee = (Pool - GameCreatorFee - WinningFirestarterFee) * TeamMemberShare
```

NOTE: a firestarter who also contributed WOOD tokens to the fireplace gets both rewards (10% firestarter bonus + X% team member share, depending on how many WOOD tokens he contributes).

See also: **[How to play](#how-to-play)**

## How much can I lose

You can only lose the amount of money that you use to buy the WOOD tokens. You determine this amount yourself. Please play responsibly and don't invest more than you can afford to lose.

See also: **[How to play](#how-to-play)**

### How to start a fire on Etherscan

1. [Open our contract](#link-to-etherscan).
1. [Connect your wallet](#how-to-connect-your-wallet-on-etherscan).
1. Find "startFire" function.
1. Click "Write". 

## How to add WOOD tokens on Etherscan

1. [Open our contract](#link-to-etherscan).
1. [Connect your wallet](#how-to-connect-your-wallet-on-etherscan).
1. Find "addWood" function.
1. Input the "address":
   * If you are adding wood to your fire, then input your address
   * If you are adding wood to friend's fire, then input your friend's address (ask him/her)
1. Input the "amount": any amount that you want (fractional amounts are also supported & burned successfully)
1. Click "Write". 

## How to invite your friends on Etherscan

1. Send them a link to [our contract](#link-to-etherscan).
1. Ask them to [add WOOD tokens](#how-to-add-wood-tokens-on-etherscan) using your address

## How to receive the prize on Etherscan

1. [Open our contract](#link-to-etherscan).
1. [Connect your wallet](#how-to-connect-your-wallet-on-etherscan).
1. Find "finish" function.
1. Click "Write".

NOTE: the transaction will succeed only if there are no fires burning right now. 

## How to connect your wallet on Etherscan

1. [Open our contract](#link-to-etherscan).
1. Click "Connect to Web3" (under the "Contract" tab).
1. Choose your wallet.
1. Continue following the instructions on the screen. 

## Specification

* Symbol: WOOD
* Type: ERC-20
* Total supply: 100'000'000 WOOD
* Distribution: 1% airdrop + periodic sales on Uniswap

## Our website

We are currently working on a new website. Meanwhile, you can use Etherscan to play the game:

1. [Start a fire](#how-to-start-a-fire-on-etherscan) on Etherscan.
1. [Add WOOD tokens](#how-to-add-wood-tokens-on-etherscan) on Etherscan.
1. [Invite your friends](#how-to-invite-friends-on-etherscan) on Etherscan.
1. [Receive the prize](#how-to-receive-the-prize-on-etherscan) on Etherscan.
