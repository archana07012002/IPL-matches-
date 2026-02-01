
# IPL Data Analytics Dashboard (2008 - 2024)
An interactive, end-to-end data visualization project built in Power BI that analyzes Indian Premier League (IPL) match data across 17 seasons. This dashboard provides deep insights into team performances, player statistics, venue impacts, and match-day decision-making trends.
## 📊 Project Overview
The goal of this project was to transform raw IPL dataset into an actionable dashboard that allows users to drill down into specific seasons, match types (League vs. Playoffs), and team-specific metrics.
### Key Insights Tracked:
Team Performance: Analysis of the most successful teams and win margins.
Toss Influence: Visualization of how "Bat vs. Field" decisions impact the final match outcome.
Player Milestones: Tracking "Player of the Match" awards and top individual contributors.
Venue & Hosting: Identifying cities with the most matches hosted and stadium-specific trends.
Match Dynamics: Correlation between target runs and winning margins.
## 🛠️ Tech Stack & Tools
Data Visualization: Power BI Desktop
Data Transformation: Power Query (ETL process)
Calculations: DAX (Data Analysis Expressions) for custom measures (e.g., Average Target Runs, Win %).
Data Source: IPL Match Dataset (2008-2024).
## 📈 Dashboard Features
#### 1. High-Level KPIs
Located at the top of the dashboard, providing instant visibility into:
Total Matches Played (1095+)
Most Successful Team (Chennai Super Kings)
Average Target Runs across seasons (165.68 - 190.59 depending on filters).
IPL Season Count.
#### 2. Interactive Slicers
Users can filter the entire dashboard by:
Match Type: Toggle between League, Qualifier 1, Qualifier 2, Eliminator, and Finals.
Season: Specific analysis for any year from 2008 to 2024.
#### 3. Visual Breakdowns
Toss Decision (Pie Chart): Shows that teams choose to Field in approximately 64% of matches.
Toss Winner vs. Match Winner: A 100% stacked bar chart visualizing the correlation between winning the toss and winning the game.
Target Runs vs. Margin (Scatter Plot): Analyzes the competitiveness of matches based on the score set.
Most Successful Teams/Umpiring: Bar charts detailing team wins and top-performing umpires (e.g., AK Chaudhary, Nitin Menon).

open the main dashboard file ([Insert filename - <a href="https://github.com/archana07012002/IPL-matches-/blob/main/IPL%20Matches.pbix])


## 🚀 How to Use
Clone this repository.
Open the .pbix file using Power BI Desktop.
Interact with the Match Type and Season dropdowns to see how the data shifts.
## 💡 Key Learnings
Implemented DAX measures to calculate rolling averages and win percentages.
Utilized Power Query to clean and format inconsistent team names (e.g., handling name changes like Delhi Daredevils to Delhi Capitals).
Designed a User-Centric UI using a consistent color palette and "dark mode" aesthetics for better readability.
