# Verified BIM benefit cases

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24496823.svg)](https://doi.org/10.5281/zenodo.24496823)

The dataset behind **[The Light Side of BIM: The Projects That Proved It Works](https://solebo.org/light-side-of-bim/)** (Ivan Shtaer, Solebo, 2026).

17 named construction and asset-management projects where a benefit attributable to building information modelling was actually measured — from the Kai Tak Sports Park roof in Hong Kong to the turnaround of a live LNG plant — with each figure rated by the strength of the source behind it.

| File | Format |
|---|---|
| `light-side-of-bim-cases.csv` | Flat table, one row per project |
| `light-side-of-bim-cases.json` | Same records plus dataset metadata and the evidence scale |

## Fields

`id`, `project`, `country`, `sector`, `client_owner`, `delivery`, `bim_tools`, `lifecycle_phase`, `benefit_type`, `measured_benefit`, `evidence_strength`, `evidence_basis`, `primary_source`, `caveat`, `source_article`, `source_url`

## Evidence scale

- **STRONG** — independent audit, government record, professional body, or peer-reviewed data with objective inputs.
- **MEDIUM+** — peer-reviewed or regulator-published, but a single self-reported case without a control.
- **MEDIUM** — named, verifiable project reported by a participant or relayed by trade press.

A figure's status never exceeds the strength of the source behind it.

## Companion

The other half of the ledger — audited overruns on the largest ISO 19650 projects: [iso-19650-megaprojects](https://github.com/ishtaer-max/iso-19650-megaprojects) · [The Dark Side of BIM](https://solebo.org/dark-side-of-bim/).

## Corrections

If you know a measured BIM benefit on a named project with a source strong enough to check, open an issue.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse freely, including commercially, as long as you credit the source.

## Cite

> Shtaer, I. (2026) *Verified BIM benefit cases* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24496823 — https://solebo.org/light-side-of-bim/
