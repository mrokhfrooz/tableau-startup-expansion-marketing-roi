# tableau-startup-expansion-marketing-roi
An interactive Tableau project analyzing startup expansion strategy through Marketing ROI (ROMI), revenue trends, and K-means clustering. The dashboard identifies high-potential cities for investment by evaluating marketing efficiency, revenue performance, and population data to support data-driven expansion decisions.


## Dataset

The dataset used in this project is attached to this repository and consists of two files:

- Startup Expansion Dataset (P1-StartupExpansion.xlsx)
- Contains marketing and revenue data for multiple U.S. cities.

US Cities Population Dataset (P1-US-Cities-Population.csv) – Contains population data used to enrich and refine the analysis through cross-database joins.

Startup Expansion Dataset – Key Columns

City – Name of the city

State / Region – Geographic classification of the city

Marketing Spend – Amount invested in marketing

Revenue – Revenue generated from marketing efforts

ROMI (Revenue / Marketing Spend) – Calculated return on marketing investment

Population Dataset – Key Columns

City – Name of the city

Population – Total population of the city

The population data is joined with the marketing dataset to enhance clustering, trend analysis, and investment decision-making.

## Questions
1) Identify which of the two sales regions is performing better (i.e., outperforms the other in 2 of the following 3 metrics):

Average Revenue per City

Average Marketing Spend per City (less is better)

Average ROMI (Return on Marketing Investment) per City
(Revenue / Marketing Spend)

2) Identify which of the 10 new locations has the best potential for the company to invest more funds into marketing.

## Resuts

Region 1 has better returns on marketing spend compared to Region 2.
![Screenshot1-Visualization using Map](https://github.com/user-attachments/assets/11bbcd36-9035-4cc2-8fc2-b6aa320ac6e4)

Red Trendline: With every dollar spent on marketing, the company generates revenue of $0.94. Consequently, in this cluster or group of cities, the company is operating at a loss.
Orange Trendline: With every dollar spent on marketing, the company generates revenue of $7.32. Consequently, in this cluster or group of cities, the company is profitable.
Blue Trendline: With every dollar spent on marketing, the company generates revenue of $3.17. Consequently, in this cluster or group of cities, the company is profitable.
![Screenshot3-trend-lines and-clustering-with-k-means](https://github.com/user-attachments/assets/92565b7f-223a-4647-884f-ca21e455cdd3)

## Conclusion
Recommend that WeWashUSleep increase its marketing efforts in three new orange cities in: California, Illinois, and New Jersey.
