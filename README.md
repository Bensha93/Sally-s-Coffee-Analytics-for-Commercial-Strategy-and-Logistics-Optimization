# Sally-s-Coffee-Analytics-for-Commercial-Strategy-and-Logistics-Optimization

---

## **Project Overview**
This project analyzes **Sally’s Coffee** sales, customer behavior, and operational challenges to provide **data-driven recommendations** for:
- **Expanding Own Brand Coffee Market Share** ☕
- **Reducing Shipping Costs** 🚚
- **Optimizing Sales & Logistics** 📦
- **Evaluating Café Expansion Feasibility** 🏪

Additionally, this project includes **interactive Power BI dashboards** to visually analyze survey responses, sales trends, and logistics performance.

---

## **Datasets Used**
| Dataset | Description |
|---------|------------|
| `coffee_survey_sallys_brew_2024.xlsx` | Customer survey responses on coffee preferences and spending habits. |
| `sales_py.xlsx` | Sales data by location, including FY 2024 revenue. |
| `shipping_costs.xlsx` | Shipping cost categories and associated states. |
| `subscription_coffee_variety_own_compared_to_other.xlsx` | Subscription data comparing Sally’s brand coffee vs. competitors. |
| `roast.xlsx` | Roast preference mapping for customers. |
| `Sally_Coffee.pbix` | Power BI Dashboard for visualization and analysis. |

---

## **Installation & Setup**
### **1️⃣ Requirements**
This project requires **Python 3.x** and the following libraries:
```bash
pip install pandas numpy matplotlib seaborn openpyxl
```
Additionally, Power BI is needed to view the **Sally_Coffee.pbix** dashboard.

### **2️⃣ Running the Code in Google Colab**
1. Upload the datasets to Colab.
2. Run each section of the notebook sequentially.
3. Adjust **file paths** if needed for local execution.

---

## **Key Analysis & Tasks**
### **📌 Task 1: Identify Top-Selling Neighborhoods**
- **Goal**: Find the **top 3 ZIP codes** in California with the highest sales in FY 2024.
- **Method**: Filter **sales data** → Group by ZIP code → Sort by total sales.

### **📌 Task 2: Average Monthly Coffee Spend**
- **Goal**: Compare spending habits of **Frequent vs. Occasional** coffee drinkers.
- **Method**: Categorize customers **(>1 cup/day = Frequent, else Occasional)** → Compute **average monthly spend**.

### **📌 Task 3: High Shipping Cost Impact**
- **Goal**: Find the **top 3 states** with “Very High” shipping costs & calculate their share in total sales.
- **Method**: Merge **sales & shipping data** → Group by **shipping cost category**.

### **📌 Task 4: High-End Coffee Consumers**
- **Goal**: Identify neighborhoods where **customers spend $10+ on coffee**.
- **Method**: Filter survey data → Exclude areas with **low responses (<10) & low sales (<$150K)**.

### **📌 Task 5: Light Roast Preference**
- **Goal**: Find the total number of **light roast** coffee drinkers.
- **Method**: Map **roast preferences** → Count respondents selecting **light roast**.

### **📌 Task 6: Reducing Shipping Costs (with Visuals)**
- **Goal**: Suggest ways to **cut shipping costs** & estimate potential savings.
- **Method**: Visualize **current costs** by state → Recommend strategies (e.g., **regional warehouses, bulk shipping**).

### **📌 Task 7: Increasing Sally’s Brand Coffee Share**
- **Goal**: Find ways to **increase Sally’s coffee market share**.
- **Method**: Analyze **subscription data** → Visualize brand preferences → Suggest **loyalty programs & promotions**.

### **📌 Task 8: Café Business Expansion Feasibility**
- **Goal**: Assess if Sally’s Coffee should expand into **physical café locations**.
- **Method**:
  - Analyze **customer preferences** for out-of-home coffee consumption.
  - Evaluate **financial feasibility** based on projected revenue & costs.
  - **Visuals**: Scatter plot of **location scores** + Bar chart of **customer coffee habits**.

---

## **Power BI Dashboards 📊**
This project includes an **interactive Power BI Dashboard** (`Sally_Coffee.pbix`) to provide clear business insights.

### **🔹 Survey Overview Dashboard**
- Visualizes **customer preferences**, including:
  - Where they drink coffee (home, office, café).
  - Preferred coffee brands and spending habits.
  - Willingness to try premium or new coffee offerings.
- Helps develop strategies for **increasing Sally’s brand coffee share**.

### **🔹 Sales & Logistics Overview Dashboard**
- Provides insights into **sales performance & supply chain challenges**.
- Key features:
  - **Sales Trends by Region & ZIP Code** 📍
  - **Shipping Cost Breakdown by State** 🚛
  - **Demand Forecasting for Café Business** 📈
- Helps with **logistics optimization** and **planning café chain expansion**.

---

## **Results & Insights**
- **Frequent drinkers** spend **~$50–$70** monthly, while **occasional drinkers** spend **~$30–$40**.
- **Top ZIP codes for sales**: Identified **California’s high-revenue neighborhoods** for targeted marketing.
- **High shipping costs** affect **~30% of total sales**, with **New York** having the highest cost.
- **Premium coffee spenders** are **rare**, but exist in select high-income neighborhoods.
- **Café business is viable**, with projected **$67K annual profit**, provided it targets **high-scoring locations**.

---

## **Project Structure**
```
📂 Sallys_Coffee_Analysis/
│── 📄 coffee_survey_sallys_brew_2024.xlsx  # Survey data
│── 📄 sales_py.xlsx                        # Sales data
│── 📄 shipping_costs.xlsx                  # Shipping data
│── 📄 subscription_coffee_variety_own_compared_to_other.xlsx # Subscription coffee data
│── 📄 roast.xlsx                           # Roast preferences
│── 📄 Sally_Coffee.pbix                     # Power BI Dashboard
│── 📄 Sallys_Coffee_Analysis.ipynb         # Jupyter Notebook for analysis
│── 📄 README.md                             # Project documentation
```

---

## **How to Use the Power BI Dashboard**
1. **Open Power BI** on your computer.
2. **Load `Sally_Coffee.pbix`** in Power BI Desktop.
3. **Navigate through interactive reports**:
   - **Survey Overview**: Understand customer preferences.
   - **Sales Overview**: Track performance and logistics impact.
4. **Use filters & slicers** to analyze trends.

---

## **Future Enhancements**
✅ **Integrate SQL for real-time data updates**  
✅ **Develop machine learning models for demand forecasting**  
✅ **Expand Power BI dashboards with predictive insights**  

---

## **Contributors**
- **Data Analyst**: [Adewole Oyediran]
- **Business Insights Lead**: [Sally Coffee(Alcon)]
- **Power BI Specialist**: [Adewole Oyediran]

📧 **Contact**: [bensha2019@outlook.com]

---
🎯 **This project provides actionable insights for Sally’s Coffee, helping drive revenue growth and strategic decisions!** 🚀
