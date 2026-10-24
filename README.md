# Decarbonizing Business Travel
### Summer Analytics 2026 Capstone | IIT Guwahati

**A Process Intelligence and Predictive AI Approach to Sustainable Business Travel**

## Project Overview

This project explores how process mining, emissions analytics, and machine learning can support more sustainable and efficient business-travel decisions.

Using business-travel data, the project identifies carbon-emission hotspots, examines operational bottlenecks in travel processes, and develops a machine learning approach to flag potentially high-carbon trips before approval.

## Objectives

- Analyze business-travel emissions across regions, travel classes, business units, and travel purposes.
- Identify process variants, delays, and bottlenecks using Celonis.
- Develop a machine learning classifier to predict high-carbon trips.
- Translate analytical findings into practical sustainability and operational recommendations.

## Tools and Technologies

- **Celonis:** Process mining, process exploration, variant analysis, and throughput analysis.
- **Python:** Data analysis and machine learning.
- **Pandas and NumPy:** Data manipulation and analysis.
- **Scikit-learn:** Random Forest classification and model evaluation.
- **Jupyter Notebook:** Experimentation and implementation.

## Key Findings

The analysis of 65,289 business trips highlighted several emission hotspots:

- Business-class flights were the largest identified travel-class emission source, accounting for approximately 73.1 million kg CO₂ in the analysis.
- Europe had the highest total regional emissions, at approximately 62.5 million kg CO₂.
- Sales was the largest emitting business unit, while customer visits represented the highest-emission travel purpose.
- The average travel-process duration was approximately 22.9 days, with some processes taking up to 40.4 days.
- Expense reimbursement was identified as the longest stage in the analyzed travel process.

## Process Mining with Celonis

Celonis was used to examine travel-process flows, process variants, and throughput times. Dashboard screenshots and the corresponding findings are documented in the project presentation.

The analysis highlighted opportunities to investigate delayed approvals, streamline reimbursement workflows, and monitor long-running cases.

## Machine Learning Approach

A Random Forest classifier was developed to predict whether a travel request belongs to the high-carbon category.

The project presentation reports the following model evaluation results:

| Metric | Reported result |
|---|---:|
| Accuracy | 99.16% |
| ROC-AUC | 0.9976 |

These figures are the reported model results, not competition leaderboard scores.

## Business Recommendations

- Encourage Economy-class travel where operationally appropriate.
- Evaluate rail as an alternative to eligible short-haul flights.
- Prioritize high-emission regions, business units, and travel purposes for targeted interventions.
- Explore carbon-aware travel approvals supported by predictive analytics.
- Investigate workflow automation and alerts for delayed approvals and reimbursements.

The presentation estimates that replacing 30% of eligible business-class trips with Economy could avoid approximately 6.95 million kg CO₂ and save approximately $9 million over three years. These are projected scenario estimates, not measured realized savings.

## Repository Contents

- `capstone_analysis.ipynb` — Python analysis and machine learning workflow.
- `capstone_presentation.pdf` — Project presentation containing Celonis dashboard screenshots, findings, and recommendations.

*Note: Filenames above describe the intended repository structure; adjust them if your uploaded files use different names.*

## Project Context

Completed as part of **Summer Analytics 2026**, associated with IIT Guwahati.

