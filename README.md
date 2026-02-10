# MLB Player Career & Payroll Analysis Using SQL

Developed a comprehensive SQL-based analysis of Major League Baseball (MLB) historical data to evaluate **player career longevity, educational talent pipelines, and team payroll strategies.**

The project leverages multi-table relational datasets to generate insights relevant to **talent development, financial strategy, and player demographics.**

---

## Key Insights Summary

- Player production peaked during the 1990s, reflecting league expansion and increased scouting reach.
- A small subset of teams consistently accounts for a disproportionate share of total salary expenditure.
- Long-term player retention (10+ years with a single team) is rare and appears increasingly uncommon..
- Certain universities function as sustained talent pipelines across multiple decades.
- Player physical attributes at debut show measurable decade-over-decade shifts.


## Part I: Education & Talent Pipeline Analysis
This section examines the relationship between educational institutions and MLB player output.

### Insights
- **Schools by Decade**: The 1990s produced the highest number of MLB players overall. (494)
- **Top Schools**: The University of Texas at Austin emerged as the most prolific contributor historically. (107)
- **Top Schools by Decade**: Arizona State University led player production during the 1970s, highlighting era-specific dominance. (32)

![image](https://github.com/user-attachments/assets/fa590935-b278-4541-8e6c-4c84e9aadc71)
![image](https://github.com/user-attachments/assets/54c32bed-ed84-4326-8721-e713136b2fc2)
![image](https://github.com/user-attachments/assets/287be6f1-e273-4be9-b4e2-c050038bc00e)


---

## Part II: Team Payroll & Financial Strategy
This section analyzes historical salary data to understand team-level spending behavior and financial growth patterns.

### Insights
- **Top-Spending Teams**: Identification of the top 20% of teams by average annual payroll.
- **Cumulative Spending**: Cumulative salary expenditure over time.
- **Billion-Dollar Threshold**: Determined the first year each team surpassed $1 billion in total salary spending.

![image](https://github.com/user-attachments/assets/4927f974-9ab5-47ca-aa56-dc1b456998eb)
![image](https://github.com/user-attachments/assets/008cf3d5-8ed9-4c85-ba3f-361c5a7489a8)
![image](https://github.com/user-attachments/assets/f156e115-3307-4c5c-bac7-4a0418d3919e)

---

## Part III: Player Career Analysis
This section evaluates career duration, team loyalty, and player movement.

### Insights
- **Career Length & Age**: Career longevity varies widely, with only a small fraction of players maintaining long-term tenure with one organization.
- **Team Transitions**: Team changes across a career are more common than long-term retention.
- **Longevity on One Team**: Players who start and finish with the same team represent a distinct minority, underscoring the volatility of professional sports careers.


<img width="359" alt="image" src="https://github.com/user-attachments/assets/0f325257-c237-4471-80b0-6bb2e8a540c8" />
<img width="458" alt="image" src="https://github.com/user-attachments/assets/3ca0aa1d-4a02-4965-9ef6-bf0a0d563dca" />
<img width="98" alt="image" src="https://github.com/user-attachments/assets/4716643d-4989-4383-b448-d9ad18eafb91" />

---

## Part IV: Player Comparison Analysis
This section focuses on shared characteristics and population-level trends among players.

### Insights
- **Shared Birthdays**: Found players who share the same birthdate (1980–1990).
- **Batting Hand Distribution**: Analyzed the percentage of right, left, and both-handed batters per team.
- **Physical Trends**: Tracked average debut height and weight by decade, along with decade-over-decade changes.


<img width="247" alt="image" src="https://github.com/user-attachments/assets/122e442e-37ef-4563-92a3-89106a1be7b7" />
<img width="229" alt="image" src="https://github.com/user-attachments/assets/a82175b8-548a-4503-bb94-cb88c73f402f" />
<img width="213" alt="image" src="https://github.com/user-attachments/assets/381815eb-5fa1-49da-97fc-474048aa0051" />

---

## Tools & Techniques

- SQL (MySQL syntax)
- Complex joins across multiple tables
- Aggregations and grouping
- Window functions for ranking and cumulative calculations
- Common Table Expressions (CTEs) for query clarity and reuse
- Filtering and cohort-based analysis

---

## Dataset Tables

- `school_details`: Full names and IDs of schools
- `schools`: Records of MLB players and their school affiliations
- `players`: Personal and career data for MLB players
- `salaries`: Player salaries, by year and team

---

## Purpose

This project showcases advanced SQL querying skills through real-world sports data analysis. It can serve as a portfolio project for aspiring data analysts and sports data enthusiasts.
