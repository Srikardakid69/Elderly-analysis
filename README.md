# CA2 – Analysis of Elderly Population in Singapore

## Overview
This project analyzes the characteristics and distribution of the elderly population in Singapore using multiple public datasets from data.gov.sg. The study focuses on how elderly residents differ by age group, gender, ambulant status, ethnic group, housing type, town, marital status, and housing tenure over time.

The project was completed as part of **CA2** and uses Python-based data analysis and visualizations to uncover demographic and housing patterns among Singapore’s ageing population.

---

## Project Objective
The main objective of this project is:

**To analyze the distribution and living patterns of the elderly population in Singapore across demographic, mobility, housing, and regional factors over time.**

---

## Questions Explored
This project answers the following key questions:

1. What are the proportions of elderly of different age groups by year?
2. How does the gender distribution of elderly residents vary across different age groups?
3. What is the distribution of elderly across different ambulant status categories in the most recent year?
4. How does the distribution of elderly population percentages differ across ethnic groups over the years?
5. How does the distribution of elderly residents vary by flat type over the years?
6. How does the distribution of the elderly population vary across different towns over the years?
7. How does the marital-status composition of elderly residents differ by sex in the most recent year?
8. How has the distribution of elderly residents across housing tenure types changed between 2013 and the most recent year?

---

## Datasets Used
This project uses **7 datasets from data.gov.sg** related to:
- Elderly age group distribution
- Gender distribution of elderly residents
- Ambulatory / mobility status
- Ethnic composition of elderly
- Elderly by housing flat type
- Elderly by town / estate
- Housing tenure of elderly households

---

## Key Features
- Data cleaning and analysis using Python
- Time-based comparison of elderly population trends
- Demographic analysis by age, gender, and ethnicity
- Mobility analysis using ambulant status categories
- Housing analysis by flat type and tenure
- Regional comparison across towns and estates
- Data visualization through pie charts, donut charts, stacked bar charts, and heatmaps

---

## Tools & Technologies
- **Python**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## Key Findings
- The **65–69 age group** forms the largest share of the elderly population, though its share declines slightly over time, while the **75–79** and **80–84** groups grow steadily, showing an ageing elderly population. :contentReference[oaicite:1]{index=1}
- Most elderly in Singapore remain **physically independent**, with **87.3% ambulant and independent** in 2018, while only a very small fraction require major physical assistance. :contentReference[oaicite:2]{index=2}
- The **Chinese group** consistently forms the majority of Singapore’s elderly population, while Malay and Indian shares are much smaller. :contentReference[oaicite:3]{index=3}
- Most elderly residents live in **3-room and 4-room flats**, which together account for over 60% of elderly housing share across the years. There is also a gradual increase in elderly residents living in **5-room flats**. :contentReference[oaicite:4]{index=4}
- Estates such as **Hougang, Bedok, and Bukit Merah** have some of the highest elderly populations, and the ageing trend is visible across almost all towns. :contentReference[oaicite:5]{index=5}
- The vast majority of elderly households live in **sold flats rather than rental flats**, and the share living in rental flats declines over time. :contentReference[oaicite:6]{index=6}

---

## Example Insights

### 1. Ageing Within the Elderly Population
The results show that while younger elderly groups such as **65–69** and **70–74** remain the largest, older age groups are gradually increasing, indicating that Singapore’s elderly population is becoming older over time. :contentReference[oaicite:7]{index=7}

### 2. Mobility and Independence
A major insight is that most elderly residents are still mobile and independent, which suggests that many seniors continue to live actively within the community. :contentReference[oaicite:8]{index=8}

### 3. Housing Patterns
The project shows that elderly residents are concentrated mainly in **3-room and 4-room flats**, while smaller flat categories and executive flats form only a small minority. :contentReference[oaicite:9]{index=9}

### 4. Regional Differences
The heatmap analysis shows that some towns such as **Bedok, Hougang, and Bukit Merah** consistently have larger elderly populations compared to newer or smaller estates. :contentReference[oaicite:10]{index=10}

---

## How to Run
1. Open the Jupyter Notebook version of this project.
2. Install the required Python libraries:
   ```bash
   pip install numpy matplotlib
