# LAPTOP_DATASET_ANALYSIS_USING_PYTHON
💻 Laptop Price Analysis – Statistical & Exploratory Study

This project analyzes a real-world laptop dataset to understand which technical specifications have the strongest impact on pricing. The analysis includes data cleaning, preprocessing, visualization, and statistical tests such as T-Test and ANOVA.

---

📁 Project Files

Reinforcement_test.ipynb – Complete Jupyter Notebook with full code

REINFORCEMENT TEST - LAPTOP DATASET DOCUMENTATION.docx – Detailed project documentation

REINFORCEMENT TEST - LAPTOP DATASET PPT.pptx – Presentation slides covering approach & results

---

🎯 Objective

To identify and analyze the key factors influencing laptop pricing using Python-based data cleaning, transformation, visualization, and statistical testing.


---

🧰 Tools & Techniques

Language: Python
Libraries Used:
       pandas
       matplotlib
       seaborn
       scipy.stats
Techniques Applied:

Data Cleaning & Standardization

Outlier Treatment

Univariate, Bivariate & Multivariate Analysis

T-Test (Independent Samples)

One-Way & Two-Way ANOVA

---

🧹 Data Preparation Highlights

Removed duplicates and rows with null values

Standardized inconsistent categories (e.g., Netbook → Notebook)

Cleaned & converted numerical features:

Corrected Inches formatting

Cleaned Weight values


Replaced outliers using logical thresholds and mean imputation

Removed invalid characters and fixed column datatypes

---

🔍 Key Insights from Analysis

💰 Price Distribution

Most laptops cluster around ₹52,000

Distribution is positively skewed, indicating many budget/mid-range models


💾 Hardware Influence

8GB RAM is most common

Price increases significantly with:

Higher RAM

Dedicated GPU

Better processor tiers

⚙ Processor & GPU Trends

Intel dominates with ~95% CPU share

Dedicated GPUs strongly push the price upwards

📊 Correlation Patterns

Price is strongly correlated with RAM

Moderate correlation with weight (performance laptops weigh more)


🏷 Brand & Category

Lenovo leads in mid-range/entry-level models

Notebook category has the highest count

---

🧪 Statistical Tests Performed

✔ T-Test: Dedicated GPU vs Price

Laptops with dedicated GPU have significantly higher prices

Strong evidence that GPU type affects pricing

✔ One-Way & Two-Way ANOVA

RAM, GPU Type, and Weight Category → significant impact on price

No significant interaction found between brand, OS, and processor

---

📌 Conclusion

Laptop prices are primarily driven by performance specifications, especially:

RAM
GPU Type
Processor Tier
Weight (indirect indicator of performance hardware)

Brand and screen size have minimal impact on final pricing.
Consumers prefer value-for-money, mid-range laptops, with Lenovo and Dell consistently capturing strong market share.
