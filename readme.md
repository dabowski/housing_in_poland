# Housing Market Analysis in Poland

## Overview
My project focuses on analyzing the housing market in Poland using data collected from web scraping. The primary goal was to investigate the relationship between rental prices, property sizes, and various cities and districts within the country. The analysis was conducted in the R environment, utilizing a range of packages such as tidyverse, caret, and rmarkdown.

## Data Collection
The data was obtained through web scraping from dedicated website, which provided valuable information on rental properties in Poland. After extracting the data, it was formatted and cleaned to prepare it for further analysis. The variables recorded were City, District, rental price, and property size.

## Data Analysis
1. Descriptive Analysis
    * Histograms were created to visualize the distribution of property sizes and rental prices.
    * Boxplots were used to compare the rental prices across different cities, providing insights into regional variations.
    * Scatterplots were generated to explore the relationship between rental prices and property sizes, both overall and by specific cities.
2. Summary Statistics
    * A table was compiled to present the average rental prices, property sizes, and property counts for each city.
3. Linear Regression
    * A Linear Regression model was applied to predict rental prices based on property size and city. This allowed for a deeper understanding of how these variables influence the rental rates.

## Tools and Packages
    * **tidyverse**: For data manipulation and visualization, including creating histograms, scatterplots, and boxplots. Also used for web scraping.
    * **caret**: Used for data splitting and training the linear regression model.
    * **rmarkdown**: To render an HTML report, enabling easy sharing and publishing of the findings on GitHub Pages.

## Conclusion
My project successfully explored the housing market in Poland, providing valuable insights into the rental prices, property sizes, and their variations across different cities and districts. The linear regression model shed light on the relationship between rent, property size, and location, allowing for more informed decision-making in the housing market.

For a detailed analysis and visualizations, please refer to the full HTML report available [here](https://dabowski.github.io/housing_analysis).
