🏎️ Formula 1 2023 – Team Pace Analysis

📌 Overview
This project is a data-driven analysis of the Formula 1 2023 season, focusing on qualifying session performance to understand how different teams compared in terms of raw pace. Using the FastF1 library, the notebook retrieves official FIA timing data, processes results, and visualizes relative team performance across race weekends.
The analysis specifically looks at:
•	Which driver was fastest within each team during qualifying (Q1, Q2, Q3).
•	How each team’s pace compared against the fastest team on the grid.
•	Visual patterns and trends across the first 10 races of the 2023 season.
This project is part of my portfolio to showcase sports analytics, Python data handling, and visualization skills.
 
⚡ Key Features
•	✅ Automated Data Collection – Retrieve event schedule and session data via FastF1 API.
•	✅ Qualifying Session Analysis – Extract lap times from Q1, Q2, and Q3 for all teams.
•	✅ Team Performance Comparison – Determine fastest driver per team and calculate relative time gaps.
•	✅ Trend Visualization – Use bar charts and line plots to illustrate pace differences between teams.
•	✅ Scalable Approach – Functions can be reused for other seasons or additional rounds.

 
🗂 Project Structure
Formula1-2023-Analysis/
│
├── formula1_analysis_2.ipynb   # Main Jupyter Notebook
├── requirements.txt            # Project dependencies (to be added)
├── README.md                   # Project documentation

Inside formula1_analysis_2023.ipynb:
1.	Library Imports
o	Import core packages (fastf1, pandas, numpy, matplotlib, seaborn).
2.	Event Schedule Retrieval
o	Load the full 2023 Formula 1 calendar with race names, rounds, and dates.
3.	Function: get_team_pace_data(round_number)
o	Fetches qualifying session for a given round.
o	Identifies the fastest lap per driver.
o	Selects the fastest driver per team.
o	Computes each team’s time deficit vs. the overall fastest team.
4.	Loop Through Multiple Rounds
o	Collect team pace data for the first 10 rounds.
o	Store results in a Pandas DataFrame.
5.	Visualization
o	Plot relative pace differences using Matplotlib/Seaborn.
o	Show team-by-team comparison in bar charts and trend plots.

 
⚙️ Tech Stack
•	Programming Language: Python
•	Libraries Used:
o	fastf1 → Fetch official FIA F1 timing and telemetry data.
o	pandas → Data manipulation and analysis.
o	numpy → Numerical calculations.
o	matplotlib → Static plots and visualizations.
o	seaborn → Enhanced data visualization with statistical insights.

  
📊 Results & Insights
•	Teams like Red Bull consistently outperformed others in qualifying, often setting the baseline for fastest pace.
•	Midfield teams (e.g., McLaren, Alpine, Aston Martin) showed variable performance across rounds.
•	Clear visualization of relative gaps helped quantify how far slower teams were from the top team per round.
•	Identified drivers within teams who acted as benchmarks for qualifying speed.
Example Visualizations:
•	Bar Charts → Relative pace difference per team in each round.
•	Line Graphs → Team performance trend across multiple rounds.

 
🔮 Future Enhancements
•	Extend analysis to all 23 rounds of 2023.
•	Incorporate race pace (long-run analysis), not just qualifying.
•	Add driver-vs-driver performance comparisons within the same team.
•	Build interactive dashboards using Plotly/Dash or Streamlit.
•	Introduce predictive modeling to forecast race outcomes.
 

