# public-transit-policy
“A simple Difference-in-Differences analysis using simulated data.”
# Public Transit Policy - Difference-in-Differences Analysis

This is a simple Difference-in-Differences (DiD) project using simulated data to evaluate whether a free public transit policy reduced average commute times.

## Project Idea
We simulate two regions:
- Region 1: No policy (control group)
- Region 2: Policy introduced in 2020 (treatment group)

## Dataset
File: `transit_policy_data.csv`

| region_id | year | treatment_group | commute_time |
|-----------|------|------------------|--------------|
| 1         | 2019 | 0                | 40           |
| 1         | 2020 | 0                | 38           |
| 2         | 2019 | 1                | 42           |
| 2         | 2020 | 1                | 36           |

## Goal
Use Difference-in-Differences to estimate the impact of the policy using basic regression.

