#  LinkedIn Job Postings Data Analysis

A full-cycle data analysis project that merges and cleans multiple job and company datasets from LinkedIn, followed by exploratory data analysis (EDA) to extract meaningful insights about the job market.

---

##  Project Overview

This project focuses on analyzing job postings scraped from LinkedIn using multiple data files — job descriptions, skills, benefits, company size, and more. The analysis aims to uncover job trends, hiring patterns, company characteristics, and sponsored content distribution.

- **Dataset Source**: LinkedIn Job Postings Dataset(via scraping tutorial)
- **Tools Used**: Python, pandas, matplotlib, WordCloud

---

##  Data Collection & Preprocessing

- **Merged** multiple datasets including:
  - `job_postings.csv`, `job_skills.csv`, `benefits.csv`
  - `companies.csv`, `company_industries.csv`, `company_specialities.csv`, `employee_counts.csv`
- **Cleaned** duplicates and nulls, aggregated job skills and benefits by `job_id`.
- **Joined** job data with company data for enhanced context.
- **Renamed** and selected key columns like job title, company name, work type, location, and company size.

---

##  Exploratory Data Analysis (EDA)

Visualizations were generated to answer key business questions:

- **Word Cloud** of job titles to understand role frequency.
- **Pie Chart** showing distribution of company sizes.
- **Bar Chart** for job type breakdown (Full-time, Contract, etc.).
- **Sponsored vs. Non-Sponsored Listings** — analyzed marketing trends in job posts.

---

##  Key Insights

- **Most common job types** were full-time positions, followed by contracts and part-time roles.
- **Sponsored listings** accounted for a notable portion of job posts, indicating employer marketing investment.
- **Company sizes** ranged widely, with mid-sized firms dominating the dataset.
- **Job titles** suggested high demand in sales, engineering, and management roles.

---

##  Files Included

- `LinkedIn_Job_Postings_2023_Data_Analysis.ipynb`: Jupyter Notebook containing data preprocessing, merging, EDA, and visualizations.

---

##   Summary

> Merged and cleaned multi-source LinkedIn job and company data; visualized hiring trends and job type distributions using Python. Revealed insights on employer sizes, sponsored listings, and in-demand job titles through word clouds and distribution plots.


---
