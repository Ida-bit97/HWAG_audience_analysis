# Here We Are Global: Target Audience Analysis

A mixed-methods audience study combining survey analysis, logistic regression, and in-depth interviews to help an organisation understand why their target audience wasn't converting to paid subscribers.

## 🏢 Context
[Here We Are Global (HWAG)](https://www.linkedin.com/company/here-we-are-global) 
is an organisation supporting dual-career couples navigating 
international relocation. This project was commissioned during 
a volunteer data analyst internship to investigate why the 
organisation lacked paid subscriptions and how to improve 
audience engagement.
The project ran in two parts: 
- Part 1 (December 2025) explored the question quantitatively through a survey;
- Part 2 (June 2026) followed up with in-depth interviews to explain and deepen those findings.

## ❓ Business Question
What factors influence whether international job seekers are 
willing to engage with and pay for HWAG's services?

## 🛠️ Tools & Methods
| Tool | Purpose |
|------|---------|
| Python (pandas, sklearn) | Logistic regression model |
| Excel | Exploratory analysis, pivot tables, dashboard |
| Canva | Stakeholder presentation |

**Part 1 — Quantitative**: survey of 30 respondents, analysed with descriptive statistics and logistic regression (odds ratios).

**Part 2 — Qualitative**: 7 semi-structured in-depth interviews (45–90 minutes each, conducted in English), used to explain and deepen the Part 1 findings and test reactions to HWAG's website and product offering.

## 🔍 Key Findings
**Part 1 — Quantitative**
- Survey data from 40 respondents (30 selected for analysis) 
  revealed key barriers to paid subscription
- Logistic regression (odds ratios) identified the following predictors 
of payment readiness:

*Factors that increase likelihood of paying:*
- Older age
- Having the same career trajectory as their partner
- Preference for toolkit format of help

*Factors that decrease likelihood of paying:*
- Uncertainty about career track
- Preference for group format of help

**Part 2 — Qualitative**

- A weak local network is the #1 barrier to finding a job in Denmark, confirmed in both the survey (44%) and the interviews;
- A hidden job market exists — most roles are filled through personal connections and never reach public listings;
- Willingness to pay is driven less by demographics than by clarity of outcome: people want a specific, guided process with a committed result, not a general description of services;
- Individual coaching was the clearest paid-product trigger across interviews; a freemium peer-networking app (mixed locals and internationals) also resonated strongly;
- HWAG is currently perceived as an emotional support organisation, which people are not ready to pay for — the recommendation is to reposition towards results-oriented guidance, with clearer product descriptions and visible success stories

These findings were presented to HWAG stakeholders with recommendations 
to tailor their service offering and marketing toward the most 
conversion-ready audience segments.

## 📁 Repository Structure
```
├── HWAG_survey_analysis.ipynb     # Logistic regression analysis
├── Survey_hwag.xlsx               # Raw data, EDA, pivot tables & dashboard
├── Transformed_hwag_python.xlsx   # Preprocessed data for model
├── HWAG_all_research_public.pdf   # Stakeholder presentation (Canva)
└── README.md
```

## 👤 Author
**Daria Ivchenko** — Junior Data Analyst  
[LinkedIn](https://www.linkedin.com/in/daria-ivchenko-759830325/) · 
[GitHub](https://github.com/Ida-bit97)
