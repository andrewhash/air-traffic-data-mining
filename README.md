# air-traffic-data-mining
Air traffic passenger classification project using Python
# Air Traffic Passenger Statistics - Classification Project

This project is a part of the ADS-502 course in the Applied Data Science 
Program at the University of San Diego.

-- Project Status: Active

## Installation
1. Clone the repo: git clone https://github.com/andrewhash/air-traffic-data-mining.git
2. Install dependencies: conda install pandas numpy scikit-learn matplotlib seaborn jupyter
3. Run: jupyter notebook

## Project Intro/Objective
The main purpose of this project is to classify air traffic volume at 
San Francisco International Airport as high or low based on historical 
passenger data spanning 1999–2026. This analysis aims to identify key 
factors that drive passenger traffic levels across airlines, terminals, 
and geographic regions.

## Contributor
- Andrew Hashoush
- Christopher Guillen
- Dana Neuman

## Methods Used
- Data Mining
- Classification Modeling
- Exploratory Data Analysis
- Predictive Modeling
- Data Visualization
- Data Manipulation

## Technologies
- Python
- Jupyter Notebook
- pandas, numpy, scikit-learn, matplotlib, seaborn

## Project Description
Dataset: San Francisco Air Traffic Passenger Statistics (data.sfgov.org)
- 39,588 records, 15 variables
- Covers July 1999 through 2026
- Key variables: airline, terminal, boarding area, geo region, 
  activity type, passenger count

Target variable: traffic_level (High = top 25% of passenger count, Low = bottom 75%)

Questions being explored:
- What factors best predict high vs. low traffic volume?
- How have traffic patterns changed over time?
- Which airlines, terminals, and regions drive the most traffic?

## License
Open Data - City and County of San Francisco

## Acknowledgments
- San Francisco Open Data Portal
- University of San Diego Master's of Applied Data Science Program
