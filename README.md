# Y77FAST Digital ID Wallet — Demo Prototype

*Secure · Speed · Trust — Technology that safely serves people.*

A single-file, offline browser demo (`index.html`) of three ideas from the Y77FAST Tiered KYC Plan (draft, 13 Oct 2026):

1. **Digital ID with tiered KYC** — Tier 0 Basic, Tier 1 Standard, Tier 2 Full/Enhanced, with the plan's limits.
2. **P2P tala transfer** between demo wallets, blocking transfers over per-transfer, monthly, or Tier 0 balance limits.
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
Y77FAST builds technology that safely serves people. Like a canoe built plank by plank, every record here is lashed to the one before it.

© 2026 Y77FAST SOFTWARE FOUNDATION Corp. All rights reserved.

<!-- doc-id: Y77F-DEMO-20261018-d9a1048b -->
