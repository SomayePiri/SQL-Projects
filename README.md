# Workforce Program Analytics (Mock Data)

## Project Overview
This project demonstrates **data cleaning, transformation, statistical analysis, and visualization** using mock workforce program data. It mirrors real-world analytics for programs like WIOA, TANF, or other workforce initiatives.

The notebook includes:
- ETL (Extract, Transform, Load) steps
- Data cleaning and feature engineering
- Summary statistics
- Visualizations (bar charts and scatter plots)
- Optional Power BI dashboard integration (can be added by user)

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV for dataset

## Dataset
The mock dataset contains 500 participants with the following columns:
- `Participant_ID`: Unique ID for each participant
- `Program`: Program enrolled (Job Readiness, Technical Skills, Career Coaching)
- `Start_Date` / `End_Date`: Program duration
- `Duration_Days`: Number of days in program
- `Hours_Trained`: Total hours trained
- `Completion_Status`: Complete / Incomplete
- `Outcome_Score`: Score representing program outcome
- `Success`: 1 if Outcome_Score > 80, else 0 (created during ETL)

## How to Use
1. Clone or download this repository.
2. Open `workforce_program_analytics.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to generate analysis and visualizations.
4. Optional: Save visualizations to the `visualizations/` folder.

## Results
- Summary of participants, hours trained, program duration, and success rates.
- Bar chart showing **success rate per program**.
- Scatter plot showing **hours trained vs success**.

## Optional Extensions
- Connect `workforce_data_mock.csv` to Power BI to create interactive dashboards.
- Extend analysis with additional mock features like demographics or employment outcomes.


