# Beyond Admission: International Student Numbers and Graduate Employment Outcomes in UK Universities (2015–2025)

This repository contains the analysis code for my MSc Data Science dissertation (Module 7005SCN, Coventry University), which examines whether rising international postgraduate admissions to UK universities between 2015 and 2025 have translated into proportionate graduate employment outcomes.

## What's in this repository

- Jupyter notebook(s) containing the full analysis pipeline: data acquisition and cleaning, dataset integration, regression analysis, COVID-19 cohort comparison, subject-level analysis, and time-series forecasting (ARIMA, Prophet, Exponential Smoothing)
- `requirements.txt` — Python packages needed to run the notebook(s)

## Data sources

This project uses two official UK government datasets, both open access:

- **Admissions data:** Higher Education Statistics Agency (HESA), Student Data Figure 9 (Statistical Bulletins SB258 and SB273) — [hesa.ac.uk/data-and-analysis/students](https://www.hesa.ac.uk/data-and-analysis/students)
- **Employment data:** Department for Education, Longitudinal Education Outcomes (LEO) Graduate and Postgraduate Outcomes, underlying data, tax year 2022/23 release — [explore-education-statistics.service.gov.uk](https://explore-education-statistics.service.gov.uk/find-statistics/leo-graduate-and-postgraduate-outcomes/2022-23)

Raw data files are not included in this repository — they are large official publications and are best accessed directly from the source links above. File paths referenced in the notebook(s) reflect my local analysis environment.

## How this code maps to the dissertation

| Notebook section | Dissertation reference |
|---|---|
| HESA admissions loading and filtering | Section 3.4 |
| LEO employment loading and filtering | Section 3.5 |
| Dataset merge | Section 4.3, Table 4.1 |
| Regression analysis | Section 4.4, Table 4.2 |
| COVID-19 cohort comparison | Section 4.5, Table 4.3 |
| Subject-level analysis | Section 4.6, Table 4.4, Appendix A |
| Forecast modelling (ARIMA, Prophet, Exponential Smoothing) | Section 4.7, Tables 4.5–4.6 |
| Verification/testing checks | Section 4.8 |

## Requirements
See `requirements.txt`. Install with:

## Author

Indutimi Vera Dekawei, 
SID 15962906
MSc Data Science, Coventry University
Supervisor: Vernon Sassman
## Note on AI use

Portions of this project involved the use of Claude (Anthropic) for comprehension, code troubleshooting, and structural support, in line with Coventry University's amber-category AI use policy. Full details are provided in the AI Usage Declaration in the dissertation report. All analysis, results, and interpretive conclusions are the author's own.
