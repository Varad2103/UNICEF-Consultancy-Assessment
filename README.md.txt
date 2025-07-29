# Position applied for: Administrative Data Analyst - Req. #581696

# UNICEF Consultancy-Assessment

This repository contains an end-to-end workflow for evaluating maternal and newborn care coverage indicators across countries, as part of a UNICEF technical consultancy assessment.

## 📁 Repository Structure

- `data/`: Contains input Excel files used in the analysis.
  - `WPP2022_GEN_F01_DEMOGRAPHIC_INDICATORS_COMPACT_REV1.xlsx`: Projected births by country and year.
  -  Used UNICEF Global Data Repository: Coverage data for ANC4 and SBA indicators.
  - `On-track and off-track countries.xlsx`: Country-level tracking status for progress.
  -  Integrated 3 datasets using consistent country identifiers. Use identical columns to join the data and create useful dataframe.
  
- `scripts/`: Python scripts used for analysis and report generation.
  - `UNICEF Data and Analytics Technical Evaluation.py`: Main analysis notebook/script.
  - `UNICEF Data and Analytics Technical Evaluation.py`: Script to run the workflow end-to-end.
  
- `docs/`: Final report(s) in PDF or DOCX format.
  - `UNICEF Data and Analytics Technical Evaluation.pdf`
  
- `output/`: Contains HTML visualization reports.
  - `coverage_report.html`

- `user_profile.py`: Configuration script to ensure reproducibility across machines.

####### Answers for the questions asked in the assessment: Weighted_ANC4  Weighted_SBA
Track_Status                             
Off-track         71.006587     87.399835
On-track          62.829343     82.245623