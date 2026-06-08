# 24JR1A05H5-AI-DASHBOARD_WEEK-2_ASSIGNMENT
# Titanic Survival Analysis Dashboard

## Overview

This project performs data analysis and visualization on the Titanic dataset using Python, Pandas, and Plotly.

The dashboard:

* Loads the Titanic dataset from an online source
* Cleans and preprocesses the data
* Generates key performance indicators (KPIs)
* Creates interactive visualizations
* Demonstrates basic data filtering and analysis

## Features

### Data Cleaning

* Fills missing values in the `Age` column using the median age
* Fills missing values in the `Embarked` column using the most common value
* Removes unnecessary columns:

  * Cabin
  * Ticket
  * Name
* Creates a new feature:

  * `FamilySize = SibSp + Parch + 1`

### KPI Metrics

* Total passengers
* Number of survivors
* Survival rate
* Average age
* Average fare

### Visualizations

1. Survival Count Bar Chart
2. Survival by Passenger Class
3. Age Distribution by Survival Status
4. Fare Distribution by Passenger Class
5. Gender Distribution of Survivors (Pie Chart)

### Filtering Example

* Female passengers in First Class
* Summary statistics for:

  * Age
  * Fare
  * Survival
  * Family Size

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Plotly

## Dataset

Titanic dataset from Data Science Dojo:

https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

## Project Structure

```text
project/
│
├── ai_dashboard_week_2_assignment.py
├── README.md
└── requirements.txt
```

## Requirements

Create a `requirements.txt` file with:

```text
pandas
numpy
plotly
```

## Installation

### 1. Clone or Download the Project

```bash
git clone <repository-url>
cd <project-folder>
```

### 2. Create a Virtual Environment (Optional)

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install pandas numpy plotly
```

## Running the Project

Run the Python script:

```bash
python ai_dashboard_week_2_assignment.py
```

The script will:

1. Load the Titanic dataset
2. Clean the data
3. Display KPI summaries
4. Open Plotly visualizations in your browser or notebook environment
5. Show filtered analysis results in the terminal

## Expected Output

### Console Output

```text
Data Loaded | shape: (891, ...)
Data Cleaned | Shape: (...)
```

KPI Summary:

```text
Total Passengers : 891
Survived         : 342
Survival Rate    : 38.4%
Average Age      : ...
Average Fare     : ...
```

### Charts Generated

* Survival Count
* Survival by Class
* Age Distribution
* Fare Distribution
* Survivor Gender Breakdown

## Author

AI Dashboard Week-2 Assignment
