# US--Population-Report
“Interactive Power BI dashboard analyzing US state population trends (1950–2015) by region. Explore growth patterns, regional comparisons, and demographic shifts using Census Bureau data.”

# 📊 US State Population by Region (1950–2015)

This Power BI report analyzes the population growth of U.S. states from 1950 to 2015, grouped by Census regions: Northeast, Midwest, South, and West. Built with **Microsoft Power BI**, it provides interactive dashboards for exploring demographic trends, regional growth, and state-level population changes.

---

## 🗂️ Project Overview

- **Tool Used**: Microsoft Power BI  
- **Data Sources**:  
  - `us-states-population-by-year.csv` – Yearly population data for all U.S. states  
  - `us-states.csv` – Mapping of states to their respective Census regions  
- **Focus Areas**:
  - Regional population trends (1950–2015)
  - State-wise growth analysis
  - Comparative insights between U.S. regions

This project helps understand historical migration, urbanization, and demographic shifts across the United States.

---

## 📂 Dataset Details

### `us-states-population-by-year.csv`
| Column Name       | Description                        |
|--------------------|------------------------------------|
| `State`            | Name of the U.S. state            |
| `Year`             | Census year (1950–2015)           |
| `Population`       | Total population of the state     |

### `us-states.csv`
| Column Name       | Description                        |
|--------------------|------------------------------------|
| `State`            | Name of the U.S. state            |
| `Region`           | Census region (Northeast, Midwest, South, West) |

_Source_: United States Census Bureau – Historical Population Data  

---

## 🖥️ How to Use

1. Download the **Power BI file** (`us-state-population-dashboard.pbix`) from this repository.
2. Open it with **Microsoft Power BI Desktop** ([Download Here](https://powerbi.microsoft.com/desktop/)).
3. Explore the interactive report:
   - Filter by Year, Region, or State.
   - Hover over visuals for deeper insights.
   - Drill down into state-level and regional trends.

---

## 📸 Sample Dashboard Screenshots

| Regional Trends (1950–2015)       | State-wise Growth |
|------------------------------------|--------------------|
| ![Regional Trends](images/region_trends.png) | ![State Growth](images/state_growth.png) |

---

## 🚀 Getting Started

### Requirements
- Microsoft Power BI Desktop installed on your machine.

### Clone the Repository
```bash
git clone https://github.com/yourusername/us-state-population-by-region.git
cd us-state-population-by-region
```

### Open the Report
Open `us-state-population-dashboard.pbix` in Power BI Desktop and interact with the visuals.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

---

## 🤝 Contributing

Pull requests are welcome! For significant changes, please open an issue first to discuss what you would like to change.
