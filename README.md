IPL Data Analysis

Overview

This project performs exploratory data analysis on IPL match data to identify patterns in team performance, toss decisions, player performance, venues, scoring, bowling, and match-winning margins.

The analysis uses Python and visualization libraries to transform match-level data into actionable insights about IPL matches and player performances.

Objectives

Analyze team match wins

Investigate the relationship between toss winners and match winners

Explore toss decisions and match-winning methods

Identify players receiving the most Player of the Match awards

Analyze top scorers and high-scoring performances

Identify leading bowling performances

Explore venue-wise match frequency

Find the largest winning margins

Identify the highest individual score and strongest bowling figures

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Dataset

The notebook analyzes an IPL dataset containing 74 matches and 20 columns.

Important fields used in the analysis include:

match_winner

toss_winner

toss_decision

won_by

margin

player_of_the_match

top_scorer

highscore

best_bowling

best_bowling_figure

venue

Analysis Performed

Team Performance

Match winners were analyzed using frequency counts to identify teams with the most wins in the dataset.

Toss Analysis

The project compares toss_winner and match_winner to calculate the percentage of matches in which the team winning the toss also won the match.

Toss decisions were also visualized to understand the choices made after winning the toss.

Player Performance

The notebook analyzes:

Players with the most Player of the Match awards

Most frequent top scorers

Aggregate high scores

Leading bowling performances

The bowling analysis extracts the wicket count from the best_bowling_figure field before aggregating bowling performance.

Venue Analysis

Match counts were grouped by venue to identify venues hosting the most matches in the dataset.

Winning Margins

Matches won by runs were sorted by margin to identify the largest run-based victory.

Individual Records

The project identifies:

Highest individual score

Highest wicket-taking bowling performance

Largest winning margin

Key Findings

Based on the analysis in the notebook:

Wankhede Stadium had the highest number of matches in the analyzed dataset.

Chennai recorded the highest winning margin by runs in the dataset.

Quinton de Kock recorded the highest individual score.

The notebook calculates the percentage of matches where the toss winner was also the match winner.

Player of the Match awards, top-scoring performances, and bowling performances are explored using frequency and aggregation analysis.

Visualizations

The notebook includes:

Bar charts

Count plots

Player-performance charts

Venue-frequency charts

Winning-margin analysis

Top-scorer analysis

Bowling-performance analysis

Project Structure

ipl-data-analysis/
├── README.md
├── notebook/
│   └── IPL_Capstone_Project.ipynb
├── data/
│   └── IPL.csv
└── requirements.txt

How to Run

Clone the repository.

Install the required Python packages.

Place IPL.csv in the expected data location.

Open IPL_Capstone_Project.ipynb in Jupyter Notebook or JupyterLab.

Run the notebook cells sequentially.

Future Improvements

Analyze season-wise performance trends

Compare team batting and bowling performance

Build player-level performance rankings

Analyze toss impact across seasons

Create interactive dashboards using Power BI, Tableau, or Plotly

Build predictive models for match outcomes

Author

Sagar Manohar
