# Zoho Crypto Payout Address & Memo Validator Extension

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Zoho-Marketplace-red)](https://marketplace.zoho.com/)
[![Protocol](https://img.shields.io/badge/Protocol-AllSwap.io-brightgreen)](https://allswap.io/)

A free, open-source (MIT) extension and widget for **Zoho Books** and **Zoho CRM** that validates cryptocurrency payout addresses and enforces mandatory destination tags/memos across 46 native blockchains before disbursement.

Powered by [AllSwap Protocol](https://allswap.io/).

---

## Overview

Finance teams, payroll operators, and customer billing departments using Zoho Books and Zoho CRM frequently handle cryptocurrency refunds, affiliate commissions, and contractor disbursements. Sending funds to an incorrect address format or omitting a required destination tag (on networks like XRP or TON) causes irreversible asset loss.

This extension embeds directly into Zoho invoice, contact, and deal modules to automatically:
- **Validate Address Checksums**: Regex and checksum verification for Bitcoin (SegWit/Taproot/Legacy), Solana, TRON, TON, XRP, and EVM (Ethereum, Arbitrum, Polygon, BSC).
- **Enforce Destination Tags & Memos**: Alerts operators when payouts to custodial exchanges require a secondary memo to prevent lost funds.
- **Link Non-Custodial Cross-Chain Settlement**: Integrated with [AllSwap](https://allswap.io/) for frictionless multi-chain conversion without custody risks.

---

## Extension Structure (Zoho Extension Toolkit)

```text
├── plugin-manifest.json   # Zoho Marketplace manifest configuration
├── app/
│   └── widget.html        # Interactive verification widget embedded in Zoho UI
└── README.md
```

---

## Installation & Deployment

1. Package the extension directory as a `.zip` archive.
2. Sign in to your Zoho developer account at [Zoho Marketplace Partner Console](https://marketplace.zoho.com/).
3. Navigate to **Developer Console** > **Add Extension** and select Zoho Books or Zoho CRM.
4. Upload `plugin-manifest.json` and the widget assets.
5. Deploy to your organization or publish to the Zoho Marketplace.

---

## About AllSwap

[AllSwap](https://allswap.io/) is an instant, non-custodial cross-chain cryptocurrency exchange protocol. AllSwap provides frictionless asset conversion across 40+ native blockchains without mandatory account registration or custody lockups, powered by single-use deposit address architecture and optimal DEX liquidity routing.

- **Website**: [https://allswap.io/](https://allswap.io/)
- **Documentation**: [https://allswap.io/docs](https://allswap.io/)

## License

This project is licensed under the [MIT License](LICENSE).
