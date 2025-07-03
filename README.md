# Supertrail-interview-

# Product Sampling & Conversion Analysis

Welcome to the project repository for **Customer Purchase & Sampling Behaviour**.  
This README outlines the assignment goals, dataset structure, required analyses, and expected deliverables.

---

## 🎯 Objective

Analyze customer-order data to uncover insights on **product sampling effectiveness** and **conversion timing**. Specifically, determine:

1. **Brand attachment** gained after a customer receives a sample.  
2. **Product attachment** (engagement with sampled items).  
3. **Time-to-conversion** — average delay between receiving a sample and making a purchase.

---

## 📂 Dataset Overview

| Column | Description |
|--------|-------------|
| `customer_id` | Unique identifier for the customer |
| `order_id`    | Unique identifier for the order |
| `order_date`  | Date-time stamp when the order was placed |
| `productName` | Name of the purchased product |
| `quantity`    | Number of units bought |
| `sku`         | Stock-keeping unit (item identifier) |
| `sellingPrice`| Price paid by the customer |
| `brand`       | Brand of the product |
| `productType` | Product category / type |

---

## 🔍 Analysis Tasks

1. **Brand Attachment After Sampling**  
   *Quantify and visualise the correlation between receiving a sample and subsequent loyalty to that brand.*

2. **Product Attachment After Sampling**  
   *Identify how customers engage with a **specific product** once they have sampled it (repeat purchases, basket size, etc.).*

3. **Time-to-Conversion**  
   *Compute the average (and distribution) of days from sampling to first paid purchase of the same product.*

---

## 📝 Expected Deliverables

* **Analysis document** (report / slide deck) summarising insights.  
* **Clear visualisations** supporting findings (charts, tables).  
  *If using Excel, submit the `.xlsx`; if using Python, submit the `.ipynb` notebook.*  
* **Methodology summary** detailing cleaning, assumptions, and calculations.

---

## 🛠 Recommended Workflow

1. **Clone** this repo and add `customer_orders.csv` to `/data`.  
2. Choose your analysis tool:  
   * **Excel:** build pivot tables, charts, and formula-based metrics.  
   * **Python (pandas):** create a Jupyter notebook for data prep, EDA, and plots (matplotlib / seaborn).  
3. Document every step (comments or separate markdown cells).  
4. Export figures to `/figures` and place your final report in `/report`.  
5. Verify reproducibility (set seeds where random sampling is involved).

---

## 🤝 Contributions

Feel free to open issues or pull requests for improvements.

---

### Licence

© 2025 [Your Name / Institution] – for educational use only.
