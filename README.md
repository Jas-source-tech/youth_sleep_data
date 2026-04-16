# Project: Importance of Sleep During Puberty

---

## 1. Data Description & Sources

The data for this analysis was sourced from the official Statistics Canada database. It focuses on the health, lifestyle, and sleep characteristics of Canadian youth.

### Data File 1: `13100763.csv`
* **Source:** Statistics Canada. Table 13-10-0763-01 - Canadian Health Survey on Children and Youth (CHSCY), indicators of physical and mental health.
* **Content:** Percentages of youth experiencing various health outcomes, including "Difficulties in getting to sleep" and "Perceived mental health, fair or poor," segmented by age group and province.
* **Format:** Long-format CSV.

### Data File 2: `13100969.csv`
* **Source:** Statistics Canada. Table 13-10-0969-01 - Meeting 24-Hour Movement Guidelines for Children and Youth.
* **Content:** Data on the percentage of Canadian youth meeting recommendations for physical activity, recreational screen time, and sleep duration.
* **Format:** Long-format CSV.

---

## 2. Prerequisites & VS Code Setup

To run the analysis code, you will need the following installed:
1. **Visual Studio Code (VS Code)**
2. **Python** 

**VS Code Extensions Required:**
* Python (Official extension by Microsoft)
* Jupyter (Official extension by Microsoft)

---

## 3. Required Python Libraries

The code relies on several standard data science packages. Open your VS Code integrated terminal and run the following command to install them:

`pip install pandas matplotlib seaborn scipy statsmodels ipykernel`


---

## 4. How to Run the Code

1. **Step 1:** Ensure all files are in the same directory.
2. **Step 2:** Open the folder in VS Code.
3. **Step 3:** Open the `sleep_analysis.ipynb` file.
4. **Step 4:** In the top right corner of the notebook interface, click **"Select Kernel"** and choose your Python environment.
5. **Step 5:** Click the **"Run"** button on the cell containing the code, or click inside the code block and press `Shift + Enter`.

---

## 5. Expected Outputs

Upon successful execution, the script will automatically process the CSV files and output the following directly inside your VS Code window:

### 1. Visualizations
* A grouped bar chart comparing the percentage of children (5-11) vs. adolescents (12-17) meeting sleep, physical, and screen guidelines.
* A scatter plot with a regression line showing the provincial correlation between sleep difficulties and poor mental health.

### 2. Statistical Outputs
* The **Pearson Correlation Coefficient (r)** and p-value.
* The **T-Statistic and p-value** from a Paired T-Test (confirming the difference in sleep difficulties before and during puberty).
* An **Ordinary Least Squares (OLS) Regression** summary table predicting mental health outcomes based on sleep difficulty variance.
