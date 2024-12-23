# Analysis of Airbnb Listings

## Introduction

This project explores and analyzes Airbnb listings, focusing on identifying trends and patterns in room types, prices, availability, and other critical aspects. The analysis aims to provide insights into how these factors vary across different boroughs and categories, aiding decision-making for stakeholders such as hosts, guests, and policymakers.

## Dataset Information
**data/airbnb_price.csv**
This is a CSV file containing data on Airbnb listing prices and locations.
- **`listing_id`**: unique identifier of listing
- **`price`**: nightly listing price in USD
- **`nbhood_full`**: name of borough and neighborhood where listing is located

**data/airbnb_room_type.xlsx**
This is an Excel file containing data on Airbnb listing descriptions and room types.
- **`listing_id`**: unique identifier of listing
- **`description`**: listing description
- **`room_type`**: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments

**data/airbnb_last_review.tsv**
This is a TSV file containing data on Airbnb host names and review dates.
- **`listing_id`**: unique identifier of listing
- **`host_name`**: name of listing host
- **`last_review`**: date when the listing was last reviewed

## Analysis Overview

The notebook includes the following steps and methodologies:
1. **Data Cleaning and Preprocessing:**
   - Checked for missing values and imputed or removed them as necessary.
   - Standardized column names and converted data types for consistency.

2. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of prices, availability, and room types.

3. **Key Insights Extraction:**
   - Aggregated data to uncover borough-level trends in room types and pricing.
   - Visualized room type distribution across boroughs.

4. **Visualization:**
   - Created various plots using Matplotlib to display findings.

## Key Findings

- **Room Types Across Boroughs:** The distribution of room types varies significantly by borough, with some boroughs showing a preference for private rooms and others for entire apartments.
- **Price Trends:** Prices exhibit variability not only between boroughs but also across room types, highlighting the importance of location and room quality.
- **Availability Patterns:** Listings in certain boroughs are more consistently available year-round compared to others.

