# Car Data Analysis with Reliability Ratings

## Overview

This project analyzes a used car dataset enriched with scraped reliability ratings to uncover insights about car prices, fuel efficiency, features, and value for money. Using Python, Selenium, and various data analysis and visualization libraries, we explore how factors such as car age, mileage, engine size, and reliability affect resale price and fuel efficiency.

## Features

- **Dataset enrichment:** Scrapes reliability ratings for car models from an external source to enhance the original dataset.
- **Exploratory Data Analysis (EDA):** Examines relationships between price, mileage, age, fuel efficiency, luxury features, and reliability.
- **Value-for-money analysis:** Identifies cars offering the best and worst value based on reliability and price.
- **Hypothesis testing:** Uses t-tests to statistically verify if reliability significantly impacts car prices.
- **Visualizations:** Includes scatter plots, bar charts, heatmaps, and more to clearly communicate insights.

## Dataset

The base dataset includes columns such as:

| Column                  | Type     | Description                        |
|-------------------------|----------|----------------------------------|
| brand                   | object   | Car manufacturer                 |
| model                   | object   | Car model                       |
| year                    | float64  | Manufacturing year               |
| mileage                 | float64  | Mileage (km or miles)            |
| engine                  | object   | Engine type                     |
| engine_size             | float64  | Engine displacement (liters)     |
| transmission            | object   | Transmission type                |
| fuel_type               | object   | Fuel type (gasoline, hybrid, etc.) |
| drivetrain              | object   | Drivetrain type (FWD, AWD, etc.)|
| min_mpg, max_mpg        | float64  | Fuel efficiency range            |
| safety & luxury features| float64  | Binary indicators (0/1)          |
| price                   | object   | Resale price                    |

This dataset is enriched by scraping **reliability ratings** for each car model.

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Google Chrome Browser
- ChromeDriver (automatically managed via `webdriver-manager`)

