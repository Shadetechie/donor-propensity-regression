# donor-propensity-regression
Exploratory Data Analysis and Logistic Regression model predicting donor likelihood to give for Advancement fundraising outreach.

# Donor Likelihood-to-Give Propensity Model (EDA & Logistic Regression)

## 1. Business Problem & Advancement Context
Fundraising and Advancement teams have limited gift officer capacity for outreach, calls, and regional travel. Rather than contacting every constituent equally, this project uses historical donor attributes to predict **likelihood to give (0 to 100% probability)** so fundraisers can prioritize high-propensity prospects.

## 2. Dataset Overview
- **Source:** Finding Donors for Charity; https://www.kaggle.com/datasets/nancyalaswad90/finding-donors-for-charityml?select=census.csv
- **Sample Size:** Rows, Columns (45222, 14)
- **Target Variable:** `gave_flag` (`1` = Donated, `0` = Did Not Donate)
- **Key Features Analyzed:** age, education num, capital gain, capital loss, hours worked
