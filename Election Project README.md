# Election Analysis Project

## Overview
This project analyzes U.S. presidential election data to explore voting trends, demographic shifts, and key electoral insights from 2016 and 2024. It involves data cleaning, exploratory analysis, and visualization of election results.

## Project Structure
- `Final_Election_Analysis_Project.ipynb`: Jupyter Notebook containing data cleaning, analysis, and visualizations.
- `Election Project Data.zip`: Contains election datasets.
  - `PD43+__2016_President_Democratic_Primary.csv`: 2016 Democratic Primary election results.
  - `PD43+__2016_President_General_Election.csv`: 2016 General Election results.
  - `PD43+__2024_President_General_Election.csv`: 2024 General Election results.
- `README.md`: Project documentation.

## Installation
To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/DanaKChilds/SQL-Election-Project.git
   cd SQL-Election-Project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(Ensure you have Python, Pandas, and Jupyter installed.)*

3. Unzip the data file:
   ```bash
   unzip Election\ Project\ Data.zip -d data/
   ```

4. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `Final_Election_Analysis_Project.ipynb` and execute the cells.

## Features
- **Data Cleaning:** Removes unnecessary columns, standardizes naming conventions.
- **Exploratory Data Analysis:** Identifies voter trends and key demographic shifts.
- **Election Result Comparisons:** Compares Democratic and Republican performance in 2016 vs. 2024.
- **Visualizations:** Uses Matplotlib for insights.

## Data Sources
The datasets originate from Massachusetts election records and include municipality-level vote counts.

## Usage
This project provides insights for political analysts, researchers, and data scientists exploring U.S. electoral trends.

## Contributing
Contributions are welcome! Fork the repository and submit pull requests.
