# Tableau-Data-Visualization-Projects
# 📊 Tableau Data Visualization Projects

## 👩‍🎓 Student Details
**Name:** Saumyaa Priyadarshinee  
**USN:** ENG23AM0187  
**Department:** Artificial Intelligence and Machine Learning (AIML)  
**Semester:** 5th semester 

---

## 📁 Project Overview
This repository contains two Tableau data visualization projects:
1. **Titanic Dataset Analysis**
2. **Coffee Chain Dataset Analysis**

Each project demonstrates hands-on data exploration and visualization using Tableau’s analytical features such as heat maps, histograms, scatter plots, box plots, bar charts, and dashboards.

---

# 🚢 **1️⃣ TITANIC DATASET ANALYSIS**

### 📘 Dataset Description:
The Titanic dataset includes demographic and survival data of passengers aboard the RMS Titanic. It is used to explore relationships between gender, age, class, and survival probability.

### 🧭 Steps Performed:
1. **Bar Chart:** Passengers vs. Gender  
2. **Stacked Bar Chart:** Survival count by Gender  
3. **Bar Chart:** Survival rate by Passenger Class  
4. **Histogram:** Age Distribution of Passengers  
5. **Bar Chart:** Average Fare by Class  
6. **Scatter Plot:** Fare vs. Age  
7. **Bar Chart:** Passenger Count by Embarkation Port  
8. **Heatmap:** Survival Rate by Gender and Class  
9. **Box Plot:** Age vs. Survival (Age distribution comparison)  
10. **Pie Chart:** Gender distribution of passengers  

### 🧩 Key Insights:
- Females had a higher survival rate compared to males.  
- First-class passengers had the highest average fare and survival rate.  
- Majority of passengers were in the age group of 20–40.  

---

# ☕ **2️⃣ COFFEE CHAIN DATASET ANALYSIS**

### 📘 Dataset Description:
The Coffee Chain dataset contains information on product sales, profits, marketing, and expenses across various states and markets. It is used to perform business analytics and visualization.

### 🧭 Instructions & Tasks Performed:

#### (i) Heat Map — Product Type, State, and Profit  
- **Drag:** Product Type → Rows, State → Columns, Profit → Color.  
- **Identify:** The state with the *lowest profit* for **Espresso** by checking the darkest (lowest) color.

#### (ii) Box Plot — Espresso Sales Distribution  
- **Drag:** Product → Columns, Sales → Rows, Filter Product Type = Espresso.  
- **Add:** Analysis → Box Plot.  
- **Identify:** The Espresso product with the *highest spread* in sales.

#### (iii) Bar Chart — Product Type, Product, and Profit  
- **Drag:** Product Type → Columns, Product → Color, Profit → Rows.  
- **Conclusion:** Shows which product types drive profit or loss.

#### (iv) Scatter Plot — State, Sales, and Profit  
- **Drag:** State → Columns, Sales → Rows, Profit → Color, Mark Type → Circle.  
- **Conclusion:** States with high sales but low profit can be identified easily.

#### (v) Identify Highest & Lowest Profit State  
- **Create View:** Drag State → Rows, Profit → Columns.  
- Sort descending to find **highest** and **lowest** profit states.

#### (vi) Sales in Nevada for Decaf Espresso  
- Apply **Filters:** State = Nevada, Product = Decaf Espresso.  
- Observe total **Sales** in the view.

#### (vii) Contribution of Tea to Overall Profit (%)  
- **Filter:** Product Type = Tea.  
- Compute: `SUM(Profit for Tea) / SUM(Profit for All)` × 100.

#### (viii) Average Marketing in Area Codes 660 and 818  
- Filter Area Code = 660, 818 → Drag Marketing → Rows → Measure = Average.

#### (ix) Highest & Lowest Profit Product in California  
- Filter State = California → Drag Product → Rows, Profit → Columns.  
- Sort to identify top and bottom products.

#### (x) Side-by-Side Circles — Minimum Marketing for Coffee Beans (Colombian)  
- Filter Product = Coffee Beans Colombian → Drag Marketing → Rows, Market → Columns, Mark = Circle.  
- Identify the minimum marketing value visually.

#### (xi) Contribution of Sales in East Market for Decaf  
- Filter Product Type = Decaf → Market = East.  
- Compute `(Sales in East for Decaf / Total Sales) × 100`.

#### (xii) Contribution of Decaf Sales in East Market (2012)  
- Add filter for **Order Date (Year = 2012)**.  
- Repeat the above percentage calculation.

#### (xiii) Average Profit for Products Starting with “C”  
- Apply **Filter → Product → Starts With “C”**.  
- Drag Profit → Rows → Measure = Average.

#### (xiv) Central Region — Top 5 Products by Sales  
- Filter Region = Central → Sort by Sales → Keep Top 5.  
- Compute `(Sales of Top 5 / Total Sales) × 100`.

#### (xv) 2013 — Highest Profit State in West Market  
- Filter Year = 2013 and Market = West.  
- Sort Profit by descending → identify top state.

#### (xvi) Total Expenses-to-Sales Ratio of State with Lowest Profit  
- Identify state with lowest profit → Create Calculated Field:  
  `SUM(Expenses) / SUM(Sales)`.

#### (xvii) Distinct Count of Area Codes — Lowest Budget Margin, Small Markets  
- Filter Market Size = Small → Identify lowest Budget Margin state.  
- Drag Area Code → Rows → Measure = Count (Distinct).

#### (xviii) 2013 — % of Profit for Caffe Mocha (Major Market)  
- Filter Year = 2013, Product = Caffe Mocha, Market = Major.  
- Compute `(Profit of Caffe Mocha Major / Total Profit 2013) × 100`.

#### (xix) Month-Year when Decaf Sales Crossed $1,100 (Colorado & Florida)  
- Filter Product Type = Decaf, State = Colorado & Florida.  
- Drag Order Date → Columns → Set to Month/Year, Sales → Rows.  
- Add reference line at 1100 → Identify the bars crossing that line.

#### (xx) Tree Map — Market by Budget Sales  
- Drag Market → Label, Budget Sales → Size & Color → Mark Type = Tree Map.  
- Identify market with the **largest rectangle** (maximum budget sales).

---

### 🧩 Key Insights:
- Espresso had the **lowest profit** in certain western states.  
- **Caffe Mocha** and **Colombian Coffee Beans** were top profit drivers.  
- **Central region’s top 5 products** contributed over 70% of total sales.  
- **California** showed highest sales and profit performance overall.

---

# 🛠️ Tools Used
- **Software:** Tableau Public  
- **Data Sources:** Titanic.csv, Coffee Chain.xlsx  
- **Version Control:** GitHub  

---
