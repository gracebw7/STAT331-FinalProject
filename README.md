# STAT331-FinalProject

Author 1: Grace Boye-Williams ([gboyewil\@calpoly.edu](mailto:gboyewil@calpoly.edu){.email}) Author 2: Nidhi Sathish ([npsathis\@calpoly.edu](mailto:npsathis@calpoly.edu){.email})

# The Data

In this lab, we will use two datasets related to jobs, salaries, and cost of living in the United States.

The first dataset includes linkedin job postings taken from 2023-2024 and includes information such as job title, industry, company, salary estimates, location and job level. Since the data was taken from real job postings, many variables may contain missing values or inconsistent formatting, especially salary information and job titles.

[LinkedIn Dataset](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)

The second dataset contains estimated cost of living information for counties and metro areas across the United States. This includes cost related to housing, healthcare, food, transportation and median income. This dataset allows for comparison between salaries and living costs across different locations.

[Cost of Living Dataset](https://www.kaggle.com/datasets/asaniczka/us-cost-of-living-dataset-3171-counties)

## Variables from the LinkedIn dataset

-   `job_id`: Unique identifier for each job posting as defined by LinkedIn
-   `title`: Title of the job posting
-   `city`: City where the job is located
-   `state`: State where the job is located
-   `normalized_salary`: Normalized annual salary for the job posting, standardized from hourly, monthly, or yearly raw text
-   `currency`: Currency in which the salary is provided, e.g. USD
-   `company_name`: Name of the hiring company
-   `company_id`: Unique identifier for the company associated with the job posting

## Variables from the Cost of Living dataset

-   `state`: state where the county is located
-   `county`: county name
-   `isMetro`: whether the county is part of a metropolitan area
-   `family_member_count`: family structure used for the estimate
-   `housing_cost`: estimated yearly housing expenses
-   `food_cost`: estimated yearly food expenses
-   `transportation_cost`: estimated yearly transportation expenses
-   `healthcare_cost`: estimated yearly healthcare expenses
-   `total_cost`: estimated total yearly cost of living
-   `median_family_income`: estimated median family income for the area

The goal of this lab is to practice data wrangling, joins, vectorized functions, grouped summaries and visualization techniques in R. Some of the main challenges in this lab include handling missing salary values, cleaning inconsistent job categories, as well as combining datasets using geographic information.

Data dictionaries and variable descriptions can be found on the Kaggle dataset pages linked below.
