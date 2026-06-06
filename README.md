# Task 2: Customer Demographics Study

## 🏢 Internship Details
| Field | Details |
|-------|---------|
| **Company** | Codtech IT Solutions Private Limited |
| **Domain** | Data Analytics |
| **Intern Name** | MD SAHIL ANSARI |
| **Intern ID** | CITS3147 |
| **Task** | Task 2 – Customer Demographics Study |

---

## 📌 Objective
To perform an in-depth analysis of customer demographics data to uncover patterns related to:
- Age, Gender, and Education distribution
- Income levels and spending behavior
- Customer segmentation (Premium, Regular, Budget)
- Loyalty scores and churn risk
- Preferred product categories and purchase frequency

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `customer_demographics.csv` | Sample dataset with 50 customer records |
| `customer_demographics_analysis.ipynb` | Jupyter Notebook with full analysis and visualizations |
| `README.md` | Project documentation |

---

## 📊 Dataset Description

The dataset contains **50 customer records** with **19 features**:

| Column | Description |
|--------|-------------|
| CustomerID | Unique identifier for each customer |
| Name | Customer name |
| Age | Customer age |
| Gender | Male / Female |
| City, State, Country | Customer location |
| Education | High School / Graduate / Post-Graduate |
| Occupation | Job/profession of the customer |
| AnnualIncome | Annual income in Indian Rupees (₹) |
| MaritalStatus | Single / Married |
| NumberOfChildren | Number of children |
| PurchaseFrequency | Number of purchases per year |
| AverageSpend | Average spend per purchase (₹) |
| PreferredCategory | Most-purchased product category |
| CustomerSegment | Premium / Regular / Budget |
| LoyaltyScore | Score out of 100 |
| ChurnRisk | Low / Medium / High |

---

## 📈 Analysis Performed

1. **Age Distribution** – Histogram and pie chart of age groups
2. **Gender Analysis** – Distribution and average spend comparison
3. **Education Level** – Bar chart of education distribution
4. **Marital Status & Children** – Pie charts and bar charts
5. **Income vs Spend** – Scatter plot by customer segment
6. **Segment-wise Income** – Overlapping histograms
7. **Occupation vs Income** – Top 10 occupations by income
8. **Preferred Categories** – Bar chart of top product categories
9. **Loyalty & Churn** – Scores by segment and churn distribution
10. **Correlation Heatmap** – Relationships between numerical features

---

## 🛠️ Technologies Used

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Tool:** Jupyter Notebook

---

## 🚀 How to Run

1. Clone or download this repository
2. Make sure you have Python 3 installed with required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Place `customer_demographics.csv` in the same folder as the notebook
4. Open Jupyter Notebook:
   ```bash
   jupyter notebook customer_demographics_analysis.ipynb
   ```
5. Run all cells using **Kernel → Restart & Run All**

---

## 💡 Key Insights

- Customers aged **26–45** form the majority of the customer base
- **Annual income strongly correlates** with average spending per purchase
- **Premium segment** customers have the highest loyalty scores and lowest churn
- **Electronics and Grocery** are the most preferred product categories
- **Budget segment customers** show the highest churn risk and need targeted retention strategies

---

*This project was completed as part of the Codtech IT Solutions Data Analytics Virtual Internship.*
