# London vs Seattle Precipitation Rain


This project compares precipitation patterns between Seattle, Washington, and London, United Kingdom, using daily weather data from January 1, 2018, to December 31, 2022. The purpose of this analysis is to explore how precipitation differs between the two cities and identify patterns and trends in their precipitation over the five-year period.

---

## Project Overview

This project analyzes and compares precipitation patterns in Seattle and London using daily weather data from January 1, 2018, to December 31, 2022. The goal is to determine how precipitation differs between two cities commonly associated with rainy weather. Although the total precipitation over the five-year period was very similar, the yearly analysis revealed noticeable differences. London recorded more precipitation in 2018 and 2019, while Seattle recorded more precipitation from 2020 through 2022.

- **Objective:** Compare precipitation patterns between Seattle and London from 2018 to 2022 to identify similarities, differences, and changes in precipitation over time.
- **Domain:** Environmental Data Science / Weather and Climate Analysis
- **Key Techniques:** Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, Descriptive Statistics, and Time Series Analysis.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND 
- **Description:** The final dataset contains 3,652 daily weather observations for London and Seattle from January 2018 through December 2022. It includes four features: date, city, precipitation, and day of the year. Precipitation is measured in inches and stored as numerical data, while the date is stored in datetime format and the city identifies the location of each observation.
- **License:** (if applicable)

---

## Analysis

The analysis was performed in a Jupyter Notebook using Python. The notebook contains the complete workflow for preparing, exploring, and comparing the London and Seattle precipitation data.

To reproduce the analysis, the notebook should be run from top to bottom. The code first imports the required Python libraries and loads the original weather datasets. Next, the data is inspected and cleaned by selecting the relevant features, handling missing dates and precipitation values, standardizing the datasets, and combining the London and Seattle data into a single DataFrame. Additional date-related features are then created to support the analysis.

After preprocessing, exploratory data analysis is performed to compare precipitation between the two cities. This includes calculating the total precipitation during the five-year period, comparing yearly precipitation, counting the number of days with precipitation greater than 0.0 inches, and creating visualizations to identify patterns and differences between London and Seattle from 2018 through 2022.

---

## Analysis File

The data cleaning and analysis are performed in:

Weather_data.ipynb

---

## Clean Data File

The cleaned dataset used for the analysis is:

clean_seattle_london_weather.csv

---

## Results

The analysis showed that Seattle and London received very similar total precipitation between 2018 and 2022. London recorded a total of approximately 205.615 inches of precipitation, while Seattle recorded approximately 206.832 inches.

However, the frequency of precipitation was noticeably different. Out of 1,826 days, London had 634 days with precipitation greater than 0.0 inches, representing approximately 34.7% of the days. Seattle had 999 days with precipitation greater than 0.0 inches, representing approximately 54.7% of the days.

The yearly comparison also revealed differences between the two cities. London received more precipitation in 2018 and 2019, with 2019 having the highest annual precipitation in the dataset. Seattle received more precipitation in 2020, 2021, and 2022.

These findings show that although London and Seattle received nearly the same total amount of precipitation over the five-year period, Seattle experienced precipitation much more frequently than London. This suggests that the total amount of precipitation alone does not fully describe the differences in precipitation patterns between the two cities.

---

## Author

- Mariana Butarov - [@MariButarov](https://github.com/MariButarov)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: Python and Jupyter Notebook, with Pandas and NumPy for data cleaning and analysis and Matplotlib for data visualization.
- Tutorials or papers referenced
- Inspiration or collaborators
