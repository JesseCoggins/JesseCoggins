# Jesse Coggins — Data Analyst · Data Scientist

In nearly a decade of multi-site operations leadership, I tracked revenue, labor and throughput to decide where a team’s time would make the most difference. I brought that perspective to my M.S. in Data Analytics at Western Governors University. These ten coursework projects show how I connect an analysis to a decision and how I judge whether the result is good enough to act on.

[Explore the portfolio case studies](https://jessecoggins.github.io/)

## Featured projects

### Customer churn · Where should a retention team test an offer?

In the telecom data, 37.3% of month-to-month customers churned, compared with 12.7% of customers on two-year contracts. I built a Tableau dashboard so a retention manager can compare those rates by state and choose a group for an outreach experiment. A holdout group would show whether the offer actually keeps more customers. [Interactive dashboard](https://public.tableau.com/shared/Z8Z9SR2NB?:display_count=n&:origin=viz_share_link) · [Project and walkthrough](https://github.com/JesseCoggins/customer-churn-dashboard)

### Loan default · What does a risk flag mean for an underwriter?

At the model’s chosen threshold, 1,380 test loans would have gone to manual review. Of those, 787 defaulted and 593 were repaid. Another 2,186 defaults went unflagged. Those counts give an underwriting team a way to weigh the cost of missed defaults against the number of additional files it can review. [Project](https://github.com/JesseCoggins/loan-default-risk-capstone) · [Stakeholder presentation](https://github.com/JesseCoggins/loan-default-risk-capstone/blob/main/docs/loan-default-presentation.pdf)

### Flight delays · How precise is an estimate for schedule planning?

I built an API that lets a planner compare average departure delays from Atlanta by destination and scheduled times. The pipeline reproduced a held-out RMSE of 8.92 minutes. Its evaluation excluded delays of an hour or more, which limits how a planner should use the estimate during major disruptions. [Flight-delay pipeline](https://github.com/JesseCoggins/flight-delay-mlops)

### Hospital readmission · When would the care team have the information it needs?

Removing length of stay dropped the model’s ROC-AUC from 0.999 to 0.498. That finding changed when I’d evaluate using the score. At discharge, the team knows the completed stay and can consider whom to contact for follow-up. At admission, the model without that information performed near chance. [Hospital readmission analysis](https://github.com/JesseCoggins/hospital-readmission-ml)

## More coursework

| Project | Decision it supports |
|---|---|
| [Cargo network optimization](https://github.com/JesseCoggins/cargo-network-optimization) | Route freight at the lowest modeled cost while meeting demand. The optimal plan used all CVG capacity and left 6,253 tons available at AFW. |
| [EcoMart database design](https://github.com/JesseCoggins/ecomart-relational-nosql-database-design) | Give managers consistent quarterly revenue and profit figures so they can compare regions and product lines across 100,000 sales records. |
| [Hospital revenue forecasting](https://github.com/JesseCoggins/revenue-forecasting-arima) | Give the finance team a 30-day baseline for spotting where actual revenue starts to diverge from the plan. |
| [Statistical analysis and market basket](https://github.com/JesseCoggins/statistical-analysis-and-market-basket) | Choose a bundle to test. One of the strongest product combinations appeared in just five of 441 baskets, a reason to start with a small merchandising trial. |
| [Seedling image classification](https://github.com/JesseCoggins/seedling-image-classifier) | Help botanists sort crop and weed images. Species-level results show which labels most need an expert’s second look. |
| [Movie-review sentiment](https://github.com/JesseCoggins/sentiment-analysis-bilstm) | Test whether a text classifier could flag complaints for staff to read. The IMDb evaluation shows how many positive reviews also land in that queue. |

## Tools

Python · SQL · Tableau · pandas · scikit-learn · statsmodels · TensorFlow/Keras · PostgreSQL · MongoDB · PuLP · MLflow · DVC · FastAPI · Docker
