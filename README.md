<h1> Transjakarta Operational Efficiency Analysis </h1>

## 1. Project Overview
This project focuses on analyzing **Transjakarta’s operational performance** using passenger transaction data (*tap-in/tap-out* records).  
The goal is to identify **inefficiencies in corridor operations**, evaluate **route-level travel durations**, and generate **data-driven recommendations** to improve service reliability and resource allocation.

### Key Objectives:
- Measure the **average and median travel duration** across all Transjakarta corridors.  
- Identify **corridors with high variability** in travel times as potential inefficiency indicators.  
- Analyze **bus stop usage** to highlight underutilized or overcrowded stops.  
- Examine **peak-hour patterns** to understand demand fluctuations throughout the day.  
- Provide **actionable recommendations** for route and schedule optimization.

---

## 2. Data Sources
- **[Transjakarta Trip Dataset (April 2023)]** – A snapshot of passenger transaction data containing tap-in/tap-out times, corridor names, stop locations, and demographic attributes.  
  - Variables include: `transID`, `tapInTime`, `tapOutTime`, `corridorName`, `tapInStopsName`, `tapOutStopsName`, `payCardAge`, `payCardSex`, and `payAmount`.
  - Missing `payAmount` values indicate **free rides**, and missing `tapOutTime` records indicate **incomplete trips**.  

---

## 3. Technologies Used
- **Programming Language:** Python (Pandas, NumPy, Matplotlib, Plotly, Seaborn)
- **Visualization Tools:** Looker Studio (Google Data Studio)
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub
- **File Format:** CSV (raw and cleaned datasets)
- **Documentation:** Markdown, MS Word

---

## 4. Project Structure
README.md <- Project documentation and overview.
Transjakarta.csv <- Original dataset
transjakarta_trip_summary_clean.csv <- Processed and feature-engineered data
Transjakarta_Operational_Efficiency_Analysis.ipynb <- Main analysis notebook
---

## 5. Summary of Findings

### 5.1 Business Insights
- The **average travel duration** across all Transjakarta routes is approximately **72 minutes**, with a median of **71.8 minutes**, indicating mostly medium-to-long trips.  
- Corridors such as those passing through **central business districts** (e.g., Dukuh Atas, Harmoni, CSW) show the **highest passenger activity**, while some outer routes are underutilized.  
- Travel durations tend to increase during **peak hours (07:00–09:00 and 16:00–18:00)**, reflecting the impact of congestion and passenger volume.  
- Several corridors show **high variance in trip durations**, suggesting potential route inefficiencies or inconsistent travel conditions.

### 5.2 Actionable Recommendations
- **Optimize routes and schedules** for corridors with prolonged or inconsistent travel times.  
- **Reallocate bus fleets** to match peak-hour passenger demand.  
- **Evaluate underutilized stops** for potential consolidation to improve route efficiency.  
- **Integrate GPS and traffic data** in future analyses to capture real-time causes of delay.  
- **Maintain data-driven monitoring** to ensure continuous service improvement.

---

## 6. Contact
- **Name:** Brian Samuel Matthew  
- **Email:**  sam7elmatthew@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/brian-samuel-matthew/  
- **Project Dashboard:** https://lookerstudio.google.com/reporting/5d4f5fb7-0a60-41f0-9f5b-819da61daeed
