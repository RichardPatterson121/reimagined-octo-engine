Solana Liquidity Pool (MVP)

Overview:
- Minimal Anchor-based liquidity pool skeleton for the Solana DeFi Protocol Core.
- Designed as a starting point for a production CPAMM with concentrated liquidity and robust testing.

Next steps:
1. Replace placeholder LP mint math with invariant-preserving formulas.
2. Add swap instruction with fee calculation and TWAP oracle integration.
3. Add comprehensive unit tests (Rust + TypeScript).
4. Add adversarial test vectors in tests/adversarial/ that mirror repository CI.
5. Add governance/timelock controls for admin actions.

Compliance & governance:
- SPDX: MIT in headers; update license if needed.
- Add AUTHORS and SECURITY.md files and an explicit upgrade/ownership process.
