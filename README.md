# Predicting House and Apartment Prices
Project related to extracting information from a website (www.encuentra24.com) for subsequent analysis.

## Overview

This project analyzes real estate prices in Guatemala to understand market trends and develop predictive models. It focuses on properties within the Q400,000 to Q2,000,000 range, examining both houses and apartments.

## Objectives

- Extract and clean real estate data from online sources.
- Perform exploratory data analysis (EDA) to uncover patterns in prices and features.
- Evaluate the impact of location on prices using statistical methods like ANOVA.
- Develop a predictive model to accurately forecast property prices.

## Methodology

1. **Data Extraction and Cleaning:** Using Selenium and BeautifulSoup for web scraping, followed by data cleaning with pandas.
2. **Geographical Analysis:** Determining municipality and zone from property titles.
3. **Descriptive Analysis:** Utilizing visualizations to explore price distributions and key feature correlations.
4. **Predictive Modeling:** Planning phase for building regression models.

## Structure

- **data/**: Contains raw and cleaned datasets.
- **notebooks/**: Jupyter notebooks for analysis and modeling.
- **reports/**: Contains generated reports and visuals.
- **scripts/**: Automation scripts for data processing.

## Setup

To reproduce the analysis, ensure you have the required Python libraries installed. Use the following command to install dependencies:

```bash
pip install -r requirements.txt
