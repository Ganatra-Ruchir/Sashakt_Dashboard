# Sashakt Overall Dashboard — Data Source & Reconciliation Audit
Updated: 11 November 2026

## Scope and privacy
This register supports the **Overall** dashboard only. It records aggregate report evidence. Family-level, beneficiary-level, and personal profiling records must never be committed to this public repository.

## Source hierarchy
1. Verified, quarter-specific *intervention tables* in the signed/issued Narol and Naroda quarterly reports are used for filtered quarter activity totals.
2. Gifting Life Drive's "Sashakt - Master Data" cumulative and year-wise worksheet remains the historical FY baseline, pending reconciliation with later reports.
3. Detailed quarterly operational sheets (Dashboard Base Data FY24-25/FY25-26, Monthly MIS, activity trackers, and partner data) are cross-checks, not automatic replacements.
4. "Reported activity reach" does not equal the number of unique beneficiaries. Do not sum service categories as if distinct individuals.

## FY 2026–27 · Q2 (July–September 2026)

Source document titles on Gifting Life Google Drive:
- Narol Q2 26-27 Report.pdf
- Naroda Q2 Report (1).pdf

| Quarterly intervention measure | Narol | Naroda | Combined | Status |
|---|---:|---:|---:|---|
| New skilling enrolments | 204 | 190 | 394 | Report intervention tables |
| Skilling graduations | 192 | 168 | 360 | Report intervention tables |
| OPD service reach | 881 | 1,077 | 1,958 | Report intervention tables, not unique people |
| Financial literacy session reach | 1,194 | 1,214 | 2,408 | Report intervention tables, not unique people |
| Sashakt Science Labs reach | 2,082 | 2,637 | 4,719 | Report intervention tables, not unique students |
| Phase-launch reported reach | 500 | 0 | 500 | Narol-only activity; do not equate with unique families |

These six values are now available from the FY 2026–27 > Q2 Overall filter.

## Material report conflicts; pending reconciliation
- **Naroda FY26–27 Q2:** report cover says "01 July - 30 Sep 2025" although the report is titled Q2 FY26–27. It has internally inconsistent competition and graduation narratives; the intervention table has been used for the six indicated KPIs only.
- **Narol Q1 upload:** cover says FY25–26 but April–June 2026, which would fall in FY26–27.
- **Naroda Q1 upload:** cover says FY25–26 and April–June 2025, while some activity descriptions refer to June 2026. Do not automatically classify this upload as FY26–27 Q1.
- **Narol FY26–27 Q2:** the competition summary lists 158 participants while a subsequent narrative references 250; this measure has deliberately been excluded from Q2 KPIs.
- **Family totals:** the current master-data dashboard snapshot cites 11,000 families, while Narol Q2 and Naroda Q2 reports refer to 7,000 and 5,000 respectively. The meaning of combined unique vs cumulative reach and cross-location duplication requires source-level verification. Do not replace the master family KPI with the sum until reconciled.
- **Existing FY26–27 skilling data:** the dashboard's bifurcated annual skilling counts do not reconcile with the combined certified metric. Annual figures have not been silently overwritten.

## Quarter report inventory reviewed or found in Drive
- FY22–23: Narol Q1, Q2, Q3, Q4 reports reviewed.
- FY23–24: Narol Q1, Q2, Q3, Q4 reviewed; Naroda Q3/Q4 historical reports located, Q4 reviewed.
- FY24–25: Narol Q1/Q3/Q4 reviewed and Q2 located; Naroda Q1/Q2/Q3 reviewed and Q4 located.
- FY25–26: Narol Q1/Q2/Q3/Q4 reviewed; Naroda Q1/Q2/Q4 reviewed; Naroda Q3 not yet verified.
- FY26–27: two Q1-labeled uploads and Narol/Naroda Q2 reviewed; Q1 FY mapping unresolved.
- Some PDF files have duplicate uploads. A duplicate upload is **not** a new quarter.

## Source files identified for future cross-checks
- Sashakt - Master Data
- Dashboard - Base Data - FY 24-25.xlsx
- Dashboard - Base Data - FY 25-26.xlsx
- Report Data Collection.xlsx
- Shashakt - Sheets & Form Links
- Skilling Monthly Income Tracking; Family Profiling; Sashakt Activities; Diva Income Tracker (do not expose raw rows publicly)

## Outstanding work
- Verify historical report figures against master sheets at FY and quarter level before enabling historical quarter dropdown choices.
- Reconcile FY26–27 overall annual skilling and cumulative family figures against phase registers and distinct-family records.
- Visually test Overall on desktop/tablet/mobile and confirm live deployment is serving the newest main commit.
- Validate that changing FY, quarter, and location never mixes data periods and never turns missing numbers into zero.
