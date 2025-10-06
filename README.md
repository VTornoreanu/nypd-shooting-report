# Data Science as a Field — NYPD Shooting Incident Report

**Repository:** https://github.com/virgiltornoreanu/nypd-shooting-report  

---

## 1️⃣ Reproducible Report

**Objective.** Analyse demographic and temporal patterns in NYPD Shooting Incidents (2008–present): yearly trend, seasonality, hour×day heatmap, demographics (gender, race, age), and borough comparisons.

**Data Source.** NYC Open Data — *NYPD Shooting Incident Data (Historic)* (`833y-fsy8`).  
The report automatically pulls the CSV data via the NYC Open Data API within the R Markdown file.

**How to reproduce** (R / R/RStudio):

```r
install. packages(c("tidyverse", "lubridate", "scales", "forcats", "reader", "tidyr", "RColorBrewer", "string", "tinytex"))
tinytex::install_tinytex()  # for PDF rendering if LaTeX is not present
