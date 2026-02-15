# 🏥 IVF Treatment Outcomes Analysis: Evidence-Based Policy Insights

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Healthcare Policy Analytics Project**  
Analysis of 169,616 IVF treatment cycles using publicly available HFEA data to inform NICE guidelines on fertility treatment funding.

---

## 📊 Project Overview

This independent data science project analyzes large-scale fertility treatment data from the UK's Human Fertilisation and Embryology Authority (HFEA) to provide evidence-based insights for healthcare policy decisions.

### Key Objectives
- Analyze IVF success rates across multiple treatment cycles (Cycle 1 through 6+)
- Identify confounding factors affecting outcome interpretation
- Provide evidence-based recommendations for NICE funding guidelines
- Demonstrate healthcare analytics and policy-focused data science skills

---

## 🎯 Key Findings

### Main Discovery: Four Major Confounding Factors

The analysis revealed that apparent decline in per-cycle success rates is heavily influenced by:

1. **Treatment Composition Shift**
   - Fresh embryo transfers: 85% (Cycle 1) → 51% (Cycle 4+)
   - Different treatment modalities have different success profiles

2. **Massive Patient Attrition**
   - 94% of patients discontinue treatment by Cycle 6
   - Creates severe selection bias in later cycles

3. **Age Progression**
   - Average patient age increases 11% across treatment cycles
   - From 32.5 years (Cycle 1) to 36.1 years (Cycle 4+)
   - Age is the dominant predictor of IVF success

4. **Population Shift**
   - 37% of patients in later cycles already have children
   - Different treatment goals (additional children vs first child)

### Clinical & Safety Insights

- **Multiple Birth Risk**: Doubles in later cycles due to declining eSET (elective single embryo transfer) usage
- **Natural Stopping Point**: Patient behavior shows clear discontinuation pattern at ~6 cycles
- **Cumulative Success**: Despite confounders, cumulative live birth rates demonstrate IVF efficacy

---

## 📈 Policy Implications

**Evidence-Based Recommendation**: Analysis supports NICE's current 3-cycle NHS funding policy

**Rationale**:
- Cumulative success rates show diminishing returns beyond 3 cycles
- Complex confounding factors make direct per-cycle comparisons unreliable
- Safety considerations (multiple birth risk increases)
- Natural patient stopping point aligns with 6-cycle threshold
- Cost-effectiveness considerations for public healthcare funding

---

## 🛠️ Technical Implementation

### Dataset
- **Source**: HFEA (Human Fertilisation and Embryology Authority) publicly available data
- **Size**: 169,616 IVF treatment cycles
- **Time Period**: 2017-2018
- **Scope**: UK fertility treatment outcomes

### Technologies Used
- **Python 3.8+**: Primary analysis language
- **Pandas**: Data manipulation and cleaning
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive analysis and documentation

### Analytical Approach

1. **Data Cleaning & Preparation**
   - Missing value treatment for large-scale healthcare dataset
   - Multi-table merging and integration
   - Feature engineering for cycle-based analysis

2. **Exploratory Data Analysis**
   - Treatment composition analysis (Fresh vs Frozen cycles)
   - Patient demographic trends across treatment cycles
   - Success rate pattern identification

3. **Statistical Analysis**
   - Per-cycle live birth rate calculations
   - Cumulative success rate modeling
   - Age-stratified analysis
   - Treatment modality comparison
   - Multiple birth risk assessment

4. **Confounding Factor Investigation**
   - Selection bias quantification (patient attrition analysis)
   - Treatment composition shift analysis
   - Age progression pattern identification
   - Population characteristic changes

---

## 📂 Repository Structure

```
HFEA-IVF-Treatment-Analysis/
│
├── HFEA_IVF_Complete_Analysis.ipynb    # Main analysis notebook
├── IVF_Cycle_Outcomes_Analysis.pptx    # Policy briefing presentation (13 slides)
├── README.md                            # This file
├── requirements.txt                     # Python dependencies
└── .gitignore                          # Git ignore file
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/HFEA-IVF-Treatment-Analysis.git
cd HFEA-IVF-Treatment-Analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook HFEA_IVF_Complete_Analysis.ipynb
```

---

## 📊 Deliverables

### 1. Jupyter Notebook
- Complete data analysis with code and documentation
- Reproducible workflow from data loading to conclusions
- Visualizations and statistical outputs

### 2. PowerPoint Presentation
- 13-slide professional policy briefing
- Executive summary of key findings
- Evidence-based recommendations for NICE guidelines
- Suitable for non-technical stakeholders

---

## 💡 Skills Demonstrated

### Technical Skills
- Large-scale data processing (169K+ records)
- Python programming (Pandas, NumPy, visualization libraries)
- Statistical analysis and interpretation
- Data cleaning and preprocessing
- Feature engineering
- Reproducible research practices

### Analytical Skills
- Healthcare analytics
- Confounding factor identification
- Bias detection and mitigation
- Critical thinking beyond surface-level findings
- Pattern recognition
- Root cause analysis

### Domain & Communication Skills
- Understanding healthcare policy and regulatory frameworks
- Working with public health data (HFEA regulations)
- Evidence-based policy recommendations
- Data storytelling for non-technical audiences
- Professional presentation creation
- Stakeholder-focused analysis

---

## ⚠️ Disclaimer

This is an **independent portfolio project** using publicly available HFEA data for educational and demonstration purposes.

**Important Notes**:
- This analysis does **NOT** represent official HFEA analysis or policy positions
- Recommendations are analytical conclusions for demonstration purposes only
- Data used is from the HFEA's publicly available anonymized register (2017-2018)
- This project is intended to showcase data science and healthcare analytics capabilities

**Data Source**: Human Fertilisation and Embryology Authority (HFEA) - https://www.hfea.gov.uk/

---

## 📧 Contact

**Vindya Siriwardhana**
- **LinkedIn**: (https://www.linkedin.com/in/vindya-siriwardhana/)
- **Email**: [asvindyaravi@gmail.com]

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- HFEA for making anonymized fertility treatment data publicly available
- NICE for establishing evidence-based healthcare guidelines
- The UK fertility treatment community for transparency in outcome reporting

---

## 📚 References

- NICE Fertility Guidelines: https://www.nice.org.uk/guidance/cg156
- HFEA Annual Reports and Data: https://www.hfea.gov.uk/
- Published research on cumulative IVF success rates

---

**⭐ If you found this analysis insightful, please consider starring this repository!**
