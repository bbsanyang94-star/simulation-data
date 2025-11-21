# Simulation Data Exports

This repository contains CSV exports produced by the Trust-Aware IoT offloading simulation.

Provenance
- The analyses and figures in the associated work were produced from the CSV files contained in this repository (`offloading_proportion.csv`, `privacy_utility.csv`, `resource_cost.csv`).
- No external datasets were used to generate these results.

Data Availability Statement (DAS)
- "All data generated and analysed during this study are included in the GitHub repository `https://github.com/bbsanyang94-star/simulation-data` (accessed 21 Nov 2025). The snapshot used for the analyses is the repository state at the time of publication; checksums for the CSV files are provided in `sha256sums.txt` to verify integrity."

Files
- `offloading_proportion.csv` — Offloading proportion data; columns: `Distance`, `NoPrivacy`, `WithPrivacy`.
- `resource_cost.csv` — Resource cost comparison; columns: `Label`, `Proposed`, `ECORA`, `MaxRange`.
- `privacy_utility.csv` — Privacy vs utility trade-off; columns: `PrivacyFactor`, `PrivacyLeakage`, `ResourceCost`.

Reproducibility
- To reproduce figures and analyses, clone the repository and run the analysis scripts in the project (or contact the corresponding author for additional instructions).

License & Citation
- Please include a citation to the repository or the DOI (if available) when using these data.

Generated: 2025-11-21
