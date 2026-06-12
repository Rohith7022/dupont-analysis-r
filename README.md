# DuPont Analysis – Financial Analytics
## VCU – Financial Analytics (FIRE 540) · Three-Part Project

A structured, end-to-end **DuPont decomposition analysis** in R, spanning question formulation, data engineering, and full quantitative analysis. Built for an investor stakeholder seeking industry and company investment recommendations.

---

## Project Structure

### Part I – Ask the Right Questions (`part-I-ask-the-right-questions.html`)
Before touching the data, this section develops the analytic framework. Defines the investor's objective, identifies meaningful questions from the DuPont ratios, and maps the analysis strategy.

**Key concepts:** Return on Equity (ROE), asset turnover, profit margin, financial leverage, investor preference frameworks

### Part II – Extract, Transform, and Load (`part-II-etl-pipeline.html`)
Full ETL pipeline in R. Loads `dupont-analysis-combined.csv` (balance sheet + income statement merged across companies and years), validates data quality, computes all DuPont ratios, and prepares analysis-ready datasets.

**Key concepts:** Data validation, NA handling, ratio computation, tidyverse ETL

### Part III – Apply Analytic Techniques (`part-III-analysis-techniques.html`)
Full quantitative analysis. Applies regression, visualization, and comparative analytics to identify top-performing companies and industries by DuPont metrics.

**Key concepts:** Regression analysis, industry benchmarking, company ranking, ggplot2 visualization

---

## Tech Stack

`R` `tidyverse` `ggplot2` `dplyr` `readr` `Quarto`

---

*Virginia Commonwealth University · MS Business (Financial Analytics) · FIRE 540*
*Instructor: Prof. Larry Tentor*
