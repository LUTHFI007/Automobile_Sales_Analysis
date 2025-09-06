# 📊 Automobile Sales Analysis during Recession (IBM Data Science Certification Project)

This project is part of the **IBM Data Science Professional Certification**.  
The objective is to analyze historical automobile sales data of **XYZAutomotives** and provide insights into how sales were impacted during **recession periods**.  

The project is divided into **two parts**:  
1. 📈 Data Visualization using Matplotlib, Seaborn & Folium  
2. 📊 Interactive Dashboard using Plotly & Dash  

---

## 📂 Dataset Overview  

The dataset is **artificially created** for this study (no real data is used).  

### Features:
- **Date**: Date of observation  
- **Recession**: 1 → recession period, 0 → normal period  
- **Automobile_Sales**: Number of vehicles sold  
- **GDP**: Per capita GDP in USD  
- **Unemployment_Rate**: Monthly unemployment rate  
- **Consumer_Confidence**: Index representing consumer spending tendency  
- **Seasonality_Weight**: Seasonal effect on automobile sales  
- **Price**: Average vehicle price  
- **Advertising_Expenditure**: Marketing/advertising spend  
- **Vehicle_Type**: Supperminicar, Smallfamilycar, Mediumfamilycar, Executivecar, Sports  
- **Competition**: Market competition level  
- **Month**: Extracted from Date  
- **Year**: Extracted from Date  

### Recession Periods Considered:
- 1980  
- 1981–1982  
- 1991  
- 2000–2001  
- 2007–2009  
- 2020 (Feb–Apr, Covid-19 Impact)  

---

## 📝 Project Workflow  

### 🔹 Part 1: Data Visualization (Matplotlib, Seaborn, Folium)  

**Objective**: Analyze historical trends and visualize the impact of recessions on automobile sales.  

#### Tasks:  
- **Task 1.1**: Line chart → Automobile sales trend year by year  
- **Task 1.2**: Line chart by vehicle type → Compare trends during recession periods  
- **Task 1.3**: Seaborn visualization → Compare sales trends (recession vs. non-recession)  
- **Task 1.4**: Subplots → GDP variations (recession vs. non-recession)  
- **Task 1.5**: Bubble plot → Seasonality effect on sales  
- **Task 1.6**: Scatter plot → Vehicle price vs. sales correlation during recessions  
- **Task 1.7**: Pie chart → Advertising expenditure (recession vs. non-recession)  
- **Task 1.8**: Pie chart → Advertisement spend by vehicle type during recessions  
- **Task 1.9**: Line plot → Unemployment rate impact on vehicle sales during recessions  

---

### 🔹 Part 2: Interactive Dashboard (Plotly & Dash)  

**Objective**: Provide directors with a **dynamic dashboard** to explore sales, recession effects, and yearly trends.  

#### Tasks:  
- **Task 2.1**: Create Dash application with a meaningful title  
- **Task 2.2**: Add dropdown menus for selecting filters (e.g., year, vehicle type, report type)  
- **Task 2.3**: Add divisions for interactive output display  
- **Task 2.4**: Create callback functions to update graphs dynamically  
- **Task 2.5**: Recession Report Dashboard → Display key charts/statistics  
- **Task 2.6**: Yearly Report Dashboard → Display trends across years  

---

## 🚀 Technologies Used  

- **Python**  
- **Pandas, Numpy** – Data manipulation  
- **Matplotlib, Seaborn, Folium** – Data visualization  
- **Plotly, Dash** – Interactive dashboards  
- **Jupyter Notebook** – Development  

---

## 📌 Key Insights  

- Automobile sales **drop significantly** during recession periods.  
- Certain vehicle types (e.g., **small family cars**) were less impacted compared to others.  
- **Consumer confidence** and **unemployment rate** strongly correlate with sales trends.  
- **Advertising expenditure** played a crucial role in maintaining visibility during recessions.  

---


