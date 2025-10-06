# EDA-Diwali-Sales-Analysis-Python

Analyze Diwali sales data to improve customer experience and sales

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#project-learning">project-learning</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes Diwali sales data to uncover customer purchasing behavior and key business trends. A complete analytics workflow was developed using Python for data cleaning, exploratory analysis, and visualization to identify high-performing product categories, customer segments, and regional sales patterns, enabling data-driven marketing and inventory strategies.

---
<h2><a class="anchor" id="project-learning"></a>project-learning</h2>

- Performed data cleaning and manipulation

- Performed exploratory data analysis (EDA) using pandas, matplotlib and seaborn libraries

- Improved customer experience by identifying potential customers across different states, occupation, gender and age groups

- Improved sales by identifying most selling product categories and products, which can help to plan inventory and hence meet the demands

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Format: CSV

- Rows: ~11,000

- Columns: Customer details, gender, age group, product category, amount spent, city tier, etc.

- Perfect for: EDA, customer segmentation, and visualization

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python – for data cleaning, transformation, and analysis

- Pandas – for data manipulation and preprocessing

- NumPy – for numerical operations

- Matplotlib & Seaborn – for data visualization and exploratory data analysis (EDA)

- Jupyter Notebook – for running and documenting the analysis

- Microsoft Excel – for quick data review and validation (optional)

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
Diwali_Sales_Analysis/
│
├── data/
│   └── Diwali_Sales_Data.csv              # Dataset used for analysis
│
├── notebooks/
│   └── Diwali_Sales_Analysis.ipynb        # Jupyter Notebook with full analysis
│
├── visuals/
│   └── sales_trends.png                   # Graphs and visualizations
│
├── README.md                              # Project documentation
│
└── requirements.txt                       # List of Python dependencies
```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Loaded the Diwali Sales dataset using Pandas for inspection and preprocessing.

- Handled missing values by removing null entries and correcting inconsistent data

- Filtered out invalid entries, such as customers with zero or negative purchase amounts.

- Created new columns for deeper insights (e.g., total purchase by gender, age group, or state).

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

- **Analyzed customer demographics** such as gender, age group, state, and occupation to identify key buyer segments.

- **Examined purchasing behavior** by comparing total sales across different product categories and regions.

- Identified top-performing categories and customer segments contributing most to revenue.

- **Visualized trends** using charts like bar plots, histograms, and pie charts created with Matplotlib and Seaborn.

- **Observed correlations** between demographic factors and purchase amount to understand sales drivers.

- **Derived insights** such as higher spending by married women in the 26–35 age group and top sales in metropolitan areas.

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

**Research Questions:**
- Which **gender** contributes the most to overall sales?

- What are the **top-performing states** in terms of total sales?

- Which **occupation types** spend the most during Diwali?

- Which **product categories** generate the highest revenue?

**Key Findings:**
- **Female customers** made more purchases and contributed more to total sales than males.

- The **26–35 age group** showed the highest spending behavior.

- **IT and Healthcare** professionals were among the top spenders.

- **Top states** such as Maharashtra, Uttar Pradesh, and Karnataka had the highest sales volume.

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository
```bash
git clone https://github.com/yourusername/Diwali_Sales_Analysis.git
```
2. Install the required dependencies
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```
3. Open the Jupyter Notebook
```bash
jupyter notebook
```

**4. Optional additions (if applicable):**

- If you use Power BI or Tableau, add a line like:

-`Open the Diwali_Sales_Dashboard.pbix file in Power BI to explore the interactive dashboard.`

- If you’re using Google Colab, add:

-`You can also upload the notebook to Google Colab and run it directly in the browser.`

