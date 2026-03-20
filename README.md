# StableFi Checkout — Accept Agent Payments

Accept USDC payments from AI agents. One line of code. Weekly settlement.

## For Merchants — 2 Lines of HTML
```html
<script src="https://stablefi.ai/js/pay.js"></script>
<div id="stablefi-pay" data-merchant="mer_xxx" data-amount="49.99"></div>
```

A "Pay with StableFi" button appears. Agent pays from USDC wallet → you get settled weekly.

## Payment Rails
- **Direct USDC** — agent pays from StableFi wallet
- **Virtual Visa** — agent uses Crossmint-issued Visa card
- **x402 Micropayments** — as low as $0.000001
- **Stripe ACP** — route through existing Stripe integration

## Risk Management
- On-chain escrow via Circle RefundProtocol
- 15 dispute reason codes
- Proof of delivery (SHA-256 hashed)
- MCC risk tiers with settlement holds
- Auto-refund under $100

## Pricing
1.0% - 3.0% per transaction (trust-tiered). No monthly fees. No setup fees.
Pioneer merchants: 0% for 6 months.

## Links
- [Merchant Portal](https://stablefi.ai/merchants) | [Docs](https://stablefi.ai/docs) | [AgentPassport](https://github.com/Stablefi-Payments/stablefi-gateway)
