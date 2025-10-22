# ☣️ Apocalypse Analytics Dataset

A comprehensive dataset designed for **Excel**, **Power BI**, and **Tableau** to practice data analysis, visualization, and storytelling around a fictional **post-apocalyptic world** scenario.

This dataset simulates population survival, resource scarcity, regional impact, and faction control — providing realistic, rich data for analytics and dashboard projects.

---

## 📂 Project Overview

**Dataset Name:** Apocalypse Analytics  
**Supported Tools:**  
- Microsoft **Excel**  
- **Power BI**  
- **Tableau Desktop / Public**

**Purpose:**  
To help data analysts and visualization enthusiasts practice:
- Cleaning and transforming complex datasets
- Building KPIs and visual dashboards
- Applying DAX (Power BI) or calculated fields (Tableau)
- Telling a story with data (e.g., survival rates, resource balance, crisis management)

---

## 🧾 Dataset Description

| File Name | Description |
|------------|--------------|
| `Apocalypse_Data.xlsx` | Main Excel dataset containing all source tables |
| `Apocalypse_PowerBI.pbix` | Power BI report file (data model + visuals) |
| `Apocalypse_Tableau.twbx` | Tableau workbook with sample dashboards |
| `Readme.md` | Documentation and usage guide |

---

## 🧱 Data Model Overview

### **1. Survivors**
| Column | Description |
|---------|--------------|
| Survivor_ID | Unique identifier for each survivor |
| Name | Survivor’s name |
| Age | Age in years |
| Gender | Male / Female / Other |
| Faction | Group or community they belong to |
| Status | Alive / Deceased / Missing |
| Location_ID | Current settlement or region reference |

---

### **2. Locations**
| Column | Description |
|---------|--------------|
| Location_ID | Unique ID of the location |
| Region | Broad geographic area |
| Settlement | Specific town or base name |
| Safety_Score | Rating (1–100) of safety/stability |
| Population | Number of current survivors |
| Resource_Availability | High / Medium / Low |

---

### **3. Resources**
| Column | Description |
|---------|--------------|
| Resource_ID | Unique ID of resource entry |
| Resource_Type | Food, Water, Medicine, Weapons, Fuel |
| Quantity | Current stock available |
| Unit | Measurement unit (liters, kg, units) |
| Location_ID | Reference to location table |
| Last_Updated | Date of latest resource count |

---

### **4. Factions**
| Column | Description |
|---------|--------------|
| Faction_ID | Unique ID for each faction |
| Faction_Name | Name of the group (e.g., “The Wanderers”, “New Dawn”) |
| Leadership | Leader name or governing structure |
| Alliance | Allied / Neutral / Hostile |
| Territory_Control | Number of settlements under control |

---

### **5. Incidents**
| Column | Description |
|---------|--------------|
| Incident_ID | Unique event identifier |
| Type | Attack / Disease / Natural Disaster / Raid |
| Date | Date of occurrence |
| Location_ID | Where it happened |
| Casualties | Number of deaths or injuries |
| Impact_Score | 1–10 scale for severity |

---

## 📊 Recommended Visualizations

### **In Power BI / Tableau:**
- 📈 *Survival Rate Dashboard*: Alive vs. Deceased by Region  
- 🌍 *Geographic Map*: Settlements with safety scores and resource levels  
- ⚔️ *Faction Influence Chart*: Territory control and alliances  
- 💧 *Resource Depletion Trends*: Over time by resource type  
- ☠️ *Incident Heatmap*: Most affected regions and their impact  

### **In Excel:**
- Pivot tables for survival analysis  
- Conditional formatting for resource shortages  
- Dynamic charts for faction performance  

---

## 🧮 KPIs You Can Derive

| KPI | Formula / Idea |
|------|----------------|
| **Survival Rate** | Alive ÷ Total Survivors |
| **Resource-to-Population Ratio** | Total Resources ÷ Population per Region |
| **Incident Frequency** | Incidents per Month per Region |
| **Faction Stability Index** | (Avg. Safety_Score × Alliance Factor) ÷ Incidents |
| **Population Growth / Decline** | (Current Population - Previous) ÷ Previous × 100 |

---

## 🔍 Analysis Ideas

- Which regions have the highest survival rates?  
- How does faction alliance affect safety scores?  
- What’s the correlation between incidents and resource scarcity?  
- Are certain resources consistently low across all safe zones?  
- Can we predict the next “collapse” area based on data trends?

---

## ⚙️ Technical Notes

- **Excel:** Fully compatible with Microsoft 365 or later  
- **Power BI:** Version 2.120 or higher recommended  
- **Tableau:** Version 2023.2+  
- **Data Refresh:** If connected via Power Query or Tableau Extract, refresh sources weekly/monthly  

---

## 🧭 Suggested Data Model (ER Diagram)

```
[Survivors] *---1 [Locations] 1---* [Resources]
          \
           \*---1 [Factions]
[Incidents] *---1 [Locations]
```

---

## 📚 Learning Objectives

- Practice ETL (Extract, Transform, Load) operations  
- Design data models with relationships and cardinalities  
- Create calculated columns, measures, and KPIs  
- Develop interactive dashboards and filters  
- Perform storytelling with data  

---

## 💡 Tips for Analysts

- In **Power BI**, use **DAX** for time intelligence and KPI metrics.  
- In **Tableau**, leverage **Level of Detail (LOD)** expressions for survival comparisons.  
- In **Excel**, combine **Power Query** and **Pivot Charts** for lightweight dashboards.  

---

## 📄 License

This dataset and project are provided for **educational and portfolio use** only.  
No real-world data is used; all names, factions, and locations are **fictional**.  

---

## ✍️ Author

**Apocalypse Analytics Project**  
Created for data visualization practice using **Excel**, **Power BI**, and **Tableau**.  

---

### 🌟 Explore, analyze, and survive the apocalypse — one dashboard at a time!
