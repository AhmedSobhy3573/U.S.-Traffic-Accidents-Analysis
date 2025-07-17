# U.S. Road Accident Data Analysis & Power BI Dashboard

## Project Overview

This project presents a comprehensive analysis of a large-scale U.S. road accident dataset, combining advanced data cleaning techniques with powerful interactive visualizations through Power BI. The primary goal is to extract meaningful insights to support traffic safety strategies, risk identification, and resource allocation.

---

## Phase 1: Data Cleaning & Preparation

The dataset contains thousands of detailed accident records across various U.S. states, including data on weather, road and light conditions, accident types, vehicle details, demographics, and emergency response times.

### Data Cleaning Steps

1. **Dropped irrelevant columns** (e.g., `Time_of_Day`).
2. **Handled missing values**:
   - Mode-based imputation for categorical features (e.g., `Type_of_Junction`).
   - Mean/median imputation for numerical features (e.g., `Vehicle_Speed`, `Road_Width`).
3. **Visualized missing data** using heatmaps.
4. **Outlier detection** using Z-score method — no significant outliers found.
5. **Saved the cleaned dataset** to:  
   `Cleaned Data/cleaned_Dataset.csv`

---

## Dataset Metadata

| Column Name | Description |
|-------------|-------------|
| **ID** | Unique identifier for each accident record |
| **State** | U.S. state where the accident occurred |
| **Date** | Timestamp of the accident |
| **Day_of_Week** | Day of the week |
| **Weather_Conditions** | Weather at time of accident |
| **Road_Conditions** | Road surface status |
| **Light_Conditions** | Lighting conditions |
| **Type_of_Road** | Road classification |
| **Type_of_Junction** | Junction type |
| **Type_of_Accident** | Accident type |
| **Vehicle_Type** | Type of involved vehicle |
| **Driver_Age_Group** | Age category of driver |
| **Num_Vehicles_Involved** | Count of vehicles |
| **Num_Casualties** | Injuries/fatalities |
| **Speed_Limit** | Legal speed limit |
| **Distance_to_Nearest_Hospital** | Proximity to hospital |
| **Distance_to_Nearest_Police_Station** | Proximity to police |
| **Visibility** | Visibility at time of crash |
| **Road_Width** | Width of the road |
| **Road_Surface_Friction_Coefficient** | Friction level |
| **Vehicle_Speed** | Speed at the time |
| **Time_Taken_for_Emergency_Response** | Emergency response time |

---

## Phase 2: Power BI Dashboard

An interactive Power BI dashboard was created to help stakeholders—such as traffic analysts, emergency responders, and policymakers—understand accident patterns and identify high-risk conditions.

### Key Features

- Visual exploration of accident frequency across states, dates, and locations  
- Dynamic filtering by weather, road type, vehicle type, accident type  
- KPIs: Total accidents, casualties, avg. response time  
- Custom groupings for visibility, hospital access, road width, and age groups  
- DAX-powered calculated columns for sorting and analysis

---

# Project Structure — U.S. Road Accident Analysis

This document outlines the folder and file structure of the project, including data, notebooks, dashboard visuals, and documentation.


```
├── Cleaned Data/
│   └── cleaned_dataset.csv.csv
├── Raw Data/
│   └── road_accident_data.csv
├── Dashboard Icons/
│   ├── Accedent_Icon.png
│   ├── Driver_Icon.png
│   ├── Emergency_Icon.png
│   └── Time_Icon.png
├── Milestone_1_EDA&Data_Cleaning.ipynb
├── Milestone_2_Road_Accident_Dashboard.pbix
├── README.md
```

---

## Root Directory
Contains the main components of the project:

---

## Cleaned Data
Contains the processed dataset after data cleaning.

- `cleaned_Dataset.csv` – Cleaned and ready-to-use dataset for analysis and dashboarding.

---

## Raw Data
Contains the original dataset before cleaning.

- `road_accident_data.csv` – Raw accident data file with missing values and inconsistencies.

---

## Dashboard Icons
Holds custom icons used in the Power BI dashboard for visual enhancement.

- `Accedent_Icon.png`
- `Driver_Icon.png`
- `Emergency_Icon.png`
- `Time_Icon.png`

---

## Jupyter Notebook
Data exploration, preprocessing, and cleaning logic.

- `Milestone_1_EDA&Data_Cleaning.ipynb` – Notebook for EDA, missing value treatment, outlier detection, and data saving.

---

## Power BI Report
Interactive dashboard for accident analysis.

- `Milestone_2_Road_Accident_Dashboard.pbix` – Power BI report with multiple pages and DAX modeling.

---

## Documentation
- `README.md` – Project overview, methodology, dashboard description, and key insights.

