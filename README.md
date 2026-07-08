# Soccer Analytics: Evaluating the Effect of Ball Control on Goal Scoring

Undergraduate research project conducted under Professor Alexander Aue, UC Davis Department of Statistics (Fall 2025).

## Overview

This project investigates how ball control metrics affect goal scoring at the international level. Using squad-level data from the 2022 FIFA World Cup, a multiple linear regression model was built to evaluate how possession, progressive carrying distance, and pass completion percentage influence a team's shots on target. Progressive carrying distance was identified as the strongest predictor after diagnosing and resolving multicollinearity among pass-completion variables.

## Data

Source: [fbref.com](https://fbref.com) — 2022 FIFA World Cup squad statistics (32 teams)

Key variables:
- Possession percentage
- Progressive carrying distance
- Pass completion percentage
- Shots on target

## Methods

- Exploratory data analysis including summary statistics, univariate distributions, and correlation matrix visualization
- Multicollinearity diagnosis and resolution among pass-completion variables
- Multiple linear regression modeling with shots on target as the response variable

## Requirements

R packages used: `tidyverse`, `skimr`, `naniar`, `GGally`, `corrplot`, `stringr`

Install with:
```r
install.packages(c("tidyverse", "skimr", "naniar", "GGally", "corrplot", "stringr"))
```

## File Structure

```
soccer-ball-control-analysis/
├── SoccerAnalyticsFall25Project.Rmd   # Main analysis file
└── wc22data.csv                        # 2022 World Cup squad data (source: fbref.com)
```

## Author

Sophia Rao — University of California, Davis
[linkedin.com/in/sophiarao](https://linkedin.com/in/sophiarao)
