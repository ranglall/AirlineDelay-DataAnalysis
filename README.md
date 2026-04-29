# Airline Delay Analysis (2015)

## ℹ️ Overview
This project explores and models the factors contributing to airline delays using a comprehensive dataset from 2015. The analysis uses advanced statistical techniques, including Exploratory Factor Analysis (EFA) and Structural Equation Modeling (SEM), to identify latent patterns and predictive variables within flight data.

---

## 💡 Key Methodology & Data Processing
**Data Sampling:** 
* The original dataset contained over one million cases, which presented significant computational challenges for visualization and report generation (knitting). To ensure efficiency and technical stability, the analysis was focused specifically on data from January 2015.
* To incorporate qualitative airline data into the statistical models, the `AIRLINE` character variable was transformed into a binary numeric variable: `Top50`. This categorizes carriers based on whether they are ranked in the top 50 airlines globally, enabling more robust data analysis.
**Data Analysis:**
* Conducted initial data anlysis, Exploratory Factor Analysis, and Structural Equation Modeling.
**Variable Mapping:**
* `Variable Chart.jpg` is a simple chart that maps variables and their relationships

---

## 🤖 Technologies Used
* **Language:** R
* **Key Libraries:** * `corrplot`: Used for correlation matrix visualization to identify initial relationships between variables.
    * Specialized packages for EFA and SEM modeling.

---

## 💡 Repository Structure
The repository is organized by analysis phase, with both source code (`.Rmd`) and rendered reports (`.html`) available for each:

* **Initial Analysis**
  * `DataSet -Initial Analysis.html` / `.Rmd`: Preliminary data cleaning, summary statistics, and trend identification.
* **Exploratory Factor Analysis (EFA)**
  * `EFA (Exploratory Factor Analysis).html` / `.Rmd`: Analysis used to uncover the underlying structure of the delay variables.
* **Structural Equation Modeling (SEM)**
  * `SEM (Structural Equation Modeling).html` / `.Rmd`: Confirmatory analysis used to test the relationships between observed variables and latent constructs.
* **Visuals**
  * `Variable Chart.jpg`: A reference guide for the dataset variables.

---

## 🚀 Usage Instructions
1. **View Reports:** Open the `.html` files in any web browser to view the finalized analysis, including visualizations and statistical output.
2. **Run Analysis:** To reproduce the findings, open the `.Rmd` files in RStudio. Ensure you have the `corrplot` library and necessary SEM/EFA packages installed.
3. **Data Note:** Ensure the source data is placed in the project directory before knitting the RMarkdown files.
