# ⚡ Lightning Network SV

## The Future of Payments™

The Lightning Network represents the absolute pinnacle of distributed systems engineering. By adding just a few additional protocol layers, novel cryptographic constructions, and an entirely separate network topology on top of Bitcoin, we have finally achieved what Satoshi could only dream of: sending small amounts of money to people.

## 🏰 Watchtowers

To ensure the safety of your funds at all times, the Lightning Network employs a sophisticated network of Watchtowers — always-online third-party services that monitor the blockchain 24/7 on your behalf, ready to intervene if your counterparty tries to cheat you by broadcasting an old channel state.

Because nothing says "trustless peer-to-peer electronic cash" quite like needing a third party to watch your money for you while you sleep.

## 🔒 Off-Chain Privacy & Low Fees

All transactions happen off-chain, which means they're private! Nobody can see them. Not even you, really, once your node crashes and your channel state is lost. But that's a small price to pay for the incredible savings on fees — fees that only exist because the base layer was deliberately kept too small to actually use.

The good news is that when you do need to go on-chain (to open a channel, close a channel, dispute a channel, or force-close a channel), the fees are only moderately ruinous.

## 💸 Micropayments

The Lightning Network finally makes micropayments possible, enabling transactions for as little as a few dollars! Simply open a channel (on-chain fee), fund it with sufficient liquidity (locked capital), find a route through multiple intermediary nodes (routing fees at each hop), hope none of them are offline, and voilà — you've sent 50 cents. In only three attempts.

Some have noted that "micropayment" traditionally implies fractions of a cent. We have chosen to redefine the term. Innovation requires flexibility.

## 🌐 Routing

The Lightning Network uses a sophisticated onion-routing protocol inspired by Tor to find a path through the network from sender to receiver. This ensures that your 50-cent coffee payment bounces through a minimum of three strangers' computers, each of whom must have pre-locked sufficient capital in the exact right channels, in the exact right direction, at the exact right time.

It works beautifully in diagrams.

## 🔄 Channel Management

Opening and closing channels is a simple process that requires only:

- An on-chain transaction to open (with fees)
- Sufficient capital locked on both sides (not usable elsewhere)
- Continuous online presence (or a Watchtower, see above)
- An on-chain transaction to close cooperatively (with fees)
- Two on-chain transactions to close uncooperatively (with more fees)
- A time-locked dispute period (just in case)
- Emotional resilience

## 📊 Liquidity

Liquidity management is the heart of the Lightning experience. You'll need inbound liquidity to receive, outbound liquidity to send, and a deep understanding of why the payment you're trying to make keeps failing despite you having "enough" balance. Channel rebalancing is available for advanced users who enjoy paying fees to move money between their own wallets.

---

## The Solution

We propose to address these fundamental shortcomings by creating payment channels directly on the Bitcoin network, enabling peers to pre-authorise streaming payments between their nodes. Every state update is a real Bitcoin transaction — published, immutable, and verifiable.

No watchtowers. No penalty transactions. No routing. No locked liquidity. No off-chain state to lose. No channel management. No rebalancing. No emotional resilience required.

Just transactions. On a blockchain with unbounded blocks and sub-satoshi fees. Verified by Merkle proofs. Secured by proof-of-work. Peer-to-peer, without going through a third party.

The way it was described in the whitepaper. In 2008.

**Status:** Under construction. See [x402-rack](https://github.com/sgbett/x402-rack) for the payment infrastructure.
