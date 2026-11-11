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
- **Family totals:** an older dashboard snapshot cited 11,000 families, while the latest combined Master Data FY26–27 row reports 12,000, while Narol Q2 and Naroda Q2 reports refer to 7,000 and 5,000 respectively. The meaning of combined unique vs cumulative reach and cross-location duplication requires source-level verification. Do not replace the master family KPI with the sum until reconciled.
- **Existing FY26–27 skilling data:** the dashboard's bifurcated annual skilling counts do not reconcile with the combined certified metric. Annual figures have not been silently overwritten.

## Quarter report inventory reviewed or found in Drive
- FY22–23: Narol Q1, Q2, Q3, Q4 reports reviewed.
- FY23–24: Narol Q1, Q2, Q3, Q4 reviewed; Naroda Q3/Q4 historical reports located, Q4 reviewed.
- FY24–25: Narol Q1/Q3/Q4 reviewed and Q2 located; Naroda Q1/Q2/Q3 reviewed and Q4 located.
- FY25–26: Narol Q1/Q2/Q3/Q4 reviewed; Naroda Q1/Q2/Q3/Q4 reviewed (Naroda Q3 sourced from file `1Rys0ZUAbiK7xCK5ewgeXSXT9d6O82oA7`).
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

## Historical Insights source investigation — 11 November 2026

### What was checked
The Gifting Life Drive's unique quarterly report series was searched/read from FY22–23 through the current FY26–27 Q2:
- FY22–23 Narol Q1–Q4 (4)
- FY23–24 Narol Q1–Q4, Naroda Q3–Q4 (6)
- FY24–25 Narol Q1–Q4, Naroda Q1–Q4 (8; Narol Q2 PDF file located but text extraction incomplete)
- FY25–26 Narol Q1–Q4, Naroda Q1–Q4 (8)
- FY26–27 latest Q1-labelled Narol/Naroda copies and Narol/Naroda Q2 (4; conflicting cover dates for Q1/Naroda Q2)
About **30 distinct report slots** were identified across these series, excluding duplicate uploads. One FY24–25 Narol Q2 PDF requires visual/OCR validation and modern FY26–27 Q1 labels need resolution.

Additional inspected sources: `Budget FY 25-26` (Narol and Naroda budget plus FY24–25 actual category columns), `Budget Utilization 26-27` and its differing copy, `Activities Budgets.xlsx`, `Sashakt - Master Data`, `Sashakt Activity Tracker`, `Active/Inactive Family - Naroda`, `Family Survey (Responses)`, and Sashakt activity-response files (some file-text exports empty).

### Project Pillars — donut
- Original Naroda reference image reports **53% skilling, 34% education, 8% health, 5% financial literacy**; it must remain labelled as a historical Naroda-specific reference, not automatically copied to Narol or both centres.
- `Budget FY 25-26` includes **FY24–25 actual expenditure** alongside proposed FY25–26 budgets. It reports overall Narol actual ₹24,158,693 and Naroda actual ₹18,197,868 for FY24–25, with multiple headings such as centre operations, skilling, child education, healthcare, school education, school health and financial literacy. These are not yet a certified *four-pillar allocation*: operational overhead allocation, subcategory hierarchy and reconciliation are required.
- `Budget Utilization 26-27` and its copy disagree on numerous planned Q2 cells. Neither is evidence of Q2 **actual spend**, so do not use them to calculate pie/donut investment shares.
- No verified Narol or combined four-pillar allocation matching the original chart's definition was located in the accessible report text or inspected budget summaries.

### Families Participation — Venn
- Active/Inactive Naroda sheet includes family codes and status, but its active/inactive tally **is not** the intersection of Health, Skilling and Education.
- Family survey and family profiling data supply household identifiers; Sashakt Activity Tracker totals are **activity instances/beneficiary touches**, not deduplicated household service participation.
- To derive a seven-region three-circle Venn, each health, skilling and education participation record must be linked to a normalized common household ID, then de-duplicated across events and services with an agreed date/FY scope.
- The original Naroda graphic claims 924 families, but region counts add to 1,084; no approved correction was located in readable source material. Thus original figures must remain flagged as unreconciled.
- No verified Narol or combined seven-region family-overlap table has been established. Missing overlaps should **not** be shown as zero or inferred by subtracting independent program totals.

### More serious FY26–27 reporting disagreements
The newer master workbook contains a tab `Q2 FY 2026–27 VERIFIED ACTIVITY METRICS` that disagrees with the published quarterly report intervention tables used earlier:
- Narol skilling admissions: report **204** versus reconciled tab **179** (Adani-specific).
- Naroda graduation: report **168** versus reconciled tab **178** (Wings to Fly).
- Naroda OPD Q2 reach: report **1,077** versus activity-tracker-reconciled **1,014**.
- Combined financial literacy Q2 **2,408** matches across the tab and reports.
Treat the earlier Q2 dashboard view as **pending alignment with the reconciled tab**, and do not describe conflicting measures as verified unique people.

### Chart implementation rule
Keep **Project Pillars as a donut** and **Families Participation as a three-circle Venn**. Display source-grounded values only when the selected location and period match their scope; otherwise show an explicit unavailable-data state, not a new bar or line chart and not fabricated numbers. Never publish person-level family or survey records in the public repository.

## 11 November 2026 — shared spreadsheet and email cross-check, Overall fixes

- Discovery used Gifting Life Drive's `sharedWithMe=true` spreadsheet listing, not merely file-name search. Confirmed accessible source sheets: `Sashakt - Master Data`, `Narol sashakt datasheet` (Healthcare/Education/Skill development), `Target vs Achievement FY 25-26`, `Active/Inactive Family - Narol/Naroda`, `Narol,naroda,lambha target vs Achievement_25-26`, `Skilling Enrollment List - Narol/Naroda`, and partner trackers.
- **Root cause of empty KPI cards:** Overall's FY26–27 renderer returned null for every location split, despite current `Bifurcated Data` FY26–27 rows. Fixed on Overall page; other program pages unchanged.
- **FY26–27 Bifurcated Data current row:** Narol skilling operational 3,004, Naroda 1,403; OPD service reach 1,508 / 2,091; financial literacy 1,982 / 2,072; school general checkups 5,709 / 3,321; Diva Salon + Studio beneficiaries 179 / 138.
- **Definition caution:** Center-side skilling operational counts are not certified-only; the combined Master Data certified KPI is 1,837. Do not sum or compare these as equivalent.
- **Q2 reported family coverage:** Narol Q2 PDF says 7,000 beneficiary families; Naroda Q2 PDF says 5,000. This is *reported family coverage*; no individual household-ID deduplication is asserted.
- **FY26–27 Q2 corrected from Master Data's `Q2 FY26-27 Jul-Sep Audit` tab:** Narol/Naroda admissions 179/190, graduations 192/178, OPD beneficiary visits 881/1,014, FL 1,194/1,214; Science Lab engagements 2,082/2,637 from report summary. Phase-launch attendance 322/0, not estimated phase-enrolled families 500.
- **Gmail corroboration:** Wings to Fly email from 29 Oct 2026 links partner FY26–27 target-vs-achievement Sheet (`1oXwio_03cCxHzoPT3YI5fl-vUh0fBU_Qf1yjIs844K0`); Adani correspondence 23 Oct 2026 explicitly says its previously supplied MIS figures are the latest verified ones; 27 Oct 2026 Home First feedback confirms Narol Q2 FY label error.
- **Chart behavior:** FY-specific Overview location charts now show program operational metrics and a real OPD reach trend rather than empty family-milestone lines. Historical donut follows FY and location; original Venn is a historical Naroda-only visual pending deduplicated family overlap.
- **Unresolved:** No verified cross-program family-ID intersection matrix for Health/Skilling/Education. The original Naroda 924-family Venn still contains irreconcilable printed regions summing to 1,084. We cannot show deduplicated Venn figures for Narol, Naroda or combined without family-program participation IDs or an approved seven-region overlap table.
