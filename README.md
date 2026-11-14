# Data-analysis-assignments
Data analysis projects completed in R, covering exploratory data analysis, statistical hypothesis testing, and data visualization.

## Assignment 1 --- Data Story: NYC Flight Delays
An exploratory analysis of flight delays in New York City during 2013,
using data from the nycflights13 R package.

Dataset - 336,776 flights - Airports: JFK, LGA, and EWR - Year: 2013

Research questions - Is departure delay associated with arrival
delay? - Do airlines differ in their arrival-delay distributions?

Methods and findings - Spearman's rank correlation was used to
examine the relationship between departure and arrival delays. The
analysis found a positive correlation (approximately 0.63). - The
Kruskal--Wallis test was used to compare arrival delays across airlines.
The results indicated statistically significant differences between
airlines (p < 0.001).

## Assignment 2 --- Three Hypotheses: Perfume Data Analysis
A statistical analysis of ratings, popularity, and fragrance trends
using the Parfumo perfume database.

Dataset - Parfumo Perfume Database --- 59k Fragrances (Kaggle) -
59,325 perfumes

Research questions - Do average ratings differ across fragrance
categories? - Is perfume popularity (number of votes) associated with
its average rating? - Does the distribution of dominant accords vary
across release decades?

Methods and findings - Spearman's rank correlation was used to
investigate the relationship between the number of votes and average
rating. A weak positive association was found (ρ ≈ 0.14, p < 0.001). -
A chi-square test was used to examine the association between release
decade and accord distribution. The association was statistically
significant (χ² = 623.5, p < 0.001). - The analysis highlighted
differences in the prevalence of accords across decades: spicy and green
accords were more represented in the 1980s, fresh accords in the 2000s,
and sweet accords in the 2010s and 2020s.

### Tools and packages
- tidyverse
- scales
- ggridges
- patchwork
- knitr
- kableExtra
- ggrepel
- rstatix
  
### Viewing the reports
To view a project, open its corresponding HTML file in a web browser:
- domaci1_data_story.html
- domaci2_tri_hipoteze.html

To reproduce or modify the analysis, open the corresponding .Rmd file
in RStudio and knit it to HTML. Make sure the required R packages and
datasets are available.
