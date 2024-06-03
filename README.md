# Economist/Data Scientist
<img src="email.png" width="180">

[Resume (PDF)](Ray_Wang_2024.pdf)

### Technical Skills
- **R**: ggplot, data.table, Shiny
- **Python**: pandas, scipy, scikit-learn, numba, conda
- Dynamic discrete choice models, structural demand estimation, causal inference
- Machine learning (random forest), classification and regression models, exploratory data analysis, data visualization
- Git, AWS, SQL

## Projects
### [Exploration of Seasonal Trading](https://github.com/raywang202/technical-trading)

An analysis of seasonal trading strategies in the S&P 500, using Jupyter Notebooks. Using a dataset of 6 million+ daily close prices across the S&P 500, I applied a random forest classifier to identify a subset of very profitable trades among all seasonal price signals, trading off recall for improved precision. The random forest strategy resulted in simulated returns that outperformed both the S&P500 and a seasonal trading strategy in both 2022 and 2023

![Random Forest](rf_returns_2023.png)

### [Dissertation Code](https://github.com/raywang202/dissertation)

Code used to implement my dissertation, [The Impact of Grades on College Major Choice, Dropout, and Labor Outcomes](https://cdr.lib.unc.edu/concern/dissertations/5m60qz54r?locale=en). At the core of my model is solving via backwards induction a dynamic programming model of student behaviors throughout college and into the workforce (using the framework of Keane and Wolpin 1997). This involves maximizing a simulated likelihood over a set of dozens of parameters, which requires calculating utilities over a large state space. Solving this problem would have been computationally infeasible without both the use of Python's Numba package as well as the University's computing cluster.

## Work Experience
### Center for Naval Analyses (CNA) | Arlington, VA
**_Research Scientist / Economist_ | Nov 2023 - Present**  
**_Research Analyst / Economist_ | Jun 2020 - Oct 2022**
- Led technical effort to model and predict sailor re-enlistment decisions using 7 million+ panel observations, using conditional choice probability (CCP) estimation methods in R
- Simulated counterfactual policy impacts across different subpopulations/Navy ratings, visualized results, and provided recommendations to military leadership, affecting the implementation of promotion/compensation policies in Navy’s Detailing Marketplace Assignment Policy (DMAP)
- Within one year of on-boarding as junior researcher, assumed project leadership role. Learned legacy codebase, expanded model functionality to incorporate heterogeneous policy impacts across different subgroups, and documented model framework leading to successful hand-off of model after project completion
- Led project that extended Navy-specific model and codebase to accommodate differently structured datasets and use-cases for the Marine Corps, on a compressed project timeline
- Mentored junior team members in econometric methods and programming best practices
- Developed metric to predict military recruiting yield across different geographic regions using LASSO methods. Presented results to non-technical audience of practitioners


**_CNA Field Representative to Carrier Strike Group (CSG) 12_ | Oct 2022 – Nov 2023**
- Directly supported Commander, CSG-12 with analysis on operational capabilities of first-in-class aircraft carrier. Embarked on board USS Gerald R. Ford for Oct - Nov 2022 and May - Nov 2023 deployments
- Worked independently in a fast turnaround and technology-constrained environment. Developed and planned analysis efforts to address Commander’s emerging priorities and timelines
- Conducted discussions with junior and senior sailors, collected and analyzed quantitative and qualitative data, and provided tailored recommendations and presentations to both senior leadership and action officers
- Efforts included modeling the impact of new military technology on Composite Training Unit Exercise certification metrics and developing new operational best practices, identifying focus areas for equipment upgrades to improve combat operational efficiency metrics, and assessing carrier strike group tactics in the presence of ship hardware interoperability concerns

### DC Energy | Vienna, VA
**_Analyst_ | Sep 2012 - Oct 2013**
- Analyzed electricity and steel/iron ore markets using R and SQL. Proposed trading strategies that led to 20% returns over 6 months
- Developed dashboards with PHP and R Shiny to visualize asset prices in support of daily trading


## Education
### PhD in Economics
**_University of North Carolina at Chapel Hill | 2014 - 2020_**
- Subfields: Applied microeconomics, labor economics
- Dissertation involved data cleaning, dynamic programming, and program execution time optimization in Python using numba; data visualization in R
  - Code snippets available [here](https://github.com/raywang202/dissertation)
  - Dissertation available at the [UNC Library](https://cdr.lib.unc.edu/concern/dissertations/5m60qz54r?locale=en)

### BS Eng. in Operations Research and Financial Engineering
**_Princeton University | 2008 - 2012_**

## Other
- Top Secret security clearance (Nov 2022 – Present)
- Secret security clearance (Jan 2021 – Nov 2022)
- Fluent in English and Chinese, intermediate Spanish

