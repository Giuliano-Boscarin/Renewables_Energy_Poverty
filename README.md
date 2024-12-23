
# Assessing the Impact of Renewable Energy Expansion on Energy Poverty among EU Countries

This project explores how the growth of renewable energy impacts energy poverty in EU countries, focusing on equitable distribution among different income groups. The analysis includes trend studies, correlation analysis, and time-series forecasting.

### Methods
- **Trend Analysis**: Study renewable energy adoption and energy poverty trends across EU countries.
- **Correlation Analysis**: Investigate the relationship between renewable energy capacity, energy costs, GDP per capita, and energy poverty indicators.
- **Clustering**: Group countries based on similar renewable energy and energy poverty characteristics using K-Means.
- **Time-Series Forecasting**: Predict future trends using Prophet.
- **Statistical Analysis**: Use metrics like Pearson and Spearman correlations to assess relationships between variables.

### Data Sources
- **Renewable Energy**: Share of renewables in total energy consumption by country (e.g., solar, wind, hydro, biomass) from [Eurostat (sdg_07_40)](https://ec.europa.eu/eurostat).
- **Energy Poverty**:
  - Share of population unable to keep homes adequately warm by poverty status from [Eurostat (ilc_mdes01)](https://ec.europa.eu/eurostat).
  - Population in arrears on utility bills from [Eurostat (ilc_mdes07)](https://ec.europa.eu/eurostat).
- **Economic Data**: GDP per capita from [Eurostat](https://ec.europa.eu/eurostat).

### Techniques Used
- **Data Preprocessing**: Standardization and scaling of data for analysis.
- **Visualization**: Using Matplotlib and Seaborn for insights and patterns.
- **Machine Learning**: K-Means for clustering countries based on energy and poverty metrics.
- **Time-Series Analysis**: Using Prophet for forecasting future trends in renewable energy adoption and energy poverty.
- **Statistical Metrics**: Pearson and Spearman correlation coefficients for examining relationships.
