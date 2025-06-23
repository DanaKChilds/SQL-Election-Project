# Massachusetts Election Shift Analysis

## Project Description
This project investigates a popular political narrative: that Senator Bernie Sanders’s 2016 Democratic Primary supporters later shifted their allegiance to Donald Trump, contributing to his gains in between the 2016 and 2024 general elections. Focusing on Massachusetts towns, this analysis quantifies the relationship between Sanders's 2016 support in the Democratic primary and Trump’s vote share improvement in the Commonwealth between 2016 and 2024.

## Features
- Cleans and harmonizes town-level vote returns from three elections
- Uses SQL to join datasets and calculate vote share shifts
- Measures correlation between Sanders 2016 support and Trump 2024 gains
- Visualizes the relationship with a regression plot

## Methods and Techniques
- Data cleaning and standardization using pandas
- SQL joins via sqlite3 for multi-source merging
- Vote share and percentage change calculations
- Correlation analysis and Seaborn linear regression visualization

## Data Sources
- Massachusetts Election Statistics from the Secretary of the Commonwealth:
  - 2016 Democratic Primary
  - 2016 General Election
  - 2024 General Election
  - https://electionstats.state.ma.us/

## Dependencies
- Python
- pandas
- sqlite
- seaborn
- matplotlib

## Citation
Vote return data sourced from the Massachusetts Secretary of State's Election Statistics portal (https://electionstats.state.ma.us/)
