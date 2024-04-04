# Data Scientist
<img src="email.png" width="180">

[Resume (PDF)](Ray_Wang_2024.pdf)

### Technical Skills
- **R**: ggplot, data.table, Shiny
- **Python**: matplotlib, pandas, scipy, sklearn
- Discrete choice, demand estimation
- Causal inference
- Machine learning, nonparametric statistics

## Work Experience
### Center for Naval Analyses (CNA) | Arlington, VA
**_Research Scientist / Economist_ | Nov 2023 - Present**  
**_Research Analyst / Economist_ | Jun 2020 - Oct 2022**
- Modeled sailor re-enlistment decisions using 7 million+ panel observations, via conditional choice probability (CCP) estimation in R
- Simulated policy impacts, visualized results, and presented recommendations to non-economists and military leadership, directly affecting implementation of Navy's Detailing Marketplace Assignment Policy Phase I
- Within one year, learned legacy codebase, extended Navy-specific codebase to work with Marine Corps data, improved model fit, and successfully on-boarded incoming staff

**_CNA Field Representative to Carrier Strike Group (CSG) 12_ | Oct 2022 – Nov 2023**
- Directly supported Commander, CSG-12 with analysis. Embarked on board _USS Gerald R. Ford_ for Oct - Nov 2022 and May - Nov 2023 deployments
- Topics included assessing electronic warfare tactics and optimizing carrier flight operations
- Worked independently in a fast turnaround environment, with tasks including interviews and discussions with sailors, data collection, analysis, and presentation of results and recommendations to leadership

### DC Energy | Vienna, VA
**_Analyst_ | Sep 2012 - Oct 2013**
- Analyzed electricity and steel/iron ore markets using R, leading to profitable trades with ~20% return on capital over 6 months
- Developed dashboards with PHP and R Shiny to visualize prices in support of daily trading

## Projects
### [Exploration of Seasonal Trading](https://github.com/raywang202/technical-trading)

An exploration of seasonality in stock price movements, using Jupyter Notebooks. I look at seasonal price movements in the S&P 500 and individual stocks, and consider how trading strategies built around this seasonality would perform in an out-of-sample backtest in 2022 and 2023. I then overlay a random forest model on top of this "first stage" model, to identify the subset of strong performing stocks among those proposed by the seasonal strategy, rather than trading all of the stocks proposed. I also highlight the importance of "purging" the data such that the training and testing data do not overlap in time. The random forest seasonal strategy outperforms both the simple seasonal strategy as well as the S&P 500 in the 2022 and 2023 backtests. And while there are a large proportion of "missed" trading opportunities due to the random forest generating a large number of false negatives (low recall), this is compensated by the higher precision in identifying strong performers, such that the random forest strategy comes out on top, especially if one considers trade frictions.

![Random Forest](rf_returns_2023.png)

### [Dissertation Code](https://github.com/raywang202/dissertation)

Code used to implement my dissertation, [The Impact of Grades on College Major Choice, Dropout, and Labor Outcomes](https://cdr.lib.unc.edu/concern/dissertations/5m60qz54r?locale=en). At the core of my model is solving via backwards induction a dynamic programming model of student behaviors throughout college and into the workforce (using the framework of Keane and Wolpin 1997). This involves maximizing a simulated likelihood over a set of dozens of parameters, which requires calculating utilities over a large state space: solving this problem would have been infeasible without both the use Python's Numba package as well as the University's computing cluster.

## Education
### PhD in Economics
**_University of North Carolina at Chapel Hill | 2014 - 2020_**
- Subfields: Applied microeconomics, labor economics
- Dissertation involved data cleaning, dynamic programming, and program execution time optimization in Python, data visualization in R
  - Code snippets available [here](https://github.com/raywang202/dissertation)
  - Dissertation available at the [UNC Library](https://cdr.lib.unc.edu/concern/dissertations/5m60qz54r?locale=en)

### BS Eng. in Operations Research and Financial Engineering
**_Princeton University | 2008 - 2012_**

## Other
- Top Secret security clearance (Nov 2022 – Present)
- Secret security clearance (Jan 2021 – Nov 2022)
- Fluent in English and Chinese

