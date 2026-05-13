# Kirimana

**Open source AI-native data contract platform.**

Kirimana lets data engineers and data architects turn ODCS v3 data contracts
into compiled, runnable workflows across Databricks, Microsoft Fabric, Trino,
DuckDB and other SQL-bearing platforms — with AI policy gating built in from
the first line.

🌐 **Website:** [kirimana.io](https://kirimana.io)
📖 **Standard:** Built on [ODCS v3](https://bitol-io.github.io/open-data-contract-standard/) (Bitol / Linux Foundation AI & Data)
⚖️ **Licence:** Apache-2.0
🏛️ **Steward:** David Barton Consulting AB (Sweden)

## Status

Kirimana is in **private preview (v0.9)** as of 2026. Source repositories will
be made public alongside the v1.0 release, targeted for H2 2026.

If you'd like early access as a design partner, please reach out via
[kirimana.io](https://kirimana.io).

## What you'll find here when we go public

- `kirimana/kirimana` — core engine, adapters, CLI, AI Gateway
- `kirimana/web` — governance UI and BFF API
- `kirimana/contracts-spec` — our extensions to ODCS v3 (incl. `ai_policy`,
  currently proposed to the Bitol working group)
- `kirimana/skills` — Claude Code / agent workflows
- ADRs documenting every architectural decision

## Governance

Kirimana is stewarded by David Barton Consulting AB (Sweden) and developed
in the open under Apache-2.0. We're pursuing a long-term path toward
donation to a neutral foundation — likely Linux Foundation AI & Data,
the same home as the ODCS / Bitol standard.

Until then: no CLA, DCO sign-off only, trademark policy published with v1.0.
