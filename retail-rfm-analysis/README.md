### 📊 retail-rfm-analysis
> **segmenting customer behavior using sql & python**

---

#### 📌 overview
this project applies the **rfm (recency, frequency, monetary)** framework to retail transaction data. the goal is to categorize customers into behavioral segments to drive targeted marketing strategies.

#### 🛠 tech_stack
- **querying**: `postgresql` / `mysql` (using common table expressions)
- **analysis**: `python` (`pandas`, `numpy`)
- **visualization**: `matplotlib`, `seaborn`
- **environment**: `vs code`

#### 🧬 methodology
to calculate the rfm scores, i used the following logic:
1. **recency**: days since last transaction (calculated from the latest date in the dataset).
2. **frequency**: total count of unique invoice numbers per customer.
3. **monetary**: total spend per customer.

[Image of RFM analysis segments diagram]

#### 📂 file_structure
- `scripts/`: sql queries for data cleaning and rfm calculation.
- `notebooks/`: exploratory data analysis (eda) and visualization.
- `data/`: sample dataset (anonymized).

---

#### 💡 key_findings
- successfully segmented the database into **champions**, **loyalists**, and **at-risk** customers.
- identified that top 10% of customers contribute to ~40% of total revenue.

<br />

<sub>
  specialization project for big data analytics • [back to portfolio](URL_TO_YOUR_MAIN_REPO)
</sub>
