# UEFA Champions League Finals Analysis

## Project Description

This project aims to analyze **UEFA Champions League Finals** data by scraping Wikipedia data using **Python**. The project includes data cleaning, missing value analysis, data visualization, and extracting insights by exploring historical trends. 

## Contents

- **Data Cleaning:** Handling missing values ​​and ensuring data accuracy.
- **Missing Value Analysis:** Examining incomplete data and handling them appropriately.
- **Historical Information:** Exploring rules and changes that affected the finals.
- **Data Visualization:** Using graphs to display statistical trends (if applicable).

## Data Source

- Data is extracted from the Wikipedia page for **UEFA Champions League Finals**.
- Tables sorted with **`wikitable plainrowheaders sortable`** are analyzed to extract finals details.
- Data is saved in a data frame (`DataFrame`) using `Pandas`.

## Data Overview

- Data was fetched using `requests` and then analyzed using `BeautifulSoup`.
- Data contains:
- Season.
- Teams.
- Final result.
- Venue.
- Empty values ​​were handled and incomplete rows were removed.


## Tools Used

- **BeautifulSoup**: To extract data from web pages.
- **requests**: To fetch data from Wikipedia.
- **pandas**: To analyze data and organize it in tabular form.
- **re**: To use regular expressions to clean up text.
- **matplotlib.pyplot**: To create charts and display results.



