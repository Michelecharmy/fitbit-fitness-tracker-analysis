# Fitbit Fitness Tracker Analysis

## Project Overview

This project analyzes Fitbit Fitness Tracker data to understand users' daily activity patterns, including steps, calories burned, activity intensity, and changes in activity over time.

## Business Questions

- How many steps do users take on average?
- Which days of the week show higher and lower activity levels?
- Is there a relationship between steps and calories burned?
- How much time do users spend at different activity intensity levels?
- How does daily activity change over the analyzed period?

## Key Findings

- The average number of steps per user-day was approximately 6,547.
- Wednesday had the highest average number of steps, with approximately 7,511 steps.
- Tuesday had the lowest average number of steps, with approximately 4,915 steps.
- There is a positive relationship between the number of steps and calories burned, although the data shows considerable variation.
- Sedentary activity represented a much larger amount of time than the other activity intensity levels.

## Tools Used

- Google Sheets
- Tableau Public
- GitHub
- CSV

## Data

The analysis uses Fitbit Fitness Tracker data covering the period from March 12, 2016 to April 12, 2016.

The main dataset analyzed was `dailyActivity_merged.csv`.

## Tableau Dashboard

The interactive dashboard was created using Tableau Public:

[View the Tableau Dashboard](https://public.tableau.com/app/profile/michele.martins/viz/FitbitFitnessTrackerAnalysis_17889908623120/FitbitFitnessTrackerAnalysis)

## Project Structure

```text
fitbit-fitness-tracker-analysis/
│
├── data/
│   └── dailyActivity_merged.csv
│
└── README.md 
**

## Limitation

The dataset represents a limited group of Fitbit users who consented to share their data. Therefore, the findings should not be generalized to all Fitbit users.

## Conclusion 

The analysis shows that users spent substantially more time in sedentary activity than in a higher intensity activities.
Step counts also varied considerably depending of the day of the week, while the relationship between steps and calories burned suggests that greater activity is generally associated with higher calorie expenditure.
