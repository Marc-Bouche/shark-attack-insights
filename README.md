# Shark Attacks Data Wrangling Quest

Welcome to the **Shark Attacks Data Wrangling Quest**! This project focuses on cleaning and analyzing a messy dataset titled "Shark Attacks" to prepare it for meaningful analysis and insights. 

## Overview

This project is part of a quest to advance Python programming skills, practice data wrangling techniques, and develop teamwork and problem-solving abilities. By cleaning the dataset, we aim to derive insights related to shark attack patterns and validate hypotheses.

---

## Hypotheses

### Hypothesis 1:
*Unprovoked shark attack incidents have a lower fatality rate than provoked incidents.*

### Hypothesis 2:
*Great White Sharks are most likely to attack in the USA.*

---

## Dataset

The dataset is sourced from the [Global Shark Attack File](https://www.sharkattackfile.net/spreadsheets/GSAF5.xls) and contains information on shark attack incidents worldwide.

### Key Dataset Features:
- **Date**: The date of the incident.
- **Type**: Whether the incident was provoked or unprovoked.
- **Injury**: A description of the injury sustained.
- **Species**: The species of shark involved (if identified).
- **Location**: Where the incident occurred.

---

## Technologies Used

- **Python**: For data wrangling, cleaning, and analysis.
- **Pandas**: For data manipulation and cleaning.
- **Jupyter Notebook**: For implementing the project in a collaborative coding environment.
- **xlrd**: To handle Excel files.

---

## Cleaning and Wrangling Steps

1. **Missing Data**: 
   - Removed rows with all `NaN` values.
   - Dropped duplicate rows.

2. **Formatting Inconsistencies**:
   - Standardized values in the `Type` and `Injury` columns.
   - Cleaned and grouped shark species names in the `Species` column.

3. **Filtering Data**:
   - Segregated incidents into fatal and non-fatal cases.
   - Differentiated between provoked and unprovoked incidents.

4. **Data Aggregation**:
   - Created summary tables for fatal and non-fatal incidents based on provocation type.
   - Validated hypotheses using pivot tables and grouped data.

---

## Analysis

### Hypothesis 1:
We analyzed the fatality rates of unprovoked versus provoked shark attacks to determine if the fatality rate differs significantly.

### Hypothesis 2:
We cleaned and grouped the shark species data to identify which shark species (e.g., Great White Shark) are most likely to attack in the USA.

---

## Results

### Key Findings:
- Unprovoked shark attacks have a distinct fatality rate compared to provoked incidents.
- Great White Sharks are a leading species involved in attacks within the USA.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Shark_Attacks_Data_Cleaning.git
