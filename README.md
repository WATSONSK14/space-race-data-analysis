<div align="center">

# 🚀 Space Race Data Analysis

**Exploratory data analysis of 4,300+ space missions from the dawn of the Space Race (1957) to 2020.**

[![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive_Charts-3F4F75?logo=plotly&logoColor=white)](https://plotly.com)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

*Who dominated space? How did launch costs evolve? Did missions get safer over time?*  
*This project answers these questions and more through data-driven visualizations.*

</div>

---

## 📖 About

This project performs a comprehensive exploratory data analysis (EDA) on a dataset scraped from [nextspaceflight.com](https://nextspaceflight.com), covering **every orbital launch attempt** from October 1957 (Sputnik) through 2020.

The analysis covers launch frequency trends, cost analysis, geographic distribution, organizational dominance, Cold War rivalries, and mission safety — all brought to life through interactive and static visualizations.

---

## 🔍 Key Questions Explored

| # | Question | Visualization |
|---|----------|---------------|
| 1 | Which organizations launched the most missions? | Horizontal Bar Chart |
| 2 | How many rockets are still active vs. retired? | Bar Chart |
| 3 | What is the mission success/failure distribution? | Bar Chart |
| 4 | How are launch costs distributed? | Histogram |
| 5 | Which countries launch the most rockets? | 🌍 Interactive Choropleth Map |
| 6 | Which countries have the most failures? | 🌍 Interactive Choropleth Map |
| 7 | How do countries, orgs & statuses relate? | 🌐 Sunburst Chart |
| 8 | Which organizations spent the most on space? | Aggregated Analysis |
| 9 | What is the average cost per launch by org? | Aggregated Analysis |
| 10 | How did launch frequency change over the decades? | Line Chart |
| 11 | What are the monthly launch trends? | Line Chart + 6M Rolling Average |
| 12 | Which months are most popular for launches? | Seasonal Analysis |
| 13 | How has the average launch price changed over time? | Line Chart |
| 14 | How did the Top 10 organizations' dominance shift? | Multi-line Chart |
| 15 | USA vs USSR: Who won the Cold War space race? | 🥧 Pie Chart |
| 16 | USA vs USSR: Year-on-year launch comparison | Dual Line Chart |
| 17 | How did mission failures change over time? | Line Chart |
| 18 | Did the failure *percentage* decrease over time? | Trend Line Chart |
| 19 | Which country led in launches each year? | Stacked Bar Chart |
| 20 | Which organization dominated each year? | Stacked Bar Chart |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.11** | Core language |
| **Pandas** | Data loading, cleaning, grouping & aggregation |
| **Matplotlib** | Static charts (bar, line, histogram) |
| **Seaborn** | Enhanced statistical visualizations |
| **Plotly Express** | Interactive charts (choropleth, sunburst, pie) |
| **iso3166** | Country name → ISO Alpha-3 code conversion |
| **Jupyter Notebook** | Interactive development environment |

---

## 📁 Project Structure

```
space-race-data-analysis/
├── data/
│   └── mission_launches.csv       # Raw dataset (4,324 missions)
├── notebooks/
│   └── Space_Missions_Analysis_(start).ipynb  # Complete analysis notebook
├── .gitignore
├── requirements.txt               # Python dependencies
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/WATSONSK14/space-race-data-analysis.git
cd space-race-data-analysis

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# Windows:
.\venv\Scripts\Activate.ps1
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

Then navigate to `notebooks/` and open the analysis notebook.

---

## 📊 Key Findings

- 🏆 **RVSN USSR** dominated launches throughout the 1960s–1980s, but **SpaceX** took the lead by 2020.
- 💰 Launch costs have **decreased significantly** over time, largely driven by reusable rocket technology.
- 📅 **December** is the most popular month for launches, while summer months see relatively fewer missions.
- ✅ The **failure rate has dropped** dramatically — from ~20% in the early years to under 5% in recent decades.
- 🌍 The **USA and Russia** account for the vast majority of all launches, but **China** has rapidly emerged as a major player.

---

## 🔄 Development Workflow

This project was developed using **Git Flow** methodology:

```
main ← PR #1: Data cleaning & initial analysis
     ← PR #2: Complete analysis (choropleth, sunburst, cost, cold war, safety)
```

Each feature was developed on a dedicated branch, reviewed via Pull Request, and merged into `main`.

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**WATSONSK14**

- GitHub: [@WATSONSK14](https://github.com/WATSONSK14)

---

<div align="center">

*Made with 📊 by WATSONSK14*

*Data source: [nextspaceflight.com](https://nextspaceflight.com)*

</div>
