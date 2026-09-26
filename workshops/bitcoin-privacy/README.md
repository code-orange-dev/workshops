# Bitcoin Privacy Workshop

> Discover how private Bitcoin payments really are - and how to make them more private.

---

## Overview

The Bitcoin Privacy Workshop is a hands-on exploration of privacy tools and techniques in the Bitcoin ecosystem. Attendees learn by doing: sending Lightning payments across multiple hops, swapping to eCash, and testing how traceable (or untraceable) their transactions actually are.

**Format**: In-person + Online
**Frequency**: Monthly
**Locations**: Bitcoin House Bali + Discord
**Audience**: Intermediate Bitcoiners
**Cost**: Free

---

## What We Cover

### Lightning Privacy
- Sending Lightning payments through 3+ hops across different wallets
- Testing traceability: Blink → Wallet of Satoshi → Phoenix → destination
- Onion routing and path privacy: what each hop can and can't see
- What hops *don't* hide: custodial wallets (Wallet of Satoshi, Blink) see every payment you make, channel balances can be probed, and invoices can link payer and payee. Adding more hops through custodians adds more parties who see the payment
- BOLT12 offers and blinded paths: the receiver-privacy fixes in progress

### eCash (Cashu & Fedimint)
- How Cashu mints work - blind signatures for privacy
- Nutstash wallet setup and usage
- Fedimint federations - community-held funds. Blind signatures give strong privacy *from the guardians*, and the trade-off is custodial trust in the federation
- Setting up a Fedimint federation on Umbrel
- Sending eCash globally without a bank (tested: US, India, Lithuania, Australia, China)

### Privacy Tools in Practice
- Submarine swaps: on-chain → Lightning → eCash, and where each step can still leak (swap provider, timing, amounts)
- WhiteNoiseChat for encrypted communications
- Fedi app - private messaging + shared custody + mini apps
- Cypherpunk culture and philosophy

### Advanced Privacy
- Why privacy is a human right, not a crime
- Censorship resistance in practice
- Threat models for different user profiles
- Operational security basics

---

## Tools & Wallets Used

| Tool | Purpose |
|------|---------|
| Fedi | eCash, private messaging, federation management |
| Cashu / Nutstash | Bearer token eCash payments |
| Phoenix | Lightning wallet with privacy features |
| Blink | Lightning wallet |
| Wallet of Satoshi | Lightning wallet (custodial, for hop testing) |
| Umbrel | Self-hosted Fedimint federation node |
| WhiteNoiseChat | Encrypted communication |

---

## Event History

| Date | Location | Highlights |
|------|----------|------------|
| Jun 24-27, 2025 | Bitcoin House Bali | Cashu, Fedimint, Fedi workshop - cypherpunk culture |
| Jul 19-24, 2025 | Online (Discord) | Reading Club evolved into privacy workshop - submarine swaps |
| Oct 24, 2025 | Bitcoin House Bali | Tracked Lightning across 4 wallets - discovered 3-hop privacy |
| Nov 4, 2025 | Online (Discord) | Used Fedi eCash for completely private payment |
| Feb 25, 2026 | Online (Discord) | Sent Fedi eCash to 5 countries without a bank |
| Mar 21, 2026 | Online (Discord) | Monthly privacy/self-custody/censorship-resistance series launched |
| Apr 8, 2026 | Online (Discord) | eCash with Fedi, WhiteNoiseChat, Trezor, SeedSigner |

---

## Outcomes

- Attendees send their first Lightning payment and map what each party in the route could see
- Community runs a live Fedimint federation on Umbrel
- Featured in the **HRF AI and Individual Rights Newsletter**
- Slides open-sourced: [bitcoin-privacy-workshop-slides](https://github.com/code-orange-dev/bitcoin-privacy-workshop-slides)

---

## Run This Workshop in Your City

1. Download the slides: [GitHub](https://github.com/code-orange-dev/bitcoin-privacy-workshop-slides)
2. Pre-fund a Cashu mint or Fedimint federation for live demos
3. Have attendees install 2+ Lightning wallets before arriving
4. Live demo: send a payment through 3 wallets, then list what each wallet operator and hop learned. Custodians see everything, so don't present hops as anonymity
5. Budget 2 hours, works best with 5-15 attendees

## Go Deeper

Developers who want to build privacy tools can continue with [The Privacy Sessions](https://github.com/code-orange-dev/curriculum/tree/main/privacy-track): 12 biweekly drop-in sessions starting with Silent Payments, including dedicated Lightning privacy (S10) and ecash (S11) sessions.

---

*Code Orange Dev School | [codeorange.dev](https://codeorange.dev) | CC0 1.0 Universal*
