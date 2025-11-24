# Tableau Visualisation – Titanic Survival Analysis  

This repository contains a Tableau visual analytics project exploring survival patterns on the Titanic using key demographic and socio-economic variables. The dashboard provides interactive insights into how **age**, **passenger class**, and **family structure** influenced the probability of survival.

The project includes the full Tableau packaged workbook (`.twbx`), individual worksheet images, and a combined dashboard export.

---

##  Project Overview  

The **Titanic dataset** remains one of the most widely analysed datasets in data science and visual analytics.  
This Tableau project focuses on identifying how different factors contributed to survival outcomes during the disaster.

Key questions explored include:

- What proportion of passengers survived?  
- Do younger passengers have a higher chance of survival?  
- How does **passenger class (Pclass)** influence survival rates?  
- Does travelling with siblings/spouses affect survival likelihood?  
- How do these variables interact when visualised together?

---

## Dashboard Contents  

The final dashboard integrates the following components:

### **1. Survived – Overall Survival Distribution (Pie Chart)**  
- **61.62%** of passengers **did not survive**.  
- **38.38%** of passengers **survived**.  
- This chart provides an immediate overview of the severity of the disaster.  

---

### **2. Custom Age Bins – Survival by Age Group**  
Age groups used:  
- **0–10 years**  
- **11–20 years**  
- **21+ years**

#### Insights:
- The **21+ age group** had the highest number of total passengers and also the highest number of deaths (327).  
- The survival proportion decreases as age increases.  
- The **0–10 group** shows better relative survival rates compared to older groups.  
- The bar is split into **counts** (top chart) and **percentages** (bottom chart), allowing comparison across categories.

---

### **3. Passenger Class (Pclass) – Survival by Socioeconomic Status**  
Classes represented:  
- **1st Class**  
- **2nd Class**  
- **3rd Class**

#### Insights:
- **3rd Class (lower socioeconomic class)** had the largest number of passengers (**372 deaths**) and the lowest survival percentage.  
- **1st Class** passengers had significantly higher survival rates.
- The percentage chart highlights the survival gap between wealthier and lower-class passengers.  

---

### **4. Sibling/Spouse Count (SibSp) – Impact of Family Structure**  
This visual shows how travelling with siblings/spouses affected survival.

#### Insights:
- Passengers with **no siblings/spouses (SibSp = 0)** formed the largest group (**398 deaths, 210 survivors**).  
- Passengers travelling with **one sibling/spouse** show slightly improved survival rates.  
- Survival rates decrease as family size increases (SibSp = 3, 4, 5, 8).  
- Larger groups (SibSp ≥ 3) represent very small portions of the dataset and have poor survival outcomes.

---
 

