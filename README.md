# Layoffs-Analysis: Exploring the Impact of Company Layoffs vs. Funds Raised

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Methodology](#methodology)
4. [Key Findings](#key-findings)
    - Companies with High Layoffs vs. Funds Raised
    - Industry Insights
    - Impact of Company Stage
    - Geographical Trends
5. [Conclusion](#conclusion)
6. [Further Exploration](#further-exploration)

---

## Introduction

This project analyzes the relationship between company layoffs and the amount of funding raised across various industries and countries. It aims to uncover trends, such as whether companies that raised significant funds managed to avoid layoffs, and how different factors like industry or company stage impact layoffs.

---

## Dataset Overview

The dataset used in this analysis contains records of layoffs from companies worldwide, including the following key fields:
- **Company**: Name of the company.
- **Location**: Headquarters of the company.
- **Industry**: Sector in which the company operates.
- **Total Laid Off**: Number of employees laid off.
- **Percentage Laid Off**: Percentage of the total workforce laid off.
- **Funds Raised**: Total funds raised by the company (in millions).
- **Stage**: Company's stage (e.g., Series B, Post-IPO).
- **Country**: Country where the company is located.

You can find the dataset in the [`data/layoffs.csv`](data/layoffs.csv) file.

---

## Methodology

The analysis was conducted using SQL queries and data manipulation techniques:
1. **Data Cleaning**: Removal of duplicates, handling missing values, and standardizing data (e.g., trimming company names and formatting dates).
2. **Exploratory Data Analysis**: SQL queries were used to explore trends in layoffs vs. funds raised, and data was grouped by company, industry, stage, and country.
3. **Visualization**: Key findings were visualized using charts to show the relationship between layoffs and other variables.

---

## Key Findings

### 1. Companies with High Layoffs vs. Funds Raised
The following companies experienced significant layoffs despite raising large amounts of capital:
| **Company** | **Total Laid Off** | **Funds Raised (in Millions)** | **Industry** | **Country** | **Stage** |
|-------------|--------------------|-------------------------------|--------------|-------------|-----------|
| Company A   | X employees         | Y million                     | Tech         | USA         | Series B  |
| Company B   | X employees         | Y million                     | Retail       | UK          | Post-IPO  |

### 2. Industry Insights
- **Technology** and **Real Estate** were the industries most affected by layoffs despite their companies raising substantial funds.

### 3. Impact of Company Stage
- **Series B** startups experienced moderate layoffs, indicating that even well-funded early-stage companies faced workforce reductions.
- **Post-IPO** companies, despite having raised large amounts of capital, experienced the highest percentage of layoffs, likely due to market pressures.

### 4. Geographical Trends
- **USA**: The largest concentration of layoffs was in the technology sector.
- **Europe**: Significant layoffs occurred in retail and media industries in countries like the UK and Germany.

---

## Conclusion

This analysis reveals that high fundraising does not guarantee protection from layoffs. Factors such as industry, company stage, and external market forces (e.g., economic conditions) heavily influence workforce reductions, regardless of available capital.

---

## Further Exploration

Potential areas for further analysis:
- **Layoffs by Department or Role**: Analyze which departments are most impacted during layoffs.
- **Longitudinal Trends**: Explore layoffs over time in relation to economic events.
- **Startup vs. Mature Companies**: Compare layoffs in early-stage startups vs. established firms to see if size and maturity affect layoff rates.

---

## Dataset

The dataset used for this analysis can be found in the [`data/layoffs.csv`](data/layoffs.csv) file. It contains detailed information on layoffs across companies worldwide, including industry, location, total laid off, and funds raised.
