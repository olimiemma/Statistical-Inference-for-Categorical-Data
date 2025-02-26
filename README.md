# Statistical Inference for Categorical Data

## Overview
This repository contains an analysis of data from the Youth Risk Behavior Surveillance System (YRBSS) survey, exploring statistical inference techniques for categorical data. The project demonstrates confidence interval estimation, hypothesis testing, and explores the relationship between sample proportion and margin of error.

## Key Features
- Bootstrap confidence interval estimation for proportions
- Hypothesis testing using the `infer` package in R
- Exploration of the success-failure condition for inference
- Analysis of the relationship between population proportion and margin of error
- Statistical comparison between different categorical variables

## Dataset
The analysis uses the YRBSS dataset, which contains survey data from high school students on various health-related behaviors, including:
- Texting while driving
- Helmet usage
- Physical activity
- Sleep habits
- Strength training

## Methods
The analysis utilizes modern statistical inference techniques with the `infer` package, which provides a consistent syntax for:
- Bootstrapping to generate confidence intervals
- Permutation testing for hypothesis tests
- Visualization of sampling distributions

## Key Findings
1. Analysis of texting while driving among non-helmet wearers
2. Exploration of proportions of students who are physically active daily
3. Assessment of sleep patterns among high school students
4. Investigation of the relationship between sleep duration and strength training

## Technical Details
### Libraries Used
- `tidyverse` for data manipulation and visualization
- `openintro` for the YRBSS dataset
- `infer` for statistical inference
- `dplyr` for data transformation

### Statistical Concepts Covered
- Bootstrap confidence intervals
- Margin of error calculation
- Success-failure condition (np ≥ 10 and n(1-p) ≥ 10)
- Type I error probability
- Sample size determination

## Getting Started
1. Clone this repository
2. Install required R packages:
   ```r
   install.packages(c("tidyverse", "openintro", "infer", "dplyr"))
   ```
3. Open the R Markdown file in RStudio
4. Run the analysis chunks to reproduce the results

## Author
Emmanuel Kasigazi

## License
This project is available under the [MIT License](LICENSE).

---
*Note: This analysis is for educational purposes and demonstrates statistical inference techniques for categorical data.*
