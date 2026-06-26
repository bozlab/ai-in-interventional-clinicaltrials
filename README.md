# Artificial Intelligence Use in Interventional Clinical Trials Registered on ClinicalTrials.gov

This repository contains the interactive Power BI dashboard and underlying 
data accompanying the cross-sectional study "Artificial Intelligence Use in 
Interventional Clinical Trials Registered on ClinicalTrials.gov." The study 
analyzed 1,212 interventional trials registered on ClinicalTrials.gov with 
study start dates from January 2022 onward that involved AI in any capacity. 
The dashboard allows users to explore trial characteristics including clinical 
condition, AI purpose, data modality, generative AI involvement, and trial 
status. All annotated data produced during the review process is included in 
this repository to support transparency and reproducibility.

---

## Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free download)
- A Microsoft account (required to render map visuals via Bing Maps)

---

## How to Use

1. Clone or download this repository.
2. Open the `.pbip` file in Power BI Desktop.
3. Click **Refresh** to load the latest data directly from the source URLs embedded in the queries.
4. Sign in with a Microsoft account when prompted to allow map visuals to render.

---

## Data Sources

| File | Description | Source |
|------|-------------|--------|
| `data/Country_Region_Continent_Mapping.xlsx` | mapping of country to continent |
| `data/final-included-studies_n1212.xlsx` | Full study data | Collected and annotated as described in the paper |
| `data/final-included-studies_n1212_abbrev.xlsx` | Abbreviated Study data specific to the dashboard |

Data is loaded directly from pinned GitHub raw URLs in Power Query, ensuring anyone who opens the dashboard uses exactly the same data as the published analysis.

---

## Repository Structure

```
├── dashboard.pbip            # Power BI Project file
├── dashboard.Report/         # Report definition (visuals, pages)
├── dashboard.SemanticModel/  # Data model (measures, tables)
├── data/                     # Source data files
└── README.md
```
---

## Dashboard Preview

![Dashboard Preview](https://github.com/bozlab/ai-in-interventional-clinicaltrials/blob/master/images/dashboard-preview.png?raw=true)

---

## Citation

If you use this dashboard or data in your own work, please cite:

> Selen Bozkurt, PhD, Irem Kar, PhD, Sweta Balaji, BS, Nevruz Ilhanli, PhD, Selvi Ramalingam, MSc, MBA, Azra Ismail, PhD, Ravi Parikh, MD (2026). *Artificial Intelligence Use in Interventional Clinical Trials Registered on ClinicalTrials.gov*. Dashboard - https://github.com/bozlab/ai-in-interventional-clinicaltrials/

---

## Contact

Selen Bozkurt -- selen.bozkurt@emory.edu  
Paper: *Artificial Intelligence Use in Interventional Clinical Trials Registered on ClinicalTrials.gov*
