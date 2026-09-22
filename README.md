# DNHDD Longitudinal Official Data

A research-ready workbook of official economic, social, fiscal, infrastructure, environmental, policy, parliamentary, scheme, transport, tax and CSR data for **Dadra and Nagar Haveli and Daman and Diu (DNHDD)**.

**Version:** 1.0.0  
**Release date:** 22 September 2026  
**Data file:** [DNHDD_Longitudinal_Official_Data.xlsx](./DNHDD_Longitudinal_Official_Data.xlsx)  
**SHA-256:** `5c48d5dcb05184dfaa0b2fe8e62059b74d52d9126d0b074981e014493159570c`

## Scope

The workbook consolidates the maximum usable time span available from official sources while retaining source-specific vintages, units, geographies and methodological notes. It covers the merged Union Territory and, where official series permit, the legacy and district geographies of Dadra and Nagar Haveli, Daman and Diu.

The dataset is intended for empirical economic and public-policy research, descriptive analysis, replication, teaching and evidence-based reporting. It does not replace the underlying official publications.

## Workbook structure

| Sheet | Contents |
|---|---|
| `Overview` | Scope, coverage, conventions and headline inventory |
| `Master Data` | Harmonised long-form observation table with provenance fields |
| `Macro and Industry` | Macroeconomic and registered-manufacturing indicators |
| `VAHAN` | Vehicle-registration series |
| `NFHS6` | NFHS-6 health and demographic indicators |
| `NITI Indices` | NITI Aayog index observations and components |
| `Schemes` | Selected central-scheme implementation indicators |
| `Parliament` | Lok Sabha and Rajya Sabha question evidence |
| `Policy Register` | Policy and regulatory instruments with status notes |
| `Sources` | Source register and links |
| `Data Dictionary` | Field definitions and conventions |
| `Direct Taxes` | Direct-tax time series and applicability notes |
| `Scheme Metrics 2` | Additional ministry-dashboard metrics |
| `DMEO Inventory` | Inventory of central-government monitoring dashboards |
| `CSR Transactions` | Cleaned CSR transaction-level extract |
| `CSR Portal Directory` | CSR portal project/organisation directory |
| `CSR Analysis` | Linked CSR summaries and diagnostics |
| `2026 Update Notes` | Latest additions, caveats and unresolved gaps |

## Construction and provenance

- Priority is given to Government of India, Union Territory Administration and Reserve Bank of India publications and dashboards.
- Original reported values are retained. Labels and geography names are harmonised for analysis without silently changing substantive definitions.
- Each series preserves its unit, period, geography, source organisation, source title or URL, vintage and relevant methodological note where available.
- Missing observations are not treated as zero. Earlier gaps are not interpolated unless a sheet explicitly records a derivation.
- Pre-merger and post-merger observations should be compared only after checking the recorded geography and methodology fields.
- Administrative dashboard values may be revised by the publishing authority after this release.

## Citation

Suggested citation:

> Sharma, Ranveer. 2026. *DNHDD Longitudinal Official Data*. Version 1.0.0. GitHub dataset. https://github.com/alwaysaccessible/dnhdd-longitudinal-official-data

BibTeX:

```bibtex
@dataset{sharma2026dnhdd,
  author    = {Sharma, Ranveer},
  title     = {DNHDD Longitudinal Official Data},
  year      = {2026},
  version   = {1.0.0},
  publisher = {GitHub},
  url       = {https://github.com/alwaysaccessible/dnhdd-longitudinal-official-data}
}
```

When using a particular indicator, also cite the original official source recorded in the workbook.

## Reproducibility and versioning

Releases are versioned. Analyses should record the release tag and workbook checksum. Corrections to source transcription, geography concordance or metadata will be documented in subsequent releases rather than silently replacing the research record.

## Rights and source terms

The underlying observations remain subject to the terms of their respective official publishers. This repository adds compilation, cleaning, concordance and documentation; users should preserve source attribution and review the cited source terms before redistribution.

## Limitations

Series differ in reference periods, definitions, revision policies and geographic coverage. A merged-UT total is not automatically comparable with a historical district value. Scheme and administrative data measure recorded implementation, not necessarily outcomes or economic incidence. Consult the sheet-level notes, source register and data dictionary before estimation.

## Issues and corrections

Please use the repository's Issues page to report a suspected transcription error, broken source link, revised official value or comparability concern. Include the sheet, record or indicator, period, and official source.
