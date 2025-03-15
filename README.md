# Data Breach Analysis - Exploratory Data Analysis (EDA)

## Project Overview
This project performs an exploratory data analysis (EDA) on a dataset containing data breach incidents. The dataset includes details such as breach types, affected organizations, states, and incident descriptions. The analysis involves data cleaning, visualization, and textual analysis.

## Dataset
- **Source:** [Public Repository](https://privacyrights.org/data-breaches)
- **Attributes:**
  - Type of breach
  - Type of organization
  - State
  - Year of breach
  - Description of incident

## Project Objectives
- Clean and preprocess the dataset
- Generate visualizations to understand breach patterns
- Perform textual analysis on incident descriptions

## Steps Involved
1. **Data Cleaning:**
   - Remove unnecessary columns
   - Handle missing values
   - Remove duplicates
2. **Data Grouping & Aggregation:**
   - Group data by breach type and organization type
3. **Visualizations:**
   - Pie charts for breach types and organization types
   - Bar charts for top 5 breach states
   - Boxplots for breach trends
4. **Text Analysis:**
   - Text preprocessing (stopword removal, lowercasing, punctuation removal)
   - Generate a WordCloud of frequently occurring words

## Key Findings
- Certain states experience higher breach incidents.
- Specific breach types are more prevalent.
- Common keywords in descriptions provide insights into breach causes.

