KULTRAMEGA STORR - SWL - PROJECT 

### ✅ STEP 2: Repository Folder Structure (Recommended)

```
KMS-Inventory-SQL-Case-Study/
│
├── data/
│   └── kms_orders_2009_2012.xlsx        # (your uploaded Excel dataset)
│
├── sql/
│   ├── case_scenario_1_queries.sql
│   └── case_scenario_2_queries.sql
│
├── outputs/
│   ├── summary_charts.png               # optional: if you made any visuals
│   └── revenue_recommendations.txt
│
├── README.md                            # main project documentation
└── kms_inventory_analysis_report.pdf    # optional: final report if needed
```

---

### ✅ STEP 3: `README.md` Content Template

```markdown
# Kultra Mega Stores Inventory Analysis (SQL Case Study)

## 🏢 Company Overview

Kultra Mega Stores (KMS), based in ONTARIO, CANADA, specializes in office supplies and furniture. Their diverse customer base includes individual consumers, small businesses (retail), and large corporate clients (wholesale). This analysis focuses on historical order data from 2009 to 2012, with specific attention to the Abuja division.

## 🎯 Objectives

- Analyze product sales trends across categories and regions.
- Identify top-performing and underperforming customer segments.
- Provide insights into shipping costs and order priorities.
- Recommend strategies to increase revenue from the lowest-spending customers.
- Assess if the shipping methods align with order priorities.

---

## 🛠️ Tools Used

- **SQL Server**  MySQL Server
- **Excel** (for initial data review)

## 📊 Method of Analysis

1. **Data Import:** The Excel file was loaded into a SQL database for querying.
2. **Exploratory Queries:** Used SQL SELECT, JOIN, GROUP BY, ORDER BY, and CASE statements.
3. **Segmentation:** Sales were analyzed by product category, region, customer segment, and shipping method.
4. **Profitability & Return Analysis:** Identified valuable customers, returns, and profitability trends.
5. **Recommendation Development:** Based on findings, actionable insights were proposed.

---

## 📌 Key Findings

### 🔹 Case Scenario 1

1. **Highest Sales Category:** `Technology` category had the highest total sales.
2. **Top 3 Regions:** Western, Eastern, and Southern; **Bottom 3:** Central, Far East, and Abuja.
3. **Appliance Sales in Ontario:** ₦X,XXX,XXX
4. **Bottom 10 Customers:** Showed inconsistent purchase patterns; possible causes include low engagement or poor targeting.
5. **Most Expensive Shipping Method:** `Express Air` incurred the highest costs.

### 🔹 Case Scenario 2

1. **Most Valuable Customers:** Identified by total purchase value; they mostly bought Technology and Office Supplies.
2. **Top Small Business Customer:** `Customer_X` with total sales of ₦X,XXX,XXX
3. **Most Active Corporate Client (2009–2012):** `Customer_Y` with the most orders placed.
4. **Most Profitable Consumer Customer:** `Customer_Z` based on total profit.
5. **Returned Items:** `Customer_A` returned items; they belong to the `Consumer` segment.

---

## 📦 Shipping Cost vs Order Priority Analysis

- **Express Air** is fast but expensive.
- **Delivery Truck** is slower but economical.
- **Findings:** Many high-priority orders were sent using slow methods, and low-priority ones used Express Air, suggesting a mismatch.
- **Recommendation:** KMS should **align shipping method with order priority** to optimize logistics costs and customer satisfaction.

---

## 📈 Recommendations

- **Retarget bottom 10 customers** with special offers or loyalty programs.
- **Optimize shipping costs** by enforcing strict shipping guidelines based on order priority.
- **Continue investing in high-performing categories** like Technology and expand them to underperforming regions.
- **Identify customer lifecycle sttage** and tailor communication for upselling/cross-selling.




## 📬 Contact: kennysteph2012@gmail.com

