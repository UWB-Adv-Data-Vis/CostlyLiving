# CostlyLiving
The Cost of Living: Gross Rent as a Percentage of Household Income in the United States

The data dashboard challenge for the Autumn 2025 BIS 412 Advanced Data Visualization course with Prof. Trujillo. The challenge uses data from the U.S. Census Bureau American Community Survey (ACS) to develop interactive data visualizations to illumniate patterns in the the rising cost of living.

### Team

-   📊 Challenge created by and made for the BIS 412 [Advanced Data Visualization](https://github.com/UWB-Adv-Data-Vis) course at the [University of Washington Bothell](https://www.uwb.edu/).

-   ✍️ Authored by [Anum R.N.K.](https://github.com/AnumRNK04) and [Laila O.](https://github.com/Laila273)

-   🔍 Challenge review committee: [Anum R.N.K.](https://github.com/AnumRNK04), [Albany G.](https://github.com/Albanygarciag), [Dylan W](https://github.com/dwuu10), [Ryan M.](https://github.com/glfmoch), [Marcus L.](https://github.com/marcusxli), [Sebastain T.](https://github.com/Sthors7), [Nuhshire J.](https://github.com/Nuhshire), [James C.](https://github.com/sudo-uwjames),and [Aiden L.](https://github.com/aidenluo04)

-   🛠️ Edited and supervised by Prof. [Caleb Trujillo](https://github.com/calebtru).
### Learning Objectives
In this assignment you will demonstrate your ability to:

*    Prepare data by appropriately formatting it for analysis, summarizing, and filtering. For example, organize real-world data using a standard file format (CSV) and organizational approaches (Tidy).
*    Answer meaningful research questions using the tools in one or more software packages to work with authentic data.
*    Be capable of running, modifying, and sharing scripts to accomplish analyze data and visualize in one scripting language (R).
*    Manage project development to store, organize, and track code using digital collaboration tools for reproducibility (GitHub).
*    Create a data dashboard for the web to disseminate findings and visualization (R Shiny)
*    Describe the rationale, methods, results, and broader social context of your student-led project that used data to answer an interesting question.
*    Describe and use different types of critical and scientific thinking to develop inquiry into selected projects and critique visualizations.

## Overview
This project looks at data from the U.S. Census Bureau's 2023 survey, specifically how much of their income renters spend on housing. The data shows what percentage of income people pay for rent and utilities across all U.S. states.

Housing costs have become a major sign of inequality in America.
Housing costs have risen faster than wages in most U.S. markets over the past twenty years.
The COVID-19 pandemic made many of these trends worse, with remote work changing where
people live and increasing competition in some housing markets. Recent data shows that nearly
half of American renters are cost-burdened, with low-income households facing the biggest
challenges. This crisis affects people's ability to move up economically, their health, and their
quality of life.
Many families now spend more than 30% of their income on rent. The U.S. Department of Housing and Urban Development calls this being "*rent burdened*." When households spend 50% or more, they are "*severely rent burdened*."

This challenge asks teams to turn complex census data into a clear, easy-to-use dashboard using R Shiny and ggplot2. The dashboard should help users see how rent burdens differ by location.



## Intent of the Dashboard
The dashboard will help users explore the data and find information. Users should be able to quickly see which states have the biggest rent problems, understand regional patterns, and see how inequality shows up in housing costs. The dashboard will show patterns in the data while giving enough background for users to understand housing affordability in different areas.

## Data Challenge Statement
Housing costs have become one of the most visible indicators of inequality in the United States. Many families now spend more than 30% of their income on rent, a level defined by the U.S. Department of Housing and Urban Development as “*rent burdened*.”

The challenge is to transform large and complex ACS datasets into a clear, intuitive, and interactive dashboard that helps users explore how rent burdens vary by state and change over time. This requires effective data wrangling, careful normalization (to adjust for inflation and income changes), and thoughtful visual design to avoid misrepresentation.

### Why This Challenge Matters:
 - Housing affordability affects millions of Americans' quality of life and financial security
 - Rent burden has gotten much worse in recent years
 - Complex census data needs to be turned into visuals that everyone can understand
 - Understanding geographic patterns can help guide policy decisions

### What We Hope to Learn:
 - Which states and regions have the worst rent affordability problems
 - How rent burden connects to other economic factors
 - Whether there are surprising patterns that go against common assumptions
 - How well data visualization can explain complex social issues

## Purpose 
To visually communicate rent affordability across the U.S. through clear visuals and encourage discussion about the housing crisis.

## Stakeholders:
 - Policymakers and city planners working on housing policies
 - Economists and researchers studying income inequality and cost of living
 - Non-profit groups and housing advocates
 - Students and the general public interested in social issues
 - Real estate professionals

## Targeted Questions for Visual Analytics
The dashboard should answer these key questions through visuals:
 1. **State Comparison**: Which U.S. states have the highest and lowest percentages of renters spending 30% or more of their income on rent? Which states have the most severly burdened residence(50% or more)?
 2. **Regional Patterns**: How does rent burden vary by U.S. region (West, South, Midwest, Northeast)? Are there clear geographic clusters?
 3. **Distribution Analysis**: What is the full breakdown of rent burden across states? How many renters fall into each category (0-20%, 20-30%, 30-40%, 40-50%, 50% or more)?
 4. **Economic Relationships**: What patterns show up when comparing state-level rent burden to median household income? Do higher-income states have lower rent burdens, or is it more complicated?
 5. **Ranking**: Can users quickly identify the top 10 most and least affordable states for
renters?


## Design Principles:
 - Keep it simple but informative: focus on 1-2 strong visualizations per person/tab
 - Clear labels, details-demand, and notes for more information
 - Same color scheme across all panels
 - Works on different screen sizes
 - Follow ggplot2 best practices
 - Please replace this README with one for your produced dashboard and include alink to the original challenge.

## Project Plan:
Week-phase planned tasks with goals are listed.

### Week 1 –
Design, Ideation, and Planning
 - Review data structure and assign roles
 - Brainstorm research questions
 - Sketch dashboard layout
 - Download and inspect ACS B25070 data 

Goal: Finalized dataset and clear dashboard objectives

### Week 2 –
Prototype, Testing, Concepts
 - Create first draft visuals (ggplot charts, tables)
 - Refine labels, titles, and axes
 - Compare map and bar chart options
 - Develop layout

Goal: Prototype visuals ready for peer review

### Week 3 –
Build, Coding, and Refinement
 - Process and summarize data
 - Add filters for year and state
 - Check for errors and debug

Goal: Working interactive dashboard without bugs

### Week 4 -
Deploy, Testing, and Presentation
 - Conduct user testing
 - Refine aesthetics and layout
 - Gather feedback from peers
 - Publish final dashboard and present results

Goal: Polished, published dashboard ready for
presentation

## Data Biography
### *Dataset: U.S. Census Bureau American Community Survey (ACS) Table B25070*
Our main dataset is Table B25070: "Gross Rent as a Percentage of Household Income in the Past 12 Months" from the 2023 ACS 5-Year Estimates. This table comes from the Census Bureau's biggest ongoing survey of American households, collecting detailed information about people, economics, and housing from over 3.5 million addresses every year. The American Community Survey replaced part of the census in 2010 and gives us the most current detailed picture of America's changing population and housing. The 5-year estimates combine data from 2019-2023, which gives us reliable data even for smaller areas and groups. Unlike 1-year estimates, 5-year data is more stable and less variable, making it perfect for comparing states.

## Understanding Table B25070:
This table measures "gross rent" as a share of household income. Gross rent includes:
 - Contract rent (the amount paid to the landlord)
 - Utilities (electricity, gas, water, sewer)
 - Fuels (oil, coal, kerosene, wood)

The table breaks down renters into categories based on what percentage of their household income goes toward these costs:
 - Less than 10%
 - 10.0 to 14.9%
 - 15.0 to 19.9%
 - 20.0 to 24.9%
 - 25.0 to 29.9%
 - 30.0 to 34.9%
 - 35.0 to 39.9%
 - 40.0 to 49.9%
 - 50.0% or more
 - Not computed (includes households with no income or negative income)

The 30% threshold has been the federal standard for housing affordability since 1981, set by HUD. Households paying more than 30% of income on housing are considered "cost-burdened" because they may struggle to afford other necessities like food, healthcare, and transportation. Those paying 50% or more are "severely cost-burdened."


## Data Accessibility and Quality:
The ACS data is available to everyone through several sources:
 - Census Bureau's data.census.gov website
 - Census Reporter (censusreporter.org) - provides user-friendly tables and visualizations
 - (tidycensus)[https://cran.r-project.org/web/packages/tidycensus/index.html] R package - allows direct access for research
The data includes margins of error for all numbers, so researchers can check how reliable the data is. For state-level analysis, the 5-year estimates have good sample sizes with relatively small margins of error.

## Historical Context
Rent burden has been a growing concern since the 1960s but has gotten worse since 2000. Key factors include:
 - Wages staying flat for low and middle-income workers
 - Rising construction costs and restrictive zoning laws limiting housing supply
 - More demand in cities where jobs are concentrated
 - Less federal funding for affordable housing programs
 - After the 2008 foreclosure crisis, many owner-occupied homes became rentals

## Geographic Patterns
Early research suggests rent burden is highest in:
 - Coastal cities (California, New York, Florida)
 - Tourism areas with limited year-round housing
 - Areas with rapid population growth outpacing new housing
 - States with high living costs but service-sector wages
On the other hand, states in the Midwest and some Southern regions tend to show lower rent burdens because housing costs less compared to incomes.

## Limitations
While thorough, the ACS data has some limits:
 - Sampling error: Smaller groups may have wider margins of error
 - Missing data: Some households don't report income, listed as "not computed"
 - Scope: Data only covers renters, not homeowners with mortgages
 - Timeliness: 5-year estimates are several years behind current conditions
 - Self-reporting: Data relies on survey responses, which may have reporting bias

Despite these limits, the ACS is still the best source for housing affordability research and is used by HUD, researchers, and policy organizations nationwide.

## Additional Data Sources 
To provide more context, we may include: HUD Fair Market Rent data, Bureau of Labor Statistics wage data by state, State-level cost of living measures, and Population and demographic information from other ACS tables.

## Sources
* Census tabulation detail: Gross Rent as a percentage of household income. Census Reporter.(n.d.). [https://censusreporter.org/tables/B25070/]
* Consolidated Planning/CHAS Data | HUD USER. (n.d.). [https://www.huduser.gov/portal/datasets/cp.html]
* U.S. Census Bureau. (2023). American Community Survey 5-Year Estimates, Table B25070: Gross Rent as a Percentage of Household Income in the Past 12 Months. Retrieved from [https://data.census.gov]
* U.S. Department of Housing and Urban Development. (n.d.). Affordable Housing. [https://www.hud.gov/program_offices/comm_planning/affordablehousing/]
* Walker K, Herman M (2025). tidycensus: Load US Census Boundary and Attribute Data as 'tidyverse' and 'sf'-Ready Data Frames. R package version 1.7.3, [https://github.com/walkerke/tidycensus].
