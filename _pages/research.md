---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research specializes in **quantitative urban policy analysis**, drawing on applied microeconomics, econometrics, macroeconomic modeling, and geographic information systems (GIS). My work examines affordable housing, neighborhood socioeconomic inequality, transportation accessibility, environmental justice, health equity, education, labor-market inequality, food policy, and geographic information inequality. I use causal inference, policy evaluation, spatial econometrics, dynamic economic modeling, and computational urban analytics to study these issues.

My academic background includes an **M.S. in Economics from Tufts University (May 2025)**, a **B.S. in Econometrics and Quantitative Economics**, a **B.A. in Mathematics**, and a **minor in Statistics** from the University of Minnesota Twin Cities (December 2023). I am currently pursuing an **M.S. in Environmental Policy and Planning at Tufts University (expected May 2027)**.

## Research Interests

Urban and Housing Economics; Affordable Housing Policy; Spatial and Applied Econometrics; Transportation Accessibility and Equity; Spatial and Socioeconomic Inequality; Urban Informatics and Computational Urban Analytics; Environmental Justice and Health Policy; Economics of Education and Labor Economics; Food Policy and Accessibility.

## Research Experience

### Graduate Research Assistant — Professor Shomon Shamsuddin

*Tufts University · September 2025–present*

- Investigate Low-Income Housing Tax Credit (LIHTC) development, housing affordability, neighborhood change, and community health using HUD LIHTC records, ACS, CDC PLACES, HUD-USPS vacancy data, and spatial datasets.
- Construct and harmonize census-tract-level datasets to support housing policy evaluation, including staggered difference-in-differences, event-study, boundary-based, and spatial econometric research designs.
- Contribute to research on Medicaid expansion, housing stability, and financial security through empirical research design, data preparation, literature review, and statistical analysis.

### Graduate Research Assistant — Professor Justin Hollander

*Tufts University · September 2025–present*

- Investigate digital urban inequality and the spatial distribution of geographic information in Wikipedia, examining how population and geographic characteristics relate to the representation of cities and other places.
- Analyze a dataset of 1,660,911 Wikipedia pages, filtered to 62,789 geographic entities using Wikidata classifications, including cities, towns, villages, human settlements, and administrative regions.
- Develop reproducible R workflows for large-scale data cleaning, geographic classification, population-data integration, descriptive statistics, and correlation analysis.
- Examine variation in article coverage, information depth, population, and geographic representation across settlements and regions.

## Research in Progress

### The Macroeconomic and Spatial Effects of Low-Income Housing Tax Credit Development: A Dynamic General-Equilibrium Framework

*2026–present · Master's Thesis · Advisor: Professor Shomon Shamsuddin*

Developing a calibrated deterministic dynamic general-equilibrium model to examine how LIHTC development could affect rental prices, private rental construction, aggregate consumption, productive investment, and housing supply. The model incorporates optimizing households, nonhousing production, rental-property development, market-rate and subsidized housing stocks, and a government-financed housing subsidy. Calibration will use publicly available HUD, Census, ACS, BEA, BLS, building-permit, and housing-market data, complemented by GIS analysis of LIHTC development patterns and neighborhood socioeconomic conditions.

### What does Wikipedia say about Cities? Epistemology and Spatial Distribution in the World’s Largest Encyclopedia

*2025–present · Collaborative Research · Professor Justin Hollander · UAA 2027 Accepted*

Examining geographic disparities in Wikipedia’s representation of cities and other places using 1,660,911 Wikipedia pages, including 62,789 place-related observations. Integrating Wikidata settlement classifications, population estimates, administrative geography, coordinates, and article characteristics to investigate differences in information coverage and spatial representation across settlements and regions.

### Spatial Inequalities in Bluebikes Accessibility: Affordable Housing, Transportation Disadvantage, and Urban Heat in Boston

*2026–present · Conference Research · AAG 2027 Accepted*

Extending previous research on urban heat, neighborhood inequality, and bikeshare accessibility to investigate spatial disparities in Bluebikes access near Low-Income Housing Tax Credit developments in Boston. The analysis integrates HUD LIHTC locations, Bluebikes stations, ACS socioeconomic indicators, and urban heat measures. Preliminary GIS analysis identified 47 LIHTC census tracts with Bluebikes stations and 21 without. Extensions include pedestrian-network service areas, slope-adjusted least-cost paths, and spatial econometric analysis.

## Conference Presentations

### Urban Affairs Association (UAA) Annual Conference <span style="float: right; font-size: 0.8em; font-weight: normal;"><em>April 2027 · Accepted for Presentation</em></span>

Hollander, J., & Kwok, A. “What does Wikipedia say about Cities? Epistemology and Spatial Distribution in the World’s Largest Encyclopedia.”

Coauthor; Professor Justin Hollander designated as primary presenter.

### American Association of Geographers (AAG) Annual Meeting <span style="float: right; font-size: 0.8em; font-weight: normal;"><em>February 2027 · Accepted for Presentation</em></span>

“Spatial Inequalities in Bluebikes Accessibility: Affordable Housing, Transportation Disadvantage, and Urban Heat in Boston.”

### American Association of Geographers (AAG) Annual Meeting <span style="float: right; font-size: 0.8em; font-weight: normal;"><em>March 20, 2026 · San Francisco, CA · Presented</em></span>

“Mapping Urban Heat Inequality in Boston: Integrating Affordable Housing, Income, and Bluebikes Access.”

## Research Papers and Applied Projects

#### [Housing and Transit Vulnerability in Grand Annecy ↗](https://storymaps.arcgis.com/stories/071b6237ee6f42d6910057581f362c9d)

*Summer 2026 · GIS 201: Introduction to GIS · ArcGIS StoryMap · Grand Annecy, France · Tufts University · Instructor: Professor Sumeeta Srinivasan*

- Integrated French property transaction data (DVF+), SIBRA GTFS public transit schedules, and IRIS statistical boundaries to examine spatial disparities in housing prices and public transportation accessibility across Grand Annecy.
- Applied ArcGIS Pro spatial analysis, including housing price per square meter, 400-meter transit-stop accessibility buffers, nearest-stop distances, and weekday transit service frequency.
- Developed a composite housing-transit vulnerability index using raster reclassification, weighted overlay, and zonal statistics.
- Applied Global and Local Moran’s I to assess spatial clustering and identify vulnerability hotspots.
- Identified significant positive spatial autocorrelation in the composite vulnerability index (Global Moran’s I = 0.627, z = 9.33, p < 0.001).

#### Spatial Analysis of LIHTC Development, Housing Affordability, and Tract-Level Health in Massachusetts

*Spring 2026 · GIS 203: Spatial Statistics · Research Paper · Tufts University · Instructor: Professor Sumeeta Srinivasan*

- Integrated HUD LIHTC property-level records, ACS socioeconomic and housing indicators, CDC PLACES health estimates, and Census TIGER/Line boundaries.
- Applied exploratory spatial data analysis (ESDA), Local Moran’s I (LISA), cross-sectional OLS, residual spatial-autocorrelation tests, and geographically weighted regression (GWR).
- Found a positive tract-level association between LIHTC concentration and high blood pressure prevalence (β = 0.465, p = 0.0094), alongside substantial geographic heterogeneity.
- Identified significant residual spatial autocorrelation (Moran’s I = 0.274, p < 0.01).
- GWR produced higher in-sample model fit than the corresponding OLS specification (R² = 0.871 versus 0.696).
- Conducted an exploratory two-way fixed-effects Difference-in-Differences analysis of LIHTC development timing and rent burden, finding no statistically significant post-development change (β = 0.0122, p = 0.413).
- Results are interpreted as tract-level spatial relationships rather than individual-level causal health effects.

#### <a href="https://storymaps.arcgis.com/stories/9cdf1d44cebd4872a843927d8724f69a" target="_blank" rel="noopener" style="text-decoration: underline;">Spatial Analysis of LIHTC, Housing Affordability, and Health ↗</a>

*Spring 2026 · GIS 203: Spatial Statistics · ArcGIS StoryMap · Interactive GIS Visualization · Tufts University · Instructor: Professor Sumeeta Srinivasan*

**2026 Tufts GIS Expo — GIS Award Finalist (Advanced StoryMaps)**

- Developed an interactive ArcGIS StoryMap illustrating the spatial distribution of LIHTC developments, housing affordability, and neighborhood health conditions across Massachusetts.
- Applied thematic mapping, Local Moran’s I (LISA), and geographically weighted regression visualizations to identify localized clusters, spatial outliers, and geographic variation in LIHTC-health associations.
- Visualized stronger positive local associations between LIHTC intensity and high blood pressure in parts of Central and Western Massachusetts and weaker or negative associations in Greater Boston.

#### Bluebikes Access, Affordable Housing, and Heat Inequality in Boston

*Spring 2026 · UEP 173: Transportation Planning · Research Paper · Tufts University · Instructor: Professor Shan Jiang*

- Integrated HUD LIHTC property locations, Bluebikes station and trip records, ACS socioeconomic indicators, land surface temperature, ERA5 climate data, and census tract boundaries.
- Conducted GIS spatial joins, proximity analysis, accessibility modeling, and mapping to investigate transportation accessibility and heat inequality.
- Estimated logistic regression of Bluebikes station presence, OLS models of land surface temperature and neighborhood characteristics, tract fixed-effects models of temperature-related ridership, and OLS models of nearest-station distance within LIHTC tracts.
- Identified 47 LIHTC census tracts with Bluebikes stations and 21 without.
- Found a stronger positive relationship between temperature and ridership in LIHTC tracts with station access (β ≈ 9.92, p < 0.001).
- Interpreted the findings as exploratory spatial and transportation relationships rather than causal effects.

#### Advancing Environmental Justice in Boston's Chinatown: Evaluation and Strategies for Just Energy Transition and Resilient Open Space

*Spring 2026 · UEP 255: Field Projects · Collaborative Research Project · Tufts University · Instructor: Professor Penn Loh · Community Partner: Chinatown Community Land Trust (CCLT)*

- Collaborated with a graduate research team and the Chinatown Community Land Trust to evaluate environmental justice challenges and strategies for equitable energy transitions and resilient open space in Boston's Chinatown.
- Designed Cantonese-language survey questionnaires and interview protocols for engagement with Cantonese-speaking residents.
- Conducted resident interviews in Cantonese.
- Contributed to stakeholder engagement, qualitative data collection, policy analysis, and community-centered planning recommendations.

#### Mapping Urban Heat Inequality in Boston: Integrating Affordable Housing, Income, and Bluebikes Access

*Fall 2025 · UEP 237: Urban Analytics · Research Paper · Tufts University · Instructor: Professor Shan Jiang · Presented at AAG 2026*

- Constructed a Boston census-tract-by-month panel integrating ERA5-Land temperature, Bluebikes trip records, HUD LIHTC developments, ACS socioeconomic indicators, and tree-canopy measures.
- Conducted GIS-based spatial analysis and origin-destination flow mapping using kepler.gl.
- Estimated tract fixed-effects panel regression, pooled OLS with socioeconomic controls, interaction models, and exploratory GWR.
- Found that a 1°C increase in county-average monthly temperature was associated with approximately 7.2 additional Bluebikes trips per 1,000 residents within the same census tract (p < 0.01).
- Identified a weaker temperature-ridership association in neighborhoods with higher minority population shares (interaction β ≈ -5.04, p < 0.05).
- Examined heat-related vulnerability across neighborhoods including Roxbury, Dorchester, Chinatown, and East Boston.

#### Does Gender and Marital Status Affect Workplace Inequality?

*Spring 2025 · EC 202: Econometrics · Tufts University · Instructor: Professor Matthew Gudgeon*

- Analyzed China Family Panel Studies data from 2010–2022, with approximately 149,000 regression observations.
- Examined gender and marital-status disparities in real annual earnings.
- Estimated high-dimensional fixed-effects regressions with year and county fixed effects, individual-clustered standard errors, and gender-marital-status interactions.
- Found a substantial female earnings disadvantage in the baseline model (β = -9,037 RMB, p < 0.01).
- Identified an additional negative female-marital-status interaction (β = -2,458 RMB, p < 0.01).
- Found stronger negative gender-marital-status associations in urban than rural areas (β = -3,929 versus -2,299 RMB, both p < 0.01).

#### School Financial Reform and Income Inequality

*Spring 2025 · EC 144: Income Inequality · Tufts University · Instructor: Professor Elizabeth Setren*

- Constructed a U.S. state-year panel comprising 1,010 observations from 1990–2018.
- Integrated Census and school-finance data to investigate relationships between school-finance reforms and state-level household income.
- Applied Difference-in-Differences using reform-state and post-2000 indicators with demographic and socioeconomic controls.
- Examined pre-treatment trends and conducted placebo tests.
- Implemented propensity-score matching combined with Difference-in-Differences as a sensitivity analysis.
- Found approximately 2.6% lower average household income in reform states during the post-2000 period (β = -0.0259, p < 0.01), with a similar estimate after matching (β = -0.0226, p < 0.01).
- Interpreted the estimates cautiously because reform timing varied across states.

#### Construction of ℝ Using Cauchy Sequences of Rational Numbers

*Fall 2024 · MATH 135: Real Analysis I · Tufts University · Instructor: Professor Nima Hoda*

- Constructed the real number system through equivalence classes of Cauchy sequences of rational numbers.
- Defined equivalence of Cauchy sequences and proved reflexivity, symmetry, and transitivity.
- Examined the well-definedness of addition and multiplication on equivalence classes.
- Developed a proof of the Archimedean property of ℝ using boundedness of Cauchy sequences and the Archimedean property of ℚ.
- Established the density of rational numbers in ℝ through rational approximations and convergence arguments.
- Investigated completeness using a diagonal-sequence construction.

#### Introduction to Markov Chains and Stochastic Decision-Making

*Fall 2023 · Math 4997W: Senior Project (Writing Intensive) · University of Minnesota Twin Cities · Supervisor: Professor Sergey Bobkov*

- Analyzed discrete- and continuous-time Markov chains using transition probability matrices, transition-rate matrices, stationary distributions, recurrence times, and absorbing states.
- Applied absorbing Markov-chain methods to a manufacturing process and calculated an approximately 18.25% probability of a part being scrapped.
- Analyzed a light-bulb replacement model using stationary distributions and mean recurrence times.
- Calculated that exactly one bulb operates approximately 28.17% of the time and that the expected interval between replacements is 71 days.
- Derived asymptotic expressions for the coupon collector problem, obtaining expected collection time of approximately \(N \log N\) and variance of approximately \((\pi^2/6)N^2\).
- Examined additional continuous-time inventory and queueing applications.

#### What is the relationship between inequality and GDP growth?

*Fall 2021 · ECON 4331W: Economic Development · University of Minnesota Twin Cities · Instructor: Jacob Strauss*

- Examined relationships between income inequality and GDP per capita growth across countries, with particular attention to the United States and China.
- Used World Bank indicators including GDP per capita growth, Gini coefficients, adjusted net national income, labor-force measures, and education expenditure.
- Estimated a multivariable linear regression using 1,310 observations.
- Examined residual plots, normal Q-Q plots, leverage, and scale-location diagnostics.
- Found a statistically significant negative association between the Gini coefficient and GDP per capita growth (β = -0.069, SE = 0.014, p < 0.01).
- Discussed the limited explanatory power of the specification (R² = 0.057) and potential endogeneity.

## Technical Skills and Research Methods

- **Programming and data:** R, Stata, Python, MATLAB, Dynare; Hugging Face (Datasets, Spaces), AI chatbot development, API integration, Excel, GitHub, Jupyter, Google Colab, LaTeX.
- **Geographic analysis:** ArcGIS Pro, ArcGIS StoryMaps, QGIS, CARTO, Kepler.gl; SQL and ArcGIS Pro attribute queries; spatial joins; network accessibility analysis; service areas; least-cost paths; raster analysis; weighted overlay; zonal statistics.
- **Econometric and spatial methods:** Panel-data regression, OLS, logistic regression, difference-in-differences (DiD), event studies, propensity-score matching, TWFE/HDFE, instrumental variables (IV/2SLS), regression discontinuity, spatial econometrics, Global and Local Moran’s I (LISA), geographically weighted regression (GWR).
- **Macroeconomic and stochastic modeling:** Dynamic general-equilibrium modeling, Real Business Cycle models, New Keynesian models, dynamic programming and Bellman equations, discrete- and continuous-time Markov chains.
- **Languages:** Cantonese (native); English, Mandarin, and Southern Min Hokkien (fluent).

---

For teaching experience, academic service, and additional professional experience, please see my [Curriculum Vitae](/cv/). You can also visit my [Teaching](/teaching/) and [Conference Presentations](/talks/) pages, or [contact me by email](mailto:Ka_Lok.Kwok@tufts.edu).
