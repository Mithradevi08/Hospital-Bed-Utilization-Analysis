# Hospital Bed Utilization Analysis

##  Project Overview
This project analyzes hospital bed utilization, patient flow, and resource allocation across different hospital services using Python. It helps identify overcrowded departments, staffing gaps, and efficiency of hospital resources.

---

##  Objectives

1. Load and process hospital admission dataset  
2. Analyze bed occupancy trends across departments (services)  
3. Identify peak patient admission load  
4. Analyze staff requirement gaps  
5. Visualize hospital resource utilization patterns  
6. Build a simple hospital operations dashboard  

---

##  Dataset Description

The dataset used contains hospital operational data with the following features:

- service (department name)
- patients_admitted
- max_occupancy
- avg_satisfaction
- staff_count
- recommended_staff
- avg_stay

---

##  Technologies Used

- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

##  Analysis Performed

### 1. Bed Utilization Analysis
Calculated utilization rate:
\[
utilization\_rate = patients\_admitted / max\_occupancy
\]

---

### 2. Department Capacity Analysis
Compared:
- Total patients admitted
- Maximum occupancy per service

---

### 3. Peak Load Analysis
Identified departments with highest patient load.

---

### 4. Patient Flow Analysis
Analyzed distribution of patients across services.

---

### 5. Satisfaction Analysis
Studied average patient satisfaction per department.

---

### 6. Staff Optimization Analysis
Calculated staff gap:
\[
staff\_gap = recommended\_staff - staff\_count
\]

---

##  Visualizations

The project includes:

-  Bed Utilization Bar Chart
-  Department Capacity Comparison
-  Peak Patient Load Chart
-  Box Plot for Patient Flow
-  Satisfaction Analysis Chart
-  Staff Gap Analysis Chart
-  Dashboard (2x2 visualization grid)

---

## Key Insights

- Some departments show **high bed utilization**, indicating overcrowding  
- Certain services have **low utilization**, indicating underuse  
- Staff shortages exist in multiple departments  
- Patient satisfaction varies across services  
- Resource allocation is not balanced across hospital services  

---

##  Final Dashboard

A combined dashboard is created using subplots showing:

- Patients per service  
- Bed utilization  
- Satisfaction levels  
- Staff gap analysis  

---

##  How to Run the Project

1. Open Google Colab or Jupyter Notebook  
2. Upload dataset: `hospital_insights_summary.csv`  
3. Run all cells step by step  
4. View visualizations and results  

---

---

##  Outcome

This project helps in:
- Improving hospital resource planning  
- Identifying overloaded departments  
- Optimizing staffing levels  
- Enhancing patient care efficiency  

