# CGROM crosswalks, machine readable

The regulatory and framework crosswalks from Section 14 of the CGROM Open Edition v2.0, published as data so they can be used in other tools rather than read in a PDF.

- **134 mappings** across **17 sources**
- **19 references** covered in the summary table

Generated from the source that produced the published document, so the rows are identical to the PDF.

Published as a citable dataset: DOI [10.6084/m9.figshare.34963048](https://doi.org/10.6084/m9.figshare.34963048).

## Files

| File | What it holds |
| --- | --- |
| `crosswalks.csv` | One row per mapping. Long format, suitable for a spreadsheet, a database or a join. |
| `crosswalks.json` | The same mappings grouped by source, with the document metadata and the disclaimer attached. |
| `references.csv` | The summary table: each framework, rule or standard covered, its nature, and how deeply it is mapped in this edition. |

## Fields in `crosswalks.csv`

| Field | Meaning |
| --- | --- |
| `section` | Section number in the Open Edition v2.0, for example `14.8`. |
| `source` | The framework, rule or standard being mapped, for example `FTC Safeguards Rule, 16 C.F.R. Part 314`. |
| `requirement_ref` | The citation within that source, where the source numbers its requirements. Empty where it does not. |
| `requirement` | The requirement, category or criterion, in outline. |
| `cgrom_element` | The CGROM mechanism, section or capability that delivers it. Mechanisms are cited as `M1` to `M10`. |

## Sources covered

NIST CSF 2.0, NIST SP 800-53 Rev. 5, NIST SP 800-61 Rev. 3, ISO/IEC 27001:2022, COBIT 2019, CIS Controls v8.1, FTC Safeguards Rule, SEC Reg S-K Item 106 and Form 8-K Item 1.05, SEC Regulation S-P as amended 2024, NYDFS 23 NYCRR Part 500, NAIC Model 668 and state adoptions, HIPAA Security Rule, CMMC and NIST SP 800-171 Rev. 3, CIRCIA, PCI DSS v4.0.1, SOC 2 Trust Services Criteria, and state privacy statutes.

## What this is not

An orientation aid, not a legal interpretation, and not an exhaustive mapping of either side. Applicability varies by entity type, sector, state and contract. Status statements reflect public sources as of September 2026, and several of the instruments mapped here are in motion: the SEC items have been under rescission pressure since May 2025, the CIRCIA final rule is still unpublished, the proposed HIPAA Security Rule update is not final, and NAIC Model 668 is adopted state by state. Read the current text of a rule before relying on any row.

## Citation

> CGROM Regulatory and Framework Crosswalks by Thiago Oliveira Lima, DOI [10.6084/m9.figshare.34963048](https://doi.org/10.6084/m9.figshare.34963048), licensed under CC BY 4.0. Derived from the CGROM Open Edition v2.0. DOI [10.6084/m9.figshare.34045599](https://doi.org/10.6084/m9.figshare.34045599), building on v1.0, DOI [10.6084/m9.figshare.33963217](https://doi.org/10.6084/m9.figshare.33963217).
