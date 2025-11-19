# Environmental Data Analysis: Historical Alaskan Salmon & Wildfire Air Quality

## About

This repository contains two data analysis workflows examining environmental patterns through temporal and spatial lenses. The first analyzes over a century of commercial salmon catch data to identify regional productivity patterns in Alaska fisheries. The second quantifies the impact of California's 2017 Thomas Fire on local air quality using EPA monitoring data.

The project demonstrates:
- Data cleaning and quality control for legacy environmental datasets
- Time series manipulation with datetime indexing and rolling window analysis
- Data type conversion and handling of OCR errors in digitized records
- Aggregation and statistical summarization across geographic regions
- Professional data visualization with contextual annotations
- Integration of multi-year datasets from federal agencies
- Reproducible workflow practices for environmental data science

This work was completed as part of EDS 220 - Working with Environmental Datasets in the UCSB Master of Environmental Data Science program.

## Repository Structure


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

### Data Sources

**Alaska Commercial Salmon Catch Data (1886-1997)**  
Historical commercial salmon catch records from the Alaska Department of Fish & Game, documenting catch volumes (in thousands of fish) by management region, year, and species. This simplified dataset was derived from original reports and published through the Knowledge Network for Biocomplexity.

**EPA Air Quality Index - Daily County Summaries**  
Daily Air Quality Index values for U.S. counties from the Environmental Protection Agency's Air Quality System (AQS). The AQI integrates measurements of major air pollutants (PM2.5, PM10, ozone, CO, SO2, NO2) into a standardized indicator ranging from 0-500.

### Data Access

**Task 2 - Alaska Salmon Analysis:**  
The salmon catch data is **included** in this repository at `task2/data/salmon_data.csv`. No additional downloads required.

**Task 3 - Air Quality Analysis:**  
The EPA AQI data is **accessed directly** from EPA servers within the notebook. The analysis automatically downloads:
- 2017 Daily AQI by County: https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2017.zip
- 2018 Daily AQI by County: https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2018.zip

**Note:** An internet connection is required to run the Task 3 analysis.

## Requirements

This analysis requires Python 3.x with the following packages:
- `pandas` - Tabular data manipulation and time series analysis
- `matplotlib` - Data visualization and plotting
- `numpy` - Numerical operations (implicit dependency)

## References

Byerly, M. (2016). *Alaska commercial salmon catches by management region (1886-1997)* [Data set]. Knowledge Network for Biocomplexity. https://doi.org/10.5063/F1T43R7N

Do-Linh, H., Galaz García, C., Jones, M. B., & Vargas Poulsen, C. (2023). *Open Science Synthesis training Week 1*. NCEAS Learning Hub & Delta Stewardship Council. https://learning.nceas.ucsb.edu/2023-06-delta/session_11.html

Galaz García, C., Cawse-Nicholson, K., Frew, A., & Fontenot, R. (2024). *EDS 220: Working with environmental datasets* [Course materials]. Master of Environmental Data Science, Bren School of Environmental Science & Management, University of California, Santa Barbara. https://meds-eds-220.github.io/MEDS-eds-220-course/

U.S. Environmental Protection Agency. (2024). *Air quality index basics*. AirNow. https://www.airnow.gov/aqi/aqi-basics/

U.S. Environmental Protection Agency. (2024). *Pre-generated data files* [Data files]. Air Quality System (AQS). https://www.epa.gov/outdoor-air-quality-data

Wikipedia contributors. (2024). *Thomas Fire*. In *Wikipedia, The Free Encyclopedia*. https://en.wikipedia.org/wiki/Thomas_Fire

## License

This project is licensed under the terms included in the LICENSE file.

---

*This project is part of the curriculum for the Master of Environmental Data Science program at the Bren School of Environmental Science & Management, UC Santa Barbara.*