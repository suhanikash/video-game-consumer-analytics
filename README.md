# Player Engagement & Gaming Product Analytics
**Technical Stack: R, Tidyverse (ggplot2, dplyr), Quarto**

This project performs a deep-dive analysis into video game telemetry data to identify patterns in player behavior, session frequency, and engagement lifecycles. It bridges the gap between raw data engineering and high-level product strategy.

## Strategic Analytical Objectives
* **Retention Analysis:** Quantifying churn risks by analyzing player activity drop-offs over time.
* **Monetization & Engagement:** Investigating the correlation between session length and in-game progression metrics.
* **Segment Discovery:** Utilizing clustering logic to identify distinct "Player Personas" based on playstyle and frequency.

## Technical Execution
* **Complex Data Wrangling:** Leveraged `dplyr` for advanced joining and transformation of multi-source gaming datasets.
* **Statistical Visualization:** Developed high-density `ggplot2` visualizations to map distribution curves of player achievement and session durations.
* **Iterative EDA:** Performed rigorous exploratory data analysis to isolate variables that most significantly impact long-term user retention.
* **Reproducible Reporting:** Authored in Quarto to provide a transparent, audit-ready pipeline from raw data to final conclusion.

## Key Conclusions & Business Impact
* **Identifying Churn:** Pinpointed specific "friction points" in the user journey where player engagement significantly declined.
* **Optimization Recommendations:** Proposed data-backed shifts in game mechanics to increase daily active users (DAU).
* **Targeted Strategy:** Segmented user data to allow for more personalized marketing and community engagement efforts.

## Repository Contents
* `project_3_game_analytics.qmd`: The primary R-source file containing the analytic logic and visualizations.
* `data/`: Sampled player engagement logs.
