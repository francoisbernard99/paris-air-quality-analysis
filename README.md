# Air Quality Time Series Analysis - Paris

A portfolio project demonstrating air quality data analysis using Python and the European Environment Agency (EEA) API.

## 🎯 Project Overview

This project analyzes SO2 (Sulfur Dioxide) air pollution in Paris during January 2023, demonstrating:
- Data acquisition from public APIs
- Data cleaning and validation
- Time series analysis
- Statistical analysis and visualization

## 📊 Key Results

- **Data Coverage:** 9,922 hourly measurements over 31 days
- **Mean SO2 Concentration:** ~2.06 µg/m³
- **Peak Hours:** 11:00-12:00 (midday)
- **Lowest Hours:** 05:00-06:00 (early morning)
- **Air Quality:** 100% compliance with WHO guidelines

## 🛠️ Technologies Used

- **Python 3.9+**
- **pandas** - Data manipulation
- **numpy** - Numerical operations
- **matplotlib** - Visualization
- **scipy** - Statistical analysis
- **requests** - API interaction
- **pyarrow** - Parquet file handling

## 🚀 Getting Started

### Prerequisites

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt
```

### Run the Analysis

```bash
jupyter notebook paris_air_quality_analysis.ipynb
```

The notebook will:
1. Download data from EEA API
2. Clean and validate the data
3. Perform statistical analysis
4. Generate visualizations
5. Save processed data

## 📁 Project Structure

```
paris_air_quality_analysis/
├── paris_air_quality_analysis.ipynb  # Main analysis notebook
├── data/
│   ├── raw/                          # Downloaded data (auto-generated)
│   └── processed/                    # Cleaned data (auto-generated)
├── requirements.txt                  # Python dependencies
└── README.md                         # This file
```

## 📈 Visualizations

The notebook generates 4 key visualizations:
1. **Time Series Plot** - SO2 trends over January 2023
2. **Distribution Histogram** - Concentration frequency distribution
3. **Daily Pattern** - Hourly variation with confidence intervals
4. **Weekly Pattern** - Day-of-week comparison

## 🔍 Key Findings

- **Daily Cycle:** Clear pattern with peak at midday (~2.19 µg/m³) and minimum in early morning (~1.81 µg/m³)
- **Weekly Pattern:** Minimal variation between weekdays and weekends
- **Data Quality:** High completeness (99.7%) with robust outlier removal
- **Health Impact:** All measurements well below WHO 24-hour guideline (40 µg/m³)

## 📚 Data Source

- **Provider:** European Environment Agency (EEA)
- **API:** https://eeadmz1-downloads-api-appservice.azurewebsites.net/
- **Dataset:** Validated air quality measurements from official monitoring stations
- **Format:** Parquet files (compressed columnar storage)

## 💡 Skills Demonstrated

- API integration and data acquisition
- Data cleaning and quality control
- Time series analysis
- Statistical analysis (percentiles, outliers, trends)
- Data visualization
- Scientific Python stack proficiency

## 📝 License

This project is for educational and portfolio purposes. Data is provided by the European Environment Agency.

## 👤 Author

**François** - Atmospheric Chemistry & Python Programming

## 🔗 Related Projects

This is Project 1 of a 3-project atmospheric sciences portfolio:
1. **Air Quality Time Series** (this project)
2. Satellite Data Analysis (Sentinel-5P)
3. Regression Analysis (Weather vs Air Quality)

---

*Generated for portfolio demonstration purposes*
