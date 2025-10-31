# ✈️ Aviation Accident Analysis Project

## 📘 Overview
This project analyzes aviation accident data to uncover patterns, trends, and insights related to aircraft incidents across various countries and years.  
The dataset contains detailed information about each aviation event — including its location, date, severity, weather conditions, and aircraft details.  

The goal is to use this data to understand **factors influencing accident severity**, identify **risk patterns**, identify **operational risk**, identify **market risk**and support **data-driven safety recommendations** for the aviation industry.

---

## 🧠 Problem Statement
Aviation safety is critical, yet accidents still occur due to multiple complex factors such as weather, human error, or technical malfunction.  
This project aims to answer key analytical questions, including:

- What are the most common causes of aviation accidents?
- Which aircraft makes and models are most frequently involved in accidents?
- How have aviation accident trends evolved over the years?

By performing exploratory data analysis (EDA) and visualization, this project seeks to **improve situational awareness** 

---

## 🧾 Dataset Description

The dataset contains detailed records of aviation events.  
Below are the key columns and their meanings:

| Column | Description |
|---------|-------------|
| **EventId** | Unique identifier for each event |
| **InvestigationType** | Indicates if it was an accident or incident |
| **AccidentNumber** | Official accident report number |
| **EventDate** | Date of the event |
| **Location** | City/region where the event occurred |
| **Country** | Country of occurrence |
| **Latitude** | Geographic coordinate (north-south position) |
| **Longitude** | Geographic coordinate (east-west position) |
| **InjurySeverity** | Severity of injuries (e.g., Fatal, Serious, Minor, None) |
| **AircraftDamage** | Extent of aircraft damage (e.g., Destroyed, Substantial) |
| **AircraftCategory** | Type/category of aircraft (e.g., Airplane, Helicopter) |
| **Make** | Manufacturer of the aircraft |
| **Model** | Specific model of the aircraft |
| **PurposeofFlight** | Purpose (e.g., Personal, Commercial, Training) |
| **TotalFatalInjuries** | Number of fatalities |
| **TotalSeriousInjuries** | Number of serious injuries |
| **TotalMinorInjuries** | Number of minor injuries |
| **TotalUninjured** | Number of uninjured occupants |
| **WeatherCondition** | Weather at the time (e.g., VMC, IMC) |
| **ReportStatus** | Status of investigation (e.g., Final, Preliminary) |
| **Year** | Year of occurrence |

---

## 🧩 Methodology

1. **Data Cleaning**
   - Handle missing values
   - Standardize column names and data types
   - Convert dates to proper datetime format

2. **Exploratory Data Analysis (EDA)**
   - Frequency of accidents by year, country, and aircraft make
   - Visualization of accident locations using coordinates

3. **Data Visualization**
   - Bar charts for severity distribution
   - Geospatial scatter plots (using Latitude & Longitude)

4. **Insights & Reporting**
   - Identify top risk factors
   - Use key performance indicators to track injuries
   - Use maps to show market risks in other countries
   - Use time series to show injuries that have occurred in years
   - Summarize findings for safety recommendations

---

## 🧰 Technologies Used

- **Python**
  - `pandas` → Data cleaning and manipulation  
  - `matplotlib` & `seaborn` → Data visualization  
  - `plotly` / `folium` → Interactive geographic mapping  

- **Visual Studio Code Notebook** for analysis and documentation  
- **Git & GitHub** for version control

---

## 📈 Example Questions to Explore
- Which year had the highest number of aviation accidents?
- Which countries report the highest number of accidents?
- What is the relationship between aircraft make/model and damage severity?

---

## 🧩 Project Structure
