# Project File Structure Guide

## Essential File Organization

```
Integrative_Project/
├── README.md                           # Project overview and instructions
├── project_structure.md                # This file - organization guide
│
├── Data/                               # Data files
│   ├── student_data.csv               # Raw dataset
│   ├── data_dictionary.csv            # Data documentation
│   └── cleaned_data.csv               # Cleaned dataset (to be created)
│
├── Analysis/                           # Analysis files
│   ├── data_cleaning.ipynb            # Data exploration and cleaning
│   ├── exploratory_analysis.ipynb     # Statistical analysis and visualizations
│   └── predictive_model.ipynb         # Conceptual model development
│
├── Documentation/                      # Written documentation
│   ├── systems_governance.md          # Section 1: Systems & Governance
│   └── group_report.md                # Final report (sections 1, 3, 4)
│
└── Visualizations/                     # Generated charts and graphs
    └── figures/                       # Saved plots and charts
```

## File Breakdown by Project Sections

### **Section 1: Systems & Governance Analysis**

**Files:**

- `Documentation/systems_governance.md`
  - Systems map
  - 5 Ws of data governance
  - Ethical risks and privacy concerns

### **Section 2: Data Cleaning & Preparation**

**Files:**

- `Analysis/data_cleaning.ipynb`
  - Data exploration
  - Data cleaning procedures
  - Create cleaned_data.csv

### **Section 3: Exploratory Analysis**

**Files:**

- `Analysis/exploratory_analysis.ipynb`
  - Univariate analysis
  - Multivariate analysis (2-3 graphs)
  - Correlation analysis
- `Visualizations/figures/` (saved plots)

### **Section 4: Conceptual Automation & Prediction**

**Files:**

- `Analysis/predictive_model.ipynb`
  - Variable selection
  - Model conceptualization
  - Risk assessment

### **Section 5: Integrative Report**

**Files:**

- `Documentation/group_report.md`
  - Team information
  - Systems & governance analysis
  - Statistical insights
  - Predictive model description

## Deliverables Checklist

- [ ] **Jupyter Notebooks** (3 files in Analysis/)
- [ ] **Group Report** (Documentation/group_report.md)
- [ ] **Presentation recording** (5-7 minutes)

## Simple Workflow

1. **Start with data_cleaning.ipynb** - explore and clean data
2. **Move to exploratory_analysis.ipynb** - create visualizations and insights
3. **Work on predictive_model.ipynb** - conceptual model development
4. **Write systems_governance.md** - systems thinking and governance
5. **Combine into group_report.md** - final integrated report
6. **Record presentation** - summarize findings
