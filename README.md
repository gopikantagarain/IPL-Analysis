# IPL Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on Indian Premier League (IPL) match data. The objective is to analyze match trends, toss decisions, team performance, and player statistics using Python and data visualization techniques.

---

## Dataset

The dataset contains match-level information such as:

* Match date and venue
* Teams played
* Toss winner and decision
* First and second innings scores
* Match winner and margin
* Player of the Match
* Top scorer
* Best bowling figures

File used:
IPL.csv

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Analysis Performed

### Data Cleaning

* Checked for missing values
* Processed bowling figures
* Extracted highest wickets and runs conceded

### Exploratory Data Analysis

* Toss decision distribution (Bat vs Field)
* Match outcome analysis
* First vs Second innings score comparison
* Team performance insights

### Player Performance

* Best bowling performance
* Highest individual scores
* Player of the Match analysis

---

## Key Insights

* Most teams prefer to **field after winning the toss**.
* Chasing teams have a higher winning probability.
* Identified top bowling performances based on wickets and runs conceded.
* High-scoring matches increase the chances of winning while batting first.

---

## How to Run the Project

1. Clone the repository
   git clone https://github.com/gopikantagarain/IPL-Analysis.git

2. Open the project folder

3. Open Jupyter Notebook

4. Run the file
   IPL_Analysis.ipynb

---

## Project Structure

IPL-Analysis/
│
├── IPL_Analysis.ipynb
├── IPL.csv
├── README.md

---

## Author

Gopikanta Garain

---

## Future Improvements

* Add machine learning model to predict match winner
* Create interactive dashboard using Plotly
* Perform season-wise analysis
* Build team win percentage visualization
