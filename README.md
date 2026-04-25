# CABG Postoperative Pneumonia Dashboard (2015–2021)

An interactive `flexdashboard` exploring the incidence and patient-level distribution of postoperative pneumonia among adults undergoing isolated coronary artery bypass grafting (CABG) in ACS-NSQIP data, 2015–2021 (N = 13,650; ~5.3% pneumonia rate).

## Live Dashboard

**[View the dashboard here](https://yixuan-he425.github.io/CABG-pneumonia-dashboard/)**

## Real-world Impact

Postoperative pneumonia is one of the most consequential and preventable complications after CABG, contributing to prolonged hospitalization, higher 30-day mortality, and excess healthcare costs. By making the temporal patterns and patient-level risk landscape of this complication transparent, this dashboard supports clinicians and quality-improvement teams in identifying high-risk subgroups and prioritizing perioperative interventions.

## Repository Contents

| File | Description |
|---|---|
| `dashboard_revised.Rmd` | Source R Markdown for the flexdashboard |
| `index.html` | Rendered dashboard for GitHub Pages |
| `README.md` | This file |

## Data Source

Data are derived from the ACS-NSQIP Participant Use Data Files (2015–2021), restricted to adult patients undergoing isolated CABG. ACS-NSQIP data are de-identified but require an institutional Data Use Agreement; raw patient-level data are **not** included in this repository.

## How to Reproduce

```r
install.packages(c("flexdashboard","plotly","DT","dplyr","tidyr","crosstalk"))
rmarkdown::render("dashboard_revised.Rmd")
```

## Author

Yixuan He, MSPH/MPH Candidate, Rollins School of Public Health, Emory University.
