# 🚀 Space Missions Data Analysis

## Overview
This project performs end-to-end data analysis on a dataset of 500 space missions,
exploring relationships between mission cost, duration, success rate, scientific
yield, launch vehicles, and target types using Python.

## Dataset
- 500 space missions (2025 onwards)
- 15 features including Mission Type, Launch Vehicle, Target Type,
  Distance from Earth, Mission Cost, Crew Size, and Mission Success %

## Questions Explored
| # | Question | Technique |
|---|---|---|
| Q1 | Which mission type has the highest success rate? | Groupby, Bar chart |
| Q2 | How does mission cost vary across launch vehicles? | Describe, Boxplot, Histogram |
| Q3 | Does farther distance mean longer duration? | Correlation, Scatter plot |
| Q4 | Which target type yields the highest scientific yield? | Groupby, Bar chart |
| Q5 | Is cost difference between successful and partial missions significant? | T-test, Hypothesis testing |

## Tech Stack
- Python 3.x
- Pandas — data manipulation
- Matplotlib — visualization
- Scipy — statistical testing
- NumPy — numerical computing

## Key Findings
- SLS is the most expensive launch vehicle on average
- No strong correlation between distance and mission duration
- [Add your findings after running the analysis]

## How to Run
1. Clone the repository
   git clone https://github.com/yourusername/space-missions-data-analysis.git

2. Install dependencies
   pip install pandas matplotlib scipy numpy

3. Run the notebook
   jupyter notebook space_missions_analysis.ipynb

## Project Structure
space-missions-data-analysis/
│
├── data/
│   └── space_missions_dataset.csv
│
├── space_missions_analysis.ipynb
├── README.md
└── requirements.txt
