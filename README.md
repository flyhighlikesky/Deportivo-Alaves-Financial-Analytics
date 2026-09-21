# Deportivo Alavés — Financial & Recruitment Analytics

> A football analytics and financial decision-support project built with Excel and Power BI to evaluate squad construction, recruitment, tactical fit, financial allocation, and competitive performance.

## Project Overview

This project analyzes Deportivo Alavés over a single season using a combination of financial analysis, recruitment modeling, tactical analysis, match analysis, and business intelligence.

The objective was to determine how a club operating under financial constraints could allocate its transfer and wage resources while building a squad capable of competing for the highest level of domestic success.

Rather than evaluating players based solely on overall ability, the project uses position-specific tactical requirements, financial commitments, recruitment value, and squad needs to support recruitment and squad-management decisions.

The final analysis was presented through an interactive Power BI dashboard designed as an executive decision-support tool.

## The Analytical Approach

The analytical model was developed in Excel and includes position-specific attribute weighting, tactical-fit calculations, recruitment requirements, player value evaluation, squad selection, and financial considerations.

File: Deportivo_Alaves_PowerBI_Ready.xlsx

PBI_Matches

<img width="1707" height="632" alt="Image" src="https://github.com/user-attachments/assets/e560db97-c90d-42f4-95d2-1232672baa42" />

PBI_Opponent_Form

<img width="495" height="410" alt="Image" src="https://github.com/user-attachments/assets/61c632a9-6150-44f2-bbce-b4f8f7de9e16" />

PBI_Players

<img width="1832" height="581" alt="Image" src="https://github.com/user-attachments/assets/e7233184-ed56-46fe-83ec-3b96c4b2d4ee" />

PBI_Suggested_XI

<img width="1413" height="252" alt="Image" src="https://github.com/user-attachments/assets/328c2499-d156-4cfe-8aec-80811279cc20" />

This separate cleaned dataset was prepared specifically for Power BI to ensure that the dashboard could use structured and consistent data.

## Recruitment Strategy

Recruitment decisions were evaluated using several factors rather than player quality alone.

PBI_Recruitment

<img width="910" height="78" alt="Image" src="https://github.com/user-attachments/assets/6ca6de5d-1921-40bb-af63-957a02d74a2c" />

The analysis considered:

- Tactical Fit
- Position-specific requirements
- Transfer cost
- Weekly wage commitment
- Player age
- Value Score
- Existing squad needs

Two completed recruitment decisions were analyzed in detail: **Gustavo Gómez** and **Francis Amuzu**.

Gómez provided a high level of tactical fit for the defensive requirements of the system, particularly through his aerial ability, strength, positioning, decisions, and teamwork.

Amuzu provided pace, movement, and dribbling ability that could improve the team's attacking transitions and complement the team's direct attacking approach.

This framework was designed to answer a financial-analysis question:

> **Does the expected tactical contribution justify the financial commitment?**

## Financial Analysis

The financial analysis evaluated the relationship between recruitment decisions and the club's available resources.

PBI_Financials

<img width="1798" height="39" alt="Image" src="https://github.com/user-attachments/assets/f7d4a142-5b59-4311-b5f9-9596ba8c0407" />

| Financial Metric | Result |
|---|---:|
| Transfer Budget | 14.5M |
| Transfer Spending | 12.244M |
| Remaining Transfer Budget | 2.256M |
| Transfer Budget Utilization | 84.4% |
| Weekly Wage Budget | 513K |
| Current Weekly Wages | 556K |
| Wage Budget Utilization | 108.4% |
| Weekly Wage Variance | -43K |

The recruitment strategy utilized approximately **84.4% of the available transfer budget**, leaving additional transfer capacity available.

However, weekly wages exceeded the stated wage budget by approximately **43K per week**, highlighting an important trade-off between improving the squad and maintaining recurring financial discipline.

The project therefore evaluates both the immediate transfer investment and the ongoing wage commitment associated with recruitment.

## Tactical & Match Analysis

The tactical analysis evaluated players according to the requirements of their positions and the team's tactical approach.

Early match analysis identified several recurring weaknesses, including poor use of width, vulnerability in aerial situations, breakdowns in the final third, and inefficient goalkeeper distribution.

PBI_Opponents

<img width="1383" height="268" alt="Image" src="https://github.com/user-attachments/assets/6982ced7-eb83-465c-8033-e5f2e613b8b7" />
<img width="1630" height="268" alt="Image" src="https://github.com/user-attachments/assets/bf0be163-7f3d-4101-83bb-46c42c40e3ee" />
<img width="657" height="272" alt="Image" src="https://github.com/user-attachments/assets/16c1e8d0-23a3-450a-b46e-490c1b1964e5" />

These observations were incorporated into the recruitment and tactical evaluation process rather than being treated as isolated match results.

## Power BI Dashboard

The final Power BI report transforms the underlying analysis into an interactive decision-support dashboard.

The report evaluates the season through four perspectives:

- Executive performance
- Squad and tactical performance
- Recruitment and financial analysis
- Match and opponent analysis

Dashboard screenshots are provided in the repository, while the Power BI file contains the interactive report.

## Season Outcome

The final season produced:

| Performance Metric | Result |
|---|---:|
| League Finish | 1st |
| Points | 79 |
| Wins | 23 |
| Draws | 10 |
| Losses | 5 |
| Goals For | 56 |
| Goals Against | 34 |
| Goal Difference | +22 |
| Champions League Qualification | Yes |

The results provide the final performance context for evaluating the financial, recruitment, and tactical decisions made throughout the project.

The project does not claim that individual recruitment or tactical decisions directly caused the final result. Instead, the dashboard evaluates how those decisions, financial constraints, squad characteristics, and match observations interacted within the season.

## Key Takeaways

The project demonstrates how a constrained resource environment can be approached through structured analysis rather than relying solely on subjective player evaluation.

The main analytical themes were:

- Allocating recruitment resources toward identified squad needs
- Measuring player suitability using a weighted tactical-fit model
- Comparing recruitment value against financial commitments
- Monitoring transfer-budget utilization and wage variance
- Using match observations to identify recurring tactical weaknesses
- Communicating multiple analytical dimensions through an interactive Power BI dashboard

## Tools & Technologies

**Excel** - data preparation, analytical modeling, weighted scoring, recruitment analysis

**Power Query** - data transformation and preparation

**Power BI** - interactive dashboards and data visualization

**DAX** - KPI, performance, and financial calculations

**OpenAI API** - AI-assisted analytical narrative and interpretation

**GitHub** - project documentation, version control, and portfolio presentation

## Limitations

This project is based on a simulated Football Manager environment rather than real-world football club financial and performance data.

The Tactical Fit and Value Score methodologies were independently designed for this project and should therefore be interpreted as analytical frameworks rather than official Football Manager metrics.

The analysis covers one season, and transfer-income data was not available for calculating net transfer spend.

## Future Development

Future versions could extend the model to multiple seasons, incorporate transfer revenue, evaluate salary efficiency, automate data refreshes, introduce additional performance metrics, and incorporate external football datasets.

---

## Project Structure

```text
deportivo-alaves-financial-analytics/
│
├── processed/
├── raw/
├── powerbi/
├── screenshots/
└── README.md
