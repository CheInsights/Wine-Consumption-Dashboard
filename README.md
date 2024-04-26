# The Wine Dashboard Project

## Introduction
The Wine Dashboard project walks you through the process of transforming a large data file in Excel into a usable dashboard. This dashboard includes graphs and drop-down menu selections to visualize the amount of wine consumed by different countries over time.

## Skills Required
- CONCAT Function
- Drop-Down Lists
- VLOOKUP Function
- Absolute References

## Getting Started
### Download the Data
Start by downloading the Wine Excel data file provided. Follow along with the video tutorial for guidance.

### Data Preparation
- Add a column named "Lookup Key" to the left of the "Country" column.
- Concatenate the country name and the year in the "Lookup Key" column using the CONCAT function.
- Remove duplicates from the list of country names.

### Setting Up the Dashboard
#### Year Over Year Trend
- Adjust the font size and column width for better visualization.
- Set up drop-down lists for country selection and year selection.
- Write a VLOOKUP formula to retrieve wine consumption per capita for the selected country and year.
- Use absolute references to lock cell references appropriately.
- Handle errors using the IFERROR function to display 0 when data is missing.

#### Ranking the Top 5 Countries
- Use the LARGE function to find the top 5 values from the wine consumption data.
- Use VLOOKUP to find the corresponding countries for the top 5 values.

### Adding Excel Charts
- Label the cells for country and year selection.
- Create line and horizontal bar charts to visualize the data.
- Dynamically update chart titles based on the selected country and year.
- Configure axis labels for both charts.
- Group rows and hide them for better presentation.
- Hide gridlines for a cleaner look.

## Conclusion
You now have a fully functional Excel dashboard showcasing wine consumption data by country over time. Feel free to customize and enhance the dashboard further according to your needs.
