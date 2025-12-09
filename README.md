# LAPTOP_PRICE_ANALYSIS-USING-PYTHON
Analyze factors influencing laptop pricing using a real-world dataset with specifications such as brand, screen size, RAM, GPU, processor, and price.

📁 Project Files
Reinforcement_test.ipynb — Jupyter notebook with full code

REINFORCEMENT TEST - LAPTOP DATASET DOCUMENTATION.docx — Detailed documentation

REINFORCEMENT TEST - LAPTOP DATASET PPT.pptx — Project presentation

🎯 Objective
To explore and identify key features that affect laptop pricing using data cleaning, transformation, statistical analysis, and visualization in Python.

🧰 Tools & Techniques
Language: Python

Libraries: pandas, seaborn, matplotlib, scipy.stats

Techniques: Data cleaning, univariate/bivariate/multivariate analysis, T-Test, ANOVA

🧹 Data Preparation Highlights
Removed duplicates and null rows

Standardized categories (e.g., Netbook → Notebook)

Converted and cleaned Inches and Weight columns

Treated outliers using logical thresholds and mean imputation

Removed invalid symbols and fixed datatypes

🔍 Key Insights
💰 Most laptops priced around ₹52,000; price is positively skewed

💾 8GB RAM most common; price increases with RAM and dedicated GPU

⚙ Intel dominates with 95% CPU market share

🧮 Price is strongly correlated with RAM, moderately with Weight

🧪 T-Test: Dedicated GPUs significantly increase price

📊 ANOVA: RAM, GPU type, and weight category significantly influence price

🏷 Lenovo leads in entry-level segment and notebooks

🧪 Statistical Tests
T-Test: GPU Type vs Price → Significant difference

Two-Way ANOVA: RAM, GPU Type, Weight → Significant impact on price

No significant interaction between company, OS, and processor types

📌 Conclusion
Laptop pricing is primarily influenced by RAM, GPU type, and performance-related specs, not by brand or screen size. Users prefer moderately priced, well-performing laptops, with Lenovo and Dell dominating market share
