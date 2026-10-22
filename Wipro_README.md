# BRSR and GRI Disclosure Analysis: Wipro Limited, FY 2024-25

An analysis of how Wipro reports on sustainability, using two frameworks side by side: India's mandatory **BRSR** (Business Responsibility and Sustainability Report) and the global **GRI Standards**.

## What this project is

An individual assignment for the BS in Analytics and Sustainability Studies at TISS Mumbai. The task was to pull key numbers out of a real company's disclosures, test how complete they are, turn them into comparable ratios, and then ask a harder question: why does a company publish two separate reports?

**Company:** Wipro Limited, FY 2024-25.
**Sources:** Wipro's BRSR (part of its Integrated Annual Report 2024-25) and its Sustainability Report with the GRI Content Index.

## What I did

1. **Extracted 9 KPIs** from the BRSR, each with its principle, unit and page number.
2. **Scored completeness:** how many of the 9 are actually disclosed with a number.
3. **Calculated intensity ratios** (emissions, water and energy per rupee crore of turnover).
4. **Reconciled my ratios** against the intensities Wipro prints in its own report.
5. **Built a GRI coverage table** for 5 standards (55 disclosures) using Wipro's GRI Content Index.
6. **Reflected on BRSR vs GRI:** which gave better data, and why both exist.

## The 9 KPIs

| KPI | Value (FY 2024-25) | BRSR page |
| --- | --- | --- |
| Turnover (Section VI, CSR details) | INR 672,928 million | 483 |
| Permanent employees | 225,306 | 482 |
| Women in permanent workforce | 37.13% | 482 |
| Employee turnover rate (permanent) | 14.81% | 482 |
| Lost Time Injury Frequency Rate | 0.27 per million person-hours | 499 |
| Scope 1 + Scope 2 emissions | 31,462 tCO2e (8,046 + 23,416) | 509 |
| Water consumption | 1,307,531 kilolitres | 507 |
| Total energy consumed | 756,175,527.8 MJ | 506 |
| POSH complaints filed | 125 | 504 |

## What I found

- **Completeness is 100% (9 of 9).** That says little about Wipro. Full disclosure of the basics is the expected baseline for a company filing a BRSR with assurance.
- **Intensity ratios** (using Section VI turnover of INR 67,293 crore): **0.4675 tCO2e**, **19.43 kilolitres** of water and **11,237 MJ** of energy per INR crore of turnover.
- **My ratios are about 1.3 times higher than Wipro's own printed intensities** (GHG 1.34, water 1.30, energy 1.32). All three gaps are almost the same size, which points to one cause rather than three errors: the revenue figure. Working backwards, Wipro's ratios imply a revenue base of roughly **INR 87,000 to 90,000 crore**, not 67,293 crore. That fits the change in reporting boundary from standalone to consolidated noted on page 480.
- **Scope 3 is missing from every ratio.** Wipro states that around 86% of its GHG impact comes from its extended value chain (page 514), and none of these ratios capture that.
- **GRI coverage is 55 of 55** across GRI 2 (30 disclosures), GRI 3 (3), GRI 305 Emissions (7), GRI 303 Water (5) and GRI 403 Occupational Health and Safety (10).
- **BRSR vs GRI:** the BRSR is templated, numbered and assured, so extraction was mechanical. The GRI report points back to the same assured data, so the interesting question is why Wipro produces both. My reading is that the BRSR is compliance with SEBI, while the GRI report serves global investors and ratings.

## Limits you should know about

- **Completeness only checks that a number exists on a page,** not whether it is accurate or well measured.
- **GRI coverage counts any entry in the content index,** including entries that say "None" (GRI 2-4) or "Workers are not relevant to our business" (GRI 2-8). A score of 100% shows that every disclosure has an entry, not how deep it goes.
- **The intensity ratios are structural.** Wipro is an IT services company, so low emissions and water use per rupee are expected. A fair comparison needs peers such as TCS or Infosys.
- **One company, one year.** The ratios use Scope 1 and 2 only.

## What is in this repo

- **Excel workbook:** four sheets (KPI Data, Completeness, Intensity Ratios, GRI Coverage), with live formulas.
- **Word report:** the written analysis and reflection.
- **Source evidence PDF:** the exact BRSR pages (480 to 514) and GRI Content Index pages (146 to 151) used.

## Built with

- **Excel** for extraction, scoring, ratios and the coverage table
- **Word** for the written report

## Author

**Yug Bhogi**, BS in Analytics and Sustainability Studies (2024-28), TISS Mumbai.
GitHub: [Yug1207](https://github.com/Yug1207)
