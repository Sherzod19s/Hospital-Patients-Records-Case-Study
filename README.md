# Hospital-Patients-Records-Case-Study
# 🏥 Hospital Analytics - Massachusetts General Hospital

A comprehensive data analysis project examining patient encounters, costs, coverage, and behavioral trends at Massachusetts General Hospital to support annual performance reporting and operational improvements.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis Objectives](#analysis-objectives)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

---

## 🎯 Project Overview

This project was developed as part of a healthcare analytics consulting engagement to help Massachusetts General Hospital leverage their data for improved patient care and cost reduction. The analysis covers three core areas:

1. **Encounters Overview** - Volume trends, encounter types, and length of stay patterns
2. **Cost & Coverage Insights** - Insurance coverage analysis, procedure costs, and claim patterns
3. **Patient Behavior Analysis** - Visit patterns, readmission rates, and length of stay distributions

---

## 📊 Dataset

The dataset includes synthetic healthcare records with the following key tables:

| Table | Description |
|-------|-------------|
| `encounters` | Patient encounter records |
| `procedures` | Medical procedures performed |
| `patients` | Demographic information |
| `payers` | Insurance provider details |

**Sample Encounter Columns:**
```python
Index(['Id', 'START', 'STOP', 'PATIENT', 'ORGANIZATION', 'PAYER',
       'ENCOUNTERCLASS', 'CODE', 'DESCRIPTION', 'BASE_ENCOUNTER_COST',
       'TOTAL_CLAIM_COST', 'PAYER_COVERAGE', 'REASONCODE',
       'REASONDESCRIPTION'],
      dtype='object')
