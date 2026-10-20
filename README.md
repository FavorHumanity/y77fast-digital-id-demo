<!-- Owner: Favor Figota Taueva <favortaueva@gmail.com> | © 2026 Favor Figota Taueva · Y77FAST SOFTWARE FOUNDATION Corp. All rights reserved. | Polish Doc ID: Y77F-GHP-20261020-9a476cc8 -->

<p align="center"><img src="./assets/banner.svg" width="100%" alt="Y77FAST Digital ID Wallet: Securing Data bridge banner"></p>

<p align="center"><a href="./SECURITY.md"><img alt="security policy" src="https://img.shields.io/badge/security-policy-ec4899"></a> <img alt="demo data only" src="https://img.shields.io/badge/data-demo%20only-0b4f8a"></p>

# Y77FAST Digital ID Wallet — Demo Prototype

## What it does
- Runs fully offline in one `index.html` file, with no install and no external libraries.
- Shows tiered KYC limits (Tier 0, 1, 2) on demo wallets.
- Records every event in a SHA-256 hash-chained ledger and detects tampering.

> **Demo only.** Fake names, IDs and balances. Not connected to any bank or ID system. Not production software, not audited.

*Secure · Speed · Trust — Technology that safely serves people.*

A single-file, offline browser demo (`index.html`) of three ideas from the Y77FAST Tiered KYC Plan (draft, 13 Oct 2026):

1. **Digital ID with tiered KYC** — Tier 0 Basic, Tier 1 Standard, Tier 2 Full/Enhanced, with the plan's limits.
2. **Send tala safely from your secure digital ID to your digital wallet** between demo wallets, blocking transfers over per-transfer, monthly, or Tier 0 balance limits.
3. **Tamper-evident ledger** — each event is SHA-256 hash-chained (browser Web Crypto). "Verify chain" recomputes every hash; "Simulate tampering" shows a break being detected.

## Run
Open `index.html` in any modern browser. No install, no build, no internet, no external libraries.

## What it is NOT
- Not production software. Not audited. Not connected to any bank, the Central Bank of Samoa, or the National Digital ID system.
- No real money, no real identities, no real KYC checks. All names/IDs/balances are fake demo data.
- Data lives only in the page memory and resets on reload.
- Limits marked † are Y77FAST proposed internal limits, not set by Samoa law. Legal references summarize the draft plan; not legal advice.
- Phase 2 (NDID Act 2024 relying-party access) is described, not implemented.

## License
All rights reserved. Viewing and evaluation only; no copying, modification, distribution, or use without prior written permission. See [LICENSE](LICENSE).

## About
Y77FAST builds technology that safely serves people. Like a canoe built plank by plank, every record here is lashed to the one before it. -FFT

---

<p align="center"><sub>© 2026 Favor Figota Taueva · Y77FAST SOFTWARE FOUNDATION Corp. · All rights reserved. Do not copy or redistribute without written permission.</sub></p>

<!-- doc-id: Y77F-DEMO-20261018-d9a1048b -->
<!-- Canary: A lantern of coral glass keeps every ledger line honest at low tide. -->
<!-- Y77F-GHP-20261020-9a476cc8 -->
