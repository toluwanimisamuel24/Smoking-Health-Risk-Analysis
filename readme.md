# Smoking Health Risk Analysis  
**Power BI Interactive Dashboard Project**

## Project Overview
This Power BI project analyses the impact of smoking on five key areas: **Lungs, Kidneys, Liver, Heart**, and **Systemic (Overall) Health**.  

The dashboards compare **Healthy** vs **Damaged** cohorts across:
- Total patients & average age/BMI
- Smoking status (Never / Current / Former)
- Smoking intensity (Years of Smoking & Cigarettes per Day)
- Gender distribution
- Cholesterol & Hypertension risk by age group

**Total records analysed**: 1,500+ patient entries (organ-specific cohorts).

**Objective**: To visually demonstrate the strong association between current smoking and organ damage, and to highlight the protective effect of quitting.

---

## Overall Summary of Findings
- **Current smokers** are dramatically over-represented in damaged groups for **lungs (+18.5 pp)**, **kidneys (+22 pp)**, **liver (+5.7 pp)**, and **systemic health (+20.3 pp)**.
- Damaged lung and liver patients are **younger** on average → smoking accelerates premature organ damage.
- **Former smokers** consistently appear in higher proportions in healthy cohorts → quitting works.
- Heart damage shows almost identical smoking status distribution → other factors (cholesterol, hypertension, age) dominate.
- Smoking intensity peaks in the 30–50 age group among damaged cases.
- Males dominate current and former smoker categories across all dashboards.

---

## Organ-Specific Analyses

### Lungs
**Key Insight**: Largest visible smoking-related damage. Current smokers are 18.5 percentage points higher in the damaged group.

**Healthy Lungs** (310 patients, avg age 54.6)  
![](/Dashboard%20Screenshots/Healthy%20Lungs.png)

**Damaged Lungs** (168 patients, avg age 51.1)  
![](/Dashboard%20Screenshots/Damaged%20Lungs.png)

**Findings**:  
- Current smokers: **48.81%** (damaged) vs **30.32%** (healthy)  
- Never smokers drop from 40.32% to 26.79%  
- Damaged patients are 3.5 years younger on average.

### Kidneys
**Key Insight**: Strongest association with current smoking.

**Healthy Kidneys** (296 patients, avg age 54.1)  
![Healthy Kidneys](/Dashboard%20Screenshots/Healthy%20Kidney.png)

**Damaged Kidneys** (174 patients, avg age 53.9)  
![Damaged Kidneys](/Dashboard%20Screenshots/Damaged%20Kidney%20.png)

**Findings**:  
- Current smokers: **51.72%** (damaged) vs **29.73%** (healthy) → **+22 pp** (largest gap)  
- Never smokers: only 26.44% in damaged group.

### Liver
**Healthy Liver** (342 patients, avg age 53.3)  
![Healthy Liver](/Dashboard%20Screenshots/Healthy%20Liver.png)

**Damaged Liver** (207 patients, avg age 52.5)  
![Damaged Liver](/Dashboard%20Screenshots/Damaged%20Liver.png)

**Findings**:  
- Current smokers: **32.85%** (damaged) vs **27.19%** (healthy) → +5.7 pp  
- Damaged patients are younger and have slightly lower BMI.

### Heart
**Healthy Heart** (336 patients, avg age 53.7)  
![Healthy Heart](/Dashboard%20Screenshots/Healthy%20Heart.png)

**Damaged Heart** (193 patients, avg age 54.9)  
![Damaged Heart](/Dashboard%20Screenshots/Damaged%20Heart.png)

**Findings**:  
- Current smokers: **30.95%** (healthy) vs **30.57%** (damaged) → almost identical distribution.  
- Damaged patients are older → cumulative effect more visible.

### Systemic Health (Overall Human Body)
**Healthy Systemic** (319 patients, avg age 54.9)  
![Healthy Human Body](/Dashboard%20Screenshots/Healthy%20Human%20Body.png)

**Damaged Systemic** (155 patients, avg age 57.5)  
![Damaged Human Body](/Dashboard%20Screenshots/Damaged%20Human%20Body.png)

**Findings**:  
- Current smokers: **50.97%** in damaged cohort (highest rate observed).  
- Clear systemic impact of continued smoking.

---

## Implications for the Health Sector
- Smoking is the **single strongest modifiable risk factor** for preventable damage to lungs, kidneys, liver, and overall health.
- Damage appears **earlier** in smokers (especially lungs and liver).
- Quitting smoking demonstrably shifts patients toward the healthy cohort.
- Heart damage is driven more by the combination of smoking + cholesterol + hypertension.

---

## Recommendations
**Clinical**  
- Mandatory smoking-status screening in pulmonology, nephrology, hepatology, and cardiology.  
- Flag current smokers as high-risk for lung, kidney, and liver damage regardless of age.  
- Integrate smoking-cessation counselling into routine visits for patients with high cholesterol/hypertension.

**Public Health**  
- Target 30–50 age group with aggressive cessation campaigns (highest intensity & earliest damage).  
- Prioritise male smokers in cessation programmes.  
- Expand access to free nicotine replacement, counselling, and medication.

**Policy**  
- Fund early screening (low-dose CT, eGFR, LFTs) specifically for current smokers aged 40+.  
- Support workplace and community smoking-cessation initiatives.

**Further Research**  
- Longitudinal studies on risk reduction after quitting.  
- Pack-year dose-response analysis.  
- Interaction between smoking and metabolic risks.

---

## How to Use This Project
1. Open the `.pbix` file in Power BI Desktop.  
2. Use the left navigation to switch between organs.  
3. Toggle between **Healthy** and **Damaged** views using the top buttons.  
4. Hover over charts for exact values and tooltips.

**Technologies**: Power BI Desktop, DAX, Power Query, custom visuals.

---

**Author**: Raji Toluwanimi Samuel  
**Date**: February 2026  
**License**: Techcrush Data Analytics Certificate
---
