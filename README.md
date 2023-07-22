# 🦄 Maven Unicorn Challenge

## 📚 About Data

Private companies with a valuation over $1 billion as of March 2022, including each company's current valuation, funding, country of origin, industry, select investors, and the years they were founded and became unicorns.

This dataset contains a csv table with 1,074 records, one for each company.

#mavenunicornchallenge

## 💡 Highlights

- Valuations in year 2021 makes up one-third of total valuations since the beginning of time.
- Unicorns in United States and China outperformed the rest of the world with 72% overall valuations.
- Bytedance, SpaceX, SHEIN and Stripe are the most successful unicorns which performed better than an average unicorn at $71 billion.
- Unicorns in AI, E-Commerce, Fintech and Edtech industries are valued higher than the average unicorn at $3.5 billion. 
- A unicorn takes an average of 7 years to attain valuation of $1billion and become a unicorn.

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Valuation` and `Funding` columns and cast as float
- Exclude rows with "Unknown" `Funding` values
- Explode `Select Investors` column into individual rows for categorical analysis

📍 Jupyter script: [Notebook](https://github.com/qarnov/unicorn_startups/blob/main/cleaning_unicorn_companies.ipynb)

📍 Clean Data: [unicorn_companies_clean.csv](https://github.com/qarnov/unicorn_startups/blob/main/clean_unicorn_companies.csv)

## 📊 Visualization

Produced a 1-pager dashboard using Tableau.

Tableau: [Link](https://public.tableau.com/app/profile/afdhal.abdel.qadir/viz/UnicornCompanies_16900400499610/Unicorns)

![Unicorns-2](https://user-images.githubusercontent.com/76422084/255338857-4f0d76d9-7787-4630-b11d-fe53400ded63.png)


