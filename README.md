# King County Real Estate Data Analysis

This project analyzes housing data from King County, WA, using linear regression and conformal prediction methods, including Jackknife+. The goal is to explore how various property features—such as bedrooms, bathrooms, square footage, and lot size—relate to house prices, and to quantify uncertainty in predictions. This work was originally completed as a final project for a statistics/data science course at the University of Washington and has been refined to improve clarity, reproducibility, and presentation of results.

## Project Structure

- `king_county_housing_analysis.Rmd` — Main R Markdown file containing code and explanations.
- `king_county_housing_analysis.html` — Knitted HTML version of the analysis.
- `king_county_housing_analysis.pdf` — Knitted PDF version of the analysis.
- `data/` — Contains training and testing datasets.
- `results/` — Stores outputs like prediction results and confidence intervals.
- `figures/` — Exported plots mainly for reference; all key figures are already embedded in the outputs.

## Key Points

- Linear regression performed on log-transformed prices.
- Jackknife+ used to create 95% prediction intervals.
- Observed large spread in intervals due to log transformation and high coverage level.

## Requirements

- R (≥ 4.0)  
- RStudio (recommended)  
- R packages: `ggplot2`
You can install the R package with: `install.packages("ggplot2")`

## How to Use

1. Clone or download this repository.
2. Open `king_county_housing_analysis.Rmd` in RStudio.
3. Run the code chunks to reproduce results and figures.