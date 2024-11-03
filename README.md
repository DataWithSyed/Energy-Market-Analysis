## Energy Prices Analysis

### Overview
This repository contains a Jupyter Notebook that analyzes energy price data across various energy markets, such as the day-ahead and aFRR markets. The analysis aims to provide insights into market dynamics, trends, and price fluctuations, potentially informing decision-making for stakeholders in the energy sector.

### Contents
This repository includes:
- **Energy Price Data**:
  - `Dayahead_market_data.xlsx`: Day-ahead market prices and relevant statistics.
  - `aFRR_market_positive_data.xlsx`: Positive reserve data for the aFRR market.
  - `aFRR_market_negative_data.xlsx`: Negative reserve data for the aFRR market.

- **Energy_Prices.ipynb**: The main Jupyter Notebook that loads, cleans, and analyzes the data to extract key insights.
- **Summarizing_Report_Energy_Prices.docx**: A report summarizing findings and important insights from the data analysis.
- **Summarizing_Report_Energy_Prices.pdf**: PDF version of the summary report for easy reference and sharing.

### Data Analysis
The notebook covers several areas of analysis:
1. **Market Price Trends**: Exploration of price trends in the day-ahead market, with visualizations to show seasonal or daily variations. This section uses line plots, bar charts, and other visual tools to illustrate changes over time.

2. **aFRR Market Analysis**: Analysis of both positive and negative reserve data in the aFRR market, examining price behaviors under different market conditions. This may include comparisons between positive and negative reserves and an exploration of volatility within these markets.

3. **Statistical Summaries and Correlations**: Summary statistics to reveal key metrics (e.g., average price, volatility) and correlation analysis to identify relationships between different markets or factors influencing prices.

4. **Insights and Findings**: Key takeaways that highlight trends, unusual price movements, or correlations between different market types. This section aims to inform stakeholders about potential patterns and behaviors in the energy market.

### Requirements
To run the notebook, ensure you have the following dependencies installed:
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `scipy` (if advanced statistical analysis is used)

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/EnergyPrices.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook Energy_Prices.ipynb
   ```

### Contributing
Contributions are welcome! If you have suggestions for expanding the analysis or additional data sources, please open an issue or submit a pull request.
