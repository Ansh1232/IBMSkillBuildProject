# Tele-Law Case Registration: An Analysis of Demographic and Regional Disparities

### *A project for the IBM SkillsBuild Data Analyst Internship Program*

---

## 📖 Project Overview

This project analyzes case registration data from India's **Tele-Law program**, an initiative to provide legal aid to marginalized communities through Common Service Centers (CSCs). The goal is to identify and understand disparities in service utilization based on **gender**, **caste**, and **geography**. By uncovering these patterns, the analysis aims to provide data-driven insights for improving the inclusivity and effectiveness of legal aid delivery across the country.

---

## 📜 Problem Statement



> Despite the expansion of the Tele-Law initiative across states and districts, there is limited understanding of demographic utilization patterns and regional disparities in legal aid access. The challenge is to analyze Tele-Law case registration data to uncover gender-wise, caste-wise, and geographic disparities in service utilization across CSCs. Uneven representation among marginalized groups (SC, ST, OBC) and low outreach in certain districts raise concerns about equity and effectiveness...

---

## 📊 Dataset

The dataset used for this analysis is the **"District-wise Tele-Law Case Registration and Advice Enabled Data for FY 2021-22 to 2024-25"**.

- **Source:** [data.gov.in](https://www.data.gov.in/resource/district-wise-tele-law-case-registration-and-advice-enabled-data-fy-2021-22-2024-25)
- **Content:** The data contains aggregated case registration counts broken down by district, state/UT, gender (Male/Female), and caste category (General, OBC, SC, ST). It also includes the number of active CSCs in each district.

---

## 🛠️ Methodology & Technologies Used

The analysis was conducted using a Jupyter Notebook and the following technologies:

- **Data Storage:** **IBM Cloud Object Storage** was used to host the dataset, fulfilling a key project requirement.
- **Data Analysis:** **Python** with the **Pandas** library for data manipulation and aggregation.
- **Data Visualization:** **Matplotlib** and **Seaborn** for creating charts and heatmaps to visualize the findings.
- **Development Environment:** Jupyter Notebook on IBM Watson Studio.

---

## 📈 Key Findings

The analysis revealed several key disparities:

1.  **Gender Disparity:** There is a significant gap in service usage, with **Male registrations (24.8 million) far outnumbering Female registrations (15.9 million)**.
2.  **Caste Disparity:** While OBC and SC communities show high engagement, the **Scheduled Tribes (ST) community has the lowest number of registrations (5.4 million)**, suggesting potential barriers to access.
3.  **Geographic Disparity:**
    -   **State-Level:** **Uttar Pradesh** has the highest number of total registrations by a large margin.
    -   **District-Level:** **22 districts reported zero registrations**, despite having active CSCs, indicating major gaps in service outreach or data reporting.
    -   **CSC Effectiveness:** When normalized by the number of CSCs, regions like **Delhi** and **Chandigarh** show the highest registration rates per center, indicating highly effective outreach.

---

## 🖼️ Visualizations

#### Gender and Caste Distribution
*(Here, you would add the screenshot of your pie chart and caste bar chart)*
![Gender and Caste Charts](path/to/your/chart_image.png)  #### Geographic Analysis: Top States and Caste-wise Heatmap
*(Here, you would add the screenshot of your combined bar chart and heatmap)*
![Geographic Charts](path/to/your/geo_image.png) ---

## 🚀 How to Use

1.  The complete analysis and code can be found in the `Tele-Law Data Analysis.ipynb` file.
2.  The notebook can be viewed directly in GitHub.
3.  To run the notebook, you would need to replace the placeholder credentials for the IBM Cloud Object Storage service with your own.
