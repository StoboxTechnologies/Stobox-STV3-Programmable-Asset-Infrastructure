# Unreleased

All notable changes since v1.5.0 (December 11, 2025) will be documented here.

---

## Added

### StoboxProtocolSTV3
- 2026-01-06: PurchaseFacet v1.2.0 — added `refundPurchase` function (7 selectors) (commit: 7874c15)
- 2026-01-13: MonetaryFacet v1.6.0 — added `setMaxSupply`, `totalIssued` functions (11 selectors) (commit: d4705f7)

### StoboxRWAVaultFactory
- 2026-01-06: Added `1_8_0_STV3Pack` with 7 facets (commit: b136acc)
  - DiamondCutFacet, DiamondLoupeFacet
  - RolesFacet, ValidationFacet v1.1.0, LockupsFacet v1.0.0
  - MonetaryFacet v1.5.0, PurchaseFacet v1.2.0
- 2026-01-06: Token version to create: v1.8.0
- 2026-01-13: Added `1_9_0_STV3Pack` with MonetaryFacet v1.6.0
- 2026-01-13: Token version to create: v1.9.0
- 2026-01-13: STV3TokenManagementFacet v1.4.0 — added `setMaxSupplyForSTV3Token` (12+1 selectors) (commit: bff2391)

### ST4RWAOfferingRegistry
- 2026-01-14: OfferingGovernanceFacet v1.4.0 — added `preMintOfferingCreate` function (11+1 selectors) (commit: f3ebe37)

## Changed

## Fixed

---

## Deployment Log

| Date | Component | Commit | Description |
|------|-----------|--------|-------------|
| 2026-01-14 | Offering Registry | f3ebe37 | OfferingGovernanceFacet v1.4.0 |
| 2026-01-13 | Vault Factory | bff2391 | STV3TokenManagementFacet v1.4.0, 1_9_0_STV3Pack |
| 2026-01-13 | Protocol STV3 | d4705f7 | MonetaryFacet v1.6.0 |
| 2026-01-06 | Vault Factory | b136acc | 1_8_0_STV3Pack, token v1.8.0 |
| 2026-01-06 | Protocol STV3 | 7874c15 | PurchaseFacet v1.2.0 |

---

## Facet Versions Summary

| Facet | Version | Selectors | New Functions |
|-------|---------|-----------|---------------|
| PurchaseFacet | v1.2.0 | 7 | `refundPurchase` |
| MonetaryFacet | v1.6.0 | 11 | `setMaxSupply`, `totalIssued` |
| STV3TokenManagementFacet | v1.4.0 | 13 | `setMaxSupplyForSTV3Token` |
| OfferingGovernanceFacet | v1.4.0 | 12 | `preMintOfferingCreate` |

---

## Current Component Versions (v1.5.3)

| Component | Version |
|-----------|---------|
| StoboxRWAVaultFactory | 1.0.8 |
| StoboxProtocolSTV3 | 1.9.0 |
| ST4RWAOfferingRegistry | 1.0.5 |
| StoboxDID | 0.1 |
