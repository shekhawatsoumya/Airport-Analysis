# Airport Analysis Dashboard

A comprehensive analysis of San Francisco International Airport (SFO) flight operations with detailed insights into flight routes, frequencies, and trends for March 2020.

## 📋 Project Overview

This project provides an in-depth analysis of flight operations at San Francisco International Airport (SFO), focusing on flight routes, flight counts, and distance metrics. The analysis identifies key patterns in both long-haul international and short-distance domestic routes, offering insights into airport operations and traffic distribution.

## 📊 Data Source

- **Platform**: Kaggle
- **Dataset**: San Francisco International Airport Flight Data
- **Time Period**: March 2020
- **Scope**: Flight routes, distances, and frequency data from SFO

## 🛠️ Methodology

### Data Cleaning
- **Tool**: Power Query Editor
- **Process**: 
  - Data extraction and transformation from raw Kaggle dataset
  - Data validation and quality checks
  - Removal of duplicates and inconsistencies
  - Data normalization for analysis

### Analysis & Visualization
- **Tool**: Tableau
- **Output**: Interactive dashboard with multiple analytical views

## 📈 Key Analysis & Insights

### 1. **Longest Route Analysis**
- **Focus**: Identifies destinations with maximum flight distances from SFO
- **Key Findings**:
  - Longest routes are to international destinations: **BLR (Bangalore)**, **SIN (Singapore)**, **DXB (Dubai)**, and **MEL (Melbourne)**
  - Long-haul routes have flight counts ranging between 1K to 3K flights
  - BLR and SIN show slightly higher flight frequencies

### 2. **Day-Wise Flight Count (March 2020)**
- **Focus**: Tracks daily flight volume trends throughout March
- **Key Findings**:
  - Flight counts remained stable from March 4-14: **3.0K to 3.2K flights per day**
  - Noticeable decline starting March 19th
  - Significant drop to **~2.7K flights by March 24th**
  - Continued decrease towards month-end

### 3. **Nearest Route Analysis**
- **Focus**: Details closest destination airports and associated flight traffic
- **Key Findings**:
  - Nearest destinations are domestic: **MNH**, **RNO**, **SBP**
  - Distances are under 350 miles
  - MNH leads with the highest count: **17,153 flights**

### 4. **Overall Flight Count Analysis**
- **Focus**: General overview of flight frequencies across all destinations
- **Key Findings**:
  - **Top Destination**: LAX (Los Angeles) with **7,968 flights**
  - Other high-volume routes: JFK, SEA, LAS, ORD, SAN, POX, EWR, SLC, BOS
  - Flight counts range from approximately **2.2K to 8K**

## 📁 Project Structure

```
Airport-Analysis/
├── README.md                          # Project documentation
├── LICENSE                            # License file
├── Raw Data/
│   └── AIRPORT ANALYSIS.xlsx         # Original dataset from Kaggle
├── Clean Data/
│   └── AIRPORT ANALYSIS.xlsx         # Cleaned and processed data
├── Description/
│   └── Description.txt               # Detailed analysis notes
└── Result/
    └── AIRPORT ANALYSIS.twb          # Tableau workbook with dashboard
```

## 🎯 Key Deliverables

- **Interactive Dashboard**: Multi-section Tableau visualization
  - Longest routes visualization
  - Daily flight count trends
  - Nearest routes analysis
  - Overall flight distribution

## 💡 Business Insights

1. **Route Performance**: LAX dominates domestic traffic while BLR/SIN lead in international long-haul routes
2. **Operational Trends**: March 2020 shows initial stability followed by a significant drop in flight volume
3. **Capacity Planning**: Near-distance routes (MNH) have surprisingly high frequency despite short distances
4. **Geographic Distribution**: Strong presence in both domestic high-traffic corridors and strategic international routes

## 🔧 Tools & Technologies

| Task | Tool |
|------|------|
| Data Source | Kaggle |
| Data Cleaning | Power Query Editor |
| Analysis & Visualization | Tableau |
| Data Format | Excel (.xlsx) |

---
