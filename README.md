# Death Penalty Across the United States 

**Authors**: Ryan Lin, Luke Bobosky, Owen Braun, Runjie Yang  
**Date**: 2023-05-05  

## Project Overview

This project examines the trends in death penalty executions across the United States between 1977 and 2023. Our goal was to investigate underlying factors that contribute to the likelihood of receiving the death penalty. Specifically, we explored how race, sex, region, and other demographic variables correlate with execution rates. We also analyzed the role of political affiliation and trends over time to gain a deeper understanding of the systemic factors influencing the death penalty in the U.S.

## Table of Contents

1. [Introduction](#introduction)
2. [Project File](#Project-file)
3. [Data Source](#data-source)
4. [Data Wrangling](#data-wrangling)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Findings](#findings)


---

## Introduction

The death penalty has long been a controversial topic in the United States. This project aims to identify trends that influence death penalty outcomes by analyzing various factors such as race, sex, geographic location, and political affiliation. We also examine how the death penalty has evolved over time, looking at the peak execution rates around the year 2000 and the subsequent decline.

---
## Project File

---

## Data Source

We utilized the **Execution Database - U.S. Executions** dataset, compiled by the Death Penalty Information Center (DPIC). This dataset contains information on individuals executed in the U.S. from 1977 to 2023, including:

- Date of execution
- Race and sex of the individual
- Region and state of execution
- Number of victims
- Information on victims' race and sex

The dataset focuses on 1566 individuals who have been executed, while over 2500 remain on death row.

---

## Data Wrangling

Several key steps were taken to clean and prepare the data for analysis:

1. **CSV to DataFrame**: The data was imported from CSV into R.
2. **Date Formatting**: Execution dates were converted to a usable year format.
3. **Data Cleaning**: Inconsistencies in the 'Sex' and 'Race' columns were resolved (e.g., handling of space characters, standardizing race categories).
4. **Subsetting**: Sub-datasets were created by grouping key variables such as race and sex.

---

## Exploratory Data Analysis

### Executions Over Time
The data shows that executions peaked around the year 2000, following a bell curve, with a decline after that period due to legal reforms and shifting public opinion.

### Sex and Race Trends
- Male executions dominate the data, though female executions have occurred.
- Whites and Blacks are the largest groups affected, with Whites making up 56% of executions and Blacks 35%.

### Geographic Distribution
The South, particularly Texas, has the highest execution rates, while many states have outlawed the death penalty.

### Victim Analysis
Most executions involve crimes with a single victim, with white female victims being the most common.

---

## Findings

1. **Executions follow a bell curve**: Peaks in 2000 followed by a decline.
2. **Racial trends**: White individuals make up the majority of those executed.
3. **Geographic trends**: The South leads the country in executions.
4. **Volunteering for execution**: Inmates in the South and Midwest are more likely to volunteer for execution.

---

## How to view this Project




