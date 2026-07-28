# EV Charging Station Demand Forecasting and Visualization

## Overview
This project focuses on analyzing EV charging station data to understand charging behavior, energy consumption, charging duration, platform usage, and facility-wise utilization through interactive visualizations. The project demonstrates data preprocessing, exploratory data analysis (EDA), KPI generation, and visualization techniques using Python.

## Objectives
- Clean and preprocess EV charging station data.
- Analyze charging sessions and energy consumption.
- Explore charging patterns across weekdays and facility types.
- Visualize key insights using interactive and static charts.
- Build a foundation for future EV charging demand forecasting.

## Dataset
Dataset Used:
- `station_data_dataverse.csv`

The dataset contains information such as:
- Charging Station
- Facility Type
- Platform
- Energy Consumed (kWh)
- Charging Time (Hours)
- Charging Cost
- Weekday
- Session Details

## Features
- Data Cleaning and Preprocessing
- Dataset Overview
- Summary Statistics
- Missing Value Analysis
- KPI Dashboard
- Distribution Analysis
- Correlation Heatmap
- Weekday Charging Analysis
- Energy vs Charging Cost Analysis
- Charging Time vs Energy Analysis
- Top 10 Charging Stations
- Platform Distribution
- Facility Type Analysis
- Treemap Visualization
- Sankey Diagram
- Geographic Visualization using Folium

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Plotly
- Seaborn
- Folium

## Project Structure

```
EV-Charging-Station-Demand-Forecasting-and-Visualization/
│
├── EV_Charging_Station_Demand_Forecasting_and_Visualization.ipynb
├── station_data_dataverse.csv
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/EV-Charging-Station-Demand-Forecasting-and-Visualization.git
```

Move into the project directory:

```bash
cd EV-Charging-Station-Demand-Forecasting-and-Visualization
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

## Results

The analysis provides insights into:
- EV charging energy consumption
- Charging duration patterns
- Facility-wise charging behavior
- Platform usage distribution
- Weekday charging trends
- Relationships between charging time, energy, and cost

## Future Enhancements

- Implement machine learning models for demand forecasting.
- Build a real-time dashboard.
- Integrate live EV charging station data.
- Deploy the project using Streamlit.

## Author

**Linsha Bangera**

Computer Science & Data Science Engineering

## License

This project is intended for educational and learning purposes.
