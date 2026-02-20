# Top Investment Opportunities: Stock Market Web Scraper
This project implements an advanced data engineering tool designed to identify the top 10 investment opportunities in the stock market using Web Scraping and dynamic financial filtering.

### -- Project Overview --
- Automated extraction of financial data from nearly 2,000 top-performing companies over the last 3 years.
- Development of a search engine that navigates corporate profiles to extract key profitability metrics.
- Implementation of a filtering algorithm to select financial assets based on stability and growth criteria.

### -- Key Objectives --
- Develop a robust scraper capable of handling dynamic navigation and asynchronous web elements.
- Extract critical financial indicators: EPS (Earnings Per Share), PER (Price-to-Earnings Ratio), dividends, and foundation year.
- Automate the generation of an updated "Top 10" investment ranking for 2024.

### -- Tech Stack --
- Language: Python
- Web Automation: Selenium WebDriver (Chrome Headless mode)
- Data Manipulation: Pandas
- Network & API: Requests & Urllib
- Environment: Jupyter Notebook / Google Colab

### -- Methodology --
- Data Acquisition: Using Selenium to extract an initial list of 481 companies with high historical performance.
- Automated Profiling: Creation of modular functions (get_EPS, get_PER, get_dividend) that automatically visit each company's profile to collect specific data via XPATH queries.
- Data Cleaning & Filtering: Processing dates and numerical formats to normalize information and filter out companies that do not meet strict investment standards.
- Ranking Logic: Applying logical filters on the final DataFrame to obtain a refined selection of the 67 strongest companies and, ultimately, the Top 10.

### -- Results --
- Successful real-time extraction of detailed financial data from hundreds of corporations.
- Automated generation of a top_10_invest_2024.csv file, ready for financial analysts or visualization tools.
- Drastic reduction in market research time, transforming hours of manual searching into a few minutes of automated execution.
