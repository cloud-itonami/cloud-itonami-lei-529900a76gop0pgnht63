# cloud-itonami-lei-529900a76gop0pgnht63

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by 中部電力株式会社.**

This repository archives the publicly published Privacy Policy of **中部電力株式会社** (Chubu Electric Power Company, Inc.), with
source-url and retrieval-date provenance, per ADR-2607110300 (`cloud-itonami-lei-corporate-tos-catalog`,
`com-junkawasaki/root`). Read-only reference/archive repository — not a governed Advisor/Governor actor.

Part of the **worldwide-scope extension** of the cloud-itonami-lei catalog (batch JP-UTIL-1, 2026-07-19).

## Company identity

- **Legal name**: 中部電力株式会社 (Chubu Electric Power Company, Inc.)
- **LEI (ISO 17442)**: [529900A76GOP0PGNHT63](https://search.gleif.org/#/record/529900A76GOP0PGNHT63) (GLEIF entity-verified, JP)
- **Jurisdiction**: JP
- **Website**: https://www.chuden.co.jp
- **Ticker**: 9502 (TSE Prime)
- **ISIC Rev.5**: 3510

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of the archived Privacy Policy.
- `facts/catalog.edn` — live-checked public-register citations for this entity
  (GLEIF, 国税庁法人番号公表サイト, gBizINFO, and the issuer's own pages), with
  the honest wrinkles between those voices documented in the file header.
- `tools/verify_citations.cljk` — the gate for `facts/catalog.edn`: every row's
  URL must answer HTTP 2xx and carry its expected substring. Drift exits 1;
  "could not answer" (parse failure, zero checks, floor miss) exits 2, never 0.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Design rationale

See ADR-2607110300 and the worldwide-scope extension ledger (`2607110300-cloud-itonami-lei-corporate-tos-catalog.worldwide-progress.edn`) in `com-junkawasaki/root` (`90-docs/adr/`).
