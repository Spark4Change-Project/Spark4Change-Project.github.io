# Spark4Change: San Diego Small Business Survival Analysis

🌐 **Live Website:** [https://Spark4Change-Project.github.io/](https://Spark4Change-Project.github.io/)

## Project Overview
Spark4Change investigates the dynamics of local business survival and social impact in San Diego County, analyzing over three decades of business data (1990-present) to understand why businesses fail and which communities face the greatest economic vulnerabilities.

## 🎯 Quick Links
- **Interactive Website:** [View Full Analysis](https://Spark4Change-Project.github.io/)
- **GitHub Organization:** [Spark4Change-Project](https://github.com/Spark4Change-Project)
- **Original Project Site:** [Google Sites](https://sites.google.com/view/spark4change)
- **GitHub Repository:** [Source Code](https://github.com/Spark4Change-Project/Spark4Change-Project.github.io)

## Team Members
- **Swasthika Rajendran** - Data Analyst
- **Aneesha Prasad** - Data Scientist
- **Sudeshna Das Rochi** - Statistical Analyst
- **Sahitya Kotla** - Visualization Specialist

## 📊 Key Findings

### Economic Correlation
- **Spearman correlation**: r = 0.34, p = 0.044 (statistically significant)
- Higher unemployment years correlate with higher business closure rates

### Critical Survival Period
- **First 5 years** are critical - this is the "valley of death" for businesses
- Approximately **50% of businesses** survive past 5 years
- Businesses surviving beyond 5 years show significantly improved long-term prospects

### Sector Vulnerability
- **High-risk sectors**: Accommodation & Food Services, Retail Trade, Arts & Entertainment
- **Stable sectors**: Professional Services, Healthcare, Finance & Insurance
- **2-3x difference** in closure hazard between high-risk and stable sectors

### Geographic Patterns
- **North County**: Generally stable business environment
- **South Bay & East County**: Higher closure rates in certain areas
- **Central San Diego**: High density with mixed survival outcomes

## 🛠️ Tools & Technologies

- **Python** - Data preprocessing and analysis
- **Pandas** - Data manipulation
- **Lifelines** - Survival analysis (Kaplan-Meier, Cox Regression)
- **SciPy** - Statistical correlation analysis
- **Tableau** - Interactive visualizations
- **ArcGIS** - Spatial analysis
- **Matplotlib** - Data visualization
- **Jupyter** - Notebook environment

## 📁 Repository Structure

```
Business_Survival_Analysis/
├── index.html                              # Main website
├── style.css                               # Website styling
├── script.js                               # Interactive features
├── README.md                               # This file
├── _config.yml                             # GitHub Pages configuration
│
├── Notebooks/
│   ├── Spark4Change.ipynb                  # Main analysis notebook
│   ├── Business_Survival.ipynb             # Alternative workflow
│   └── spark4change_(1).py                 # Complete Python script
│
├── Data/
│   ├── sd_businesses_active_datasd.csv     # Active businesses
│   ├── sd_businesses_inactive_*.csv        # Historical data (4 files)
│   ├── biz_clean_full.csv                  # Cleaned dataset
│   ├── Unemployment.csv                    # Economic indicators
│   └── survival_firm_level_clean.csv       # Survival analysis data
│
├── Outputs/
│   ├── yearly_closure_unemployment.csv     # Annual metrics
│   ├── sector_year_closure_rate*.csv       # Sector analysis
│   └── industry_cluster_year_*.csv         # Industry clusters
│
└── Visualizations/
    ├── *.twb                               # Tableau workbooks
    ├── km_overall_survival_clean.png       # Survival curves
    └── km_sector_top6_survival_clean.png   # Sector comparison
```

## 🚀 Getting Started

### View the Website
Simply visit: [https://swasthi-raj.github.io/Business_Survival_Analysis/](https://swasthi-raj.github.io/Business_Survival_Analysis/)

### Run the Analysis Locally

1. **Clone the repository**
```bash
git clone https://github.com/swasthi-raj/Business_Survival_Analysis.git
cd Business_Survival_Analysis
```

2. **Install dependencies**
```bash
pip install pandas numpy scipy lifelines matplotlib jupyter
```

3. **Run the Jupyter notebook**
```bash
jupyter notebook Spark4Change.ipynb
```

Or execute the complete script:
```bash
python spark4change_(1).py
```

## 📈 Analysis Workflow

### 1. Data Collection & Integration
- Merged 5 datasets (active + 4 historical periods)
- 400,000+ business records spanning 35 years

### 2. Data Cleaning
- Standardized column names and date formats
- Extracted clean ZIP codes
- Created business status flags

### 3. Feature Engineering
- Mapped 80+ ZIP codes to San Diego neighborhoods
- Classified businesses by NAICS sector
- Created industry clusters

### 4. Survival Analysis
- Calculated business duration and closure dates
- Built Kaplan-Meier survival curves
- Fit Cox Proportional Hazards models

### 5. Statistical Testing
- Pearson & Spearman correlation with unemployment
- Sector-specific hazard ratios
- Time-series closure rate analysis

### 6. Visualization
- Tableau dashboards for interactive exploration
- Survival curve plots
- Heatmaps of closure patterns

## 💡 Key Recommendations

### For Policymakers
- Launch "First Five Years" support program
- Create sector-specific intervention plans
- Build economic shock response fund
- Implement geographic equity initiatives

### For Economic Development
- Sector-specific mentorship programs
- Real-time business health monitoring
- Rapid-response during downturns
- Targeted resources for vulnerable areas

### For Communities
- Strengthen business networks
- Expand microfinance programs
- Financial literacy training
- Peer learning initiatives

## 📊 Expected Impact

- **10-15%** reduction in early-stage closures
- **More equitable** distribution of business success
- **Faster recovery** during economic downturns
- **Data-informed policy** replacing reactive interventions

## 📝 Citation

If you use this research, please cite:
```
Spark4Change Team (2024). San Diego Small Business Survival Analysis.
GitHub: https://github.com/swasthi-raj/Business_Survival_Analysis
```

## 📄 License

This project is for educational and research purposes.

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues or pull requests.

## 📧 Contact

For questions or collaboration opportunities:
- Visit our [website](https://swasthi-raj.github.io/Business_Survival_Analysis/)
- Check out our [original project site](https://sites.google.com/view/spark4change)

---

**Made with ❤️ by the Spark4Change Team**

*Empowering communities through data-driven insights for economic resilience*