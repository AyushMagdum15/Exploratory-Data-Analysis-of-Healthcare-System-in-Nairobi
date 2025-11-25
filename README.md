# 🏥 Exploratory Data Analysis of the Healthcare System in Nairobi  
### **Comprehensive Analytics • Python • Power BI • Interactive Dashboard**

![Banner](assets/screenshots/banner.png)

---

## 📌 **Overview**
This project analyzes the **healthcare ecosystem of Nairobi County**, focusing on:

- Distribution of health facilities  
- Bed & cot capacity  
- Service availability (ANC, ART, X-ray, TB, PMTCT, etc.)  
- Operational performance  
- Sub-county-level healthcare equity  
- Population-adjusted coverage metrics  

The project also includes a **fully interactive dashboard** (Python Dash) to visualize capacities & service gaps across Nairobi sub-counties.
---
---

## 📊 **Key Insights (Summary)**

### **1️⃣ Facility Capacity**
- Highest number of facilities in **Westlands, Lang’ata, Embakasi**.
- Sub-counties with critically low per-capita facilities identified.

### **2️⃣ Bed & Cot Distribution**
- Severe shortage of beds in several high-population sub-counties.
- Beds-per-10k indicator highlights hospital strain.

### **3️⃣ Service Availability**
| Service | Findings |
|--------|----------|
| ANC | Strong coverage in most sub-counties |
| ART | Uneven distribution—gaps in Eastlands region |
| X-ray / Radiology | Very limited availability |
| TB Diagnostics | Concentrated in only a few hospitals |
| PMTCT | High but uneven performance |

### **4️⃣ Operational Performance**
- Many facilities not marked as "Operational"
- Sub-counties with high facility numbers but low operational rates flagged

Example embed:

```markdown
![Service Heatmap](assets/screenshots/heatmap.png)
🧠 Methodology
Step 1: Data Cleaning
Removed duplicates

Standardized sub-county names

Created a fuzzy matching system for messy names

Merged facilities dataset with Kenya population census

Step 2: Feature Engineering
Facilities per 10k population

Beds per 10k population

Service coverage (%) columns

Operational status normalization

Step 3: Exploratory Analysis
Heatmaps

Bar charts

Geographic-level insights

Correlations & pair plots

Step 4: Sub-County Aggregation
Aggregated metrics such as:

Total facilities

Total beds/cots

Service counts

Coverage percentages

Operational facility ratio

Step 5: Interactive Dashboard
A premium Power BI-style dashboard built in Python Dash, containing:

KPI Cards

Bar chart (Top N subcounties)

Scatter plot (Beds vs Facilities)

Service Heatmap

Radar Chart (Avg service coverage)

Searchable Data Table

Light/Dark theme toggle

Run via:

bash
Copy code
python dashboard/app.py
🔧 Setup & Installation
1️⃣ Clone the repository
bash
Copy code
git clone https://github.com/AyushMagdum15/Exploratory-Data-Analysis-of-Healthcare-System-in-Nairobi.git
cd Exploratory-Data-Analysis-of-Healthcare-System-in-Nairobi
2️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ Run Dashboard
bash
Copy code
python dashboard/app.py
🚀 Future Enhancements
Choropleth Map of Nairobi sub-counties

Machine Learning: predicting facility shortage zones

API-based real-time health facility updates

Deployment on Render / Vercel

📣 Connect with Me
Ayush Gajanan Magdum
🔗 GitHub: AyushMagdum15
🔗 LinkedIn: linkedin.com/in/ayush-magdum
📧 Email: ayushmagdum15@gmail.com

⭐ If you found this useful, give the repo a star!
kotlin
Copy code
⭐ Star this repository to support more open-source analytics projects!

