# Environmental Data Analysis: Alaska Salmon Fisheries & Wildfire Air Quality Impacts

**Author:** Emily Miller  
**Course:** EDS 220 - Working with Environmental Datasets  
**Program:** UCSB Masters in Environmental Data Science  
**Repository:** https://github.com/rellimylime/eds220-hwk2

---

## About

This repository contains two Python-based data analysis workflows demonstrating essential techniques for working with environmental datasets:

1. **Alaska Commercial Salmon Catch Analysis (1886-1997)**: Analyzes over a century of commercial salmon catch data to identify regional patterns in Alaska fisheries productivity. This workflow demonstrates data cleaning, type conversion, aggregation, and visualization techniques.

2. **Santa Barbara Air Quality During the 2017 Thomas Fire**: Examines the impact of California's Thomas Fire on local air quality using EPA Air Quality Index (AQI) data. This analysis showcases time series manipulation, rolling window calculations, and event-focused visualization.

Both analyses follow professional data science workflow standards with comprehensive documentation, detailed code comments, and reproducible methodology suitable for environmental data science portfolios.

---

## Repository Structure
     └── task2  
        └── data                          # Contains the data used in the analysis, as well as all data used for the tests       
        └── tests                         # Contains a .py file for each test
        └── hwk2-task2-salmon.ipynb       # The empty .ipynb for task 2                                               
     └── task3          
        └── data                          # Contains all data used for the tests
        └── tests                         # Contains a .py file for each test
        └── hwk2-task3-aqi.ipynb          # The empty .ipynb for task 3
  
      └── README.md
      └── License.txt

---

## Data

### Alaska Salmon Data (Task 2)

**Location:** `task2/data/salmon_data.csv`

**Source:** Alaska Department of Fish & Game (via KNB Data Repository)

**Description:** Simplified dataset containing commercial salmon catches by management region from 1886 to 1997. Data includes catch volumes (in thousands of fish) organized by region, year, and salmon species across 18 Alaska management areas.

**To run the analysis:** The data file is included in the repository. Simply open and run `task2/hwk2-task2-salmon.ipynb` in Jupyter.

### Air Quality Index Data (Task 3)

**Location:** Data is accessed directly from EPA servers (no local storage required)

**Source:** U.S. Environmental Protection Agency Air Quality System (AQS)

**Description:** Daily AQI values for all U.S. counties with air quality monitoring. The analysis filters to Santa Barbara County, California for 2017-2018.

**To run the analysis:** Open and run `task3/hwk2-task3-aqi.ipynb` in Jupyter. The notebook automatically downloads data from:
- https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2017.zip
- https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2018.zip

**Note:** Internet connection required for Task 3 analysis.

---

## References

### Course Materials

Galaz García, C., Cawse-Nicholson, K., Frew, A., & Fontenot, R. (2024). *EDS 220 - Working with environmental datasets*. UCSB Masters in Environmental Data Science. https://meds-eds-220.github.io/MEDS-eds-220-course/

### Data Sources - Task 2

Byerly, M. (2016). *Alaska commercial salmon catches by management region (1886-1997)* [Data set]. Knowledge Network for Biocomplexity. https://doi.org/10.5063/F1T43R7N

Do-Linh, H., Galaz García, C., Jones, M. B., & Vargas Poulsen, C. (2023). *Open Science Synthesis training Week 1*. NCEAS Learning Hub & Delta Stewardship Council. https://learning.nceas.ucsb.edu/2023-06-delta/session_11.html

### Data Sources - Task 3

U.S. Environmental Protection Agency. (2024). *Air quality index basics*. AirNow. https://www.airnow.gov/aqi/aqi-basics/

U.S. Environmental Protection Agency. (2024). *Pre-generated data files* [Data files]. Air Quality System (AQS). https://www.epa.gov/outdoor-air-quality-data

Wikipedia contributors. (2024). *Thomas Fire*. In *Wikipedia, The Free Encyclopedia*. https://en.wikipedia.org/wiki/Thomas_Fire

---

## License

This project is licensed under the terms included in the LICENSE file.

---

*This repository was created as part of the EDS 220 course in the UCSB Masters in Environmental Data Science program.*