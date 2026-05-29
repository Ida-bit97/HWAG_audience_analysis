# Here We Are Global: Target Audience Analysis

A mixed-methods audience study combining survey analysis and 
logistic regression to help organisation with understanding
why their target audience wasn't converting to paid subscribers.

## 🏢 Context
[Here We Are Global (HWAG)](https://www.linkedin.com/company/here-we-are-global) 
is an organisation supporting dual-career couples navigating 
international relocation. This project was commissioned during 
a volunteer data analyst internship to investigate why the 
organisation lacked paid subscriptions and how to improve 
audience engagement.

## ❓ Business Question
What factors influence whether international job seekers are 
willing to engage with and pay for HWAG's services?

## 🛠️ Tools & Methods
| Tool | Purpose |
|------|---------|
| Python (pandas, sklearn) | Logistic regression model |
| Excel | Exploratory analysis, pivot tables, dashboard |
| Canva | Stakeholder presentation |

## 🔍 Key Findings
- Survey data from 40 respondents (30 selected for analysis) 
  revealed key barriers to paid subscription
- Logistic regression (odds ratios) identified the following predictors 
of payment readiness:

**Factors that increase likelihood of paying:**
- Older age
- Having the same career trajectory as their partner
- Preference for toolkit format of help

**Factors that decrease likelihood of paying:**
- Uncertainty about career track
- Preference for group format of help

These findings were presented to HWAG stakeholders with recommendations 
to tailor their service offering and marketing toward the most 
conversion-ready audience segments.

## 📁 Repository Structure
```
├── HWAG_survey_analysis.ipynb     # Logistic regression analysis
├── Survey_hwag.xlsx               # Raw data, EDA, pivot tables & dashboard
├── Transformed_hwag_python.xlsx   # Preprocessed data for model
├── HWAG_part1.pdf                 # Stakeholder presentation (Canva)
└── README.md
```

## 👤 Author
**Daria Ivchenko** — Junior Data Analyst  
[LinkedIn](https://www.linkedin.com/in/daria-ivchenko-759830325/) · 
[GitHub](https://github.com/Ida-bit97)
