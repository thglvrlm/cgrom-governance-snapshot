# CGROM Governance Snapshot

A free, 15-question self-assessment of cyber governance and risk maturity across five pillars. It runs entirely in the browser: no sign-up, no server, no analytics, and no answers are collected or transmitted. Open `index.html` and it works offline.

Available in English and Portuguese.

## What it does

You score fifteen statements from 0 to 3. The tool returns a score per pillar, an overall maturity level on a five-level scale, and, for every statement scored 0 or 1, the United States frameworks and rules where the matching CGROM mechanism applies, including NIST CSF 2.0, the FTC Safeguards Rule, SEC Regulation S-K Item 106 and state insurance data security law.

It is a directional view. It is not an audit, a certification or legal advice.

## The method behind it

The statements, the scoring and the five-level maturity model come from the CGROM Open Edition, a published open-access framework by Thiago Oliveira Lima:

- CGROM Open Edition v1.0, 22 September 2026, DOI [10.6084/m9.figshare.33963217](https://doi.org/10.6084/m9.figshare.33963217)
- CGROM Open Edition v2.0, October 2026, DOI [10.6084/m9.figshare.34045599](https://doi.org/10.6084/m9.figshare.34045599)

v2.0 builds on v1.0 and does not replace it. The fifteen statements in this tool are identical in both editions, so a score taken against either edition stays comparable.

CGROM, the Cyber Governance and Risk Operating Model, is an integration layer rather than a replacement for existing frameworks. NIST CSF 2.0, ISO/IEC 27001 and COBIT define what to achieve. CGROM defines how to operate: governance mechanisms, indicators and an implementation sequence that turn technical security findings into risk decisions leadership can govern and auditors can verify.

## Crosswalks as data

The regulatory and framework crosswalks from the Open Edition are also published here in machine readable form, so they can be used inside other tools instead of read in a PDF: 134 mappings across 17 sources, in [`data/`](data/). See [data/README.md](data/README.md) for the field dictionary and the limits of use.

## Running it

Download `index.html` and open it in any browser. There is no build step and no dependency.

To host it, serve the single file from any static host.

## Privacy

Answers stay in the browser for the duration of the session and are never sent anywhere. The page makes no network requests.

## Contributing

Issues and pull requests are welcome, particularly on the wording of the statements, the framework crosswalks and the Portuguese translation. If you have used the Snapshot in a real organisation, feedback on where the result diverged from the internal perception is the most useful contribution of all.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0). You may share and adapt the work, including commercially, provided you give appropriate credit. See [LICENSE](LICENSE).

## Author

Thiago Oliveira Lima. TOL CyberGuard.
