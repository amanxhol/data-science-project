Project Title:
How Raw Material Costs Influence the Real Estate Market
Category:
Data Science / Economics
Problem Statement / Motivation:
Fluctuations in real estate prices are usually explained through factors like demand, interest rates, and population growth. However, the role of construction material costs remains less examined, even though materials such as steel, wood, and concrete represent a major share of construction expenses. This project aims to analyze whether increases in the cost of raw materials are followed by rises in housing prices, and if so, with what time delay.
Focusing on Switzerland and the United States—two countries with strong housing markets and publicly available data—the project will explore long-term economic patterns. Understanding this relationship could provide valuable insights for policymakers, investors, and construction firms when forecasting housing market trends or planning new developments.
Planned Approach and Technologies:
The project will follow a standard data science workflow. Data will be collected from trusted public sources, for exemple : FRED (Federal Reserve Economic Data), the Bureau of Labor Statistics (United States), the Swiss Federal Statistical Office (BFS) and the WorldBank. These datasets include the Producer Price Index for construction materials, national housing price indices and raw material prices.
After data collection, the main tasks will include cleaning and transforming the datasets, harmonizing different time frequencies, and calculating relevant indicators such as percentage changes and moving averages. Exploratory data analysis will then be used to visualize long-term trends and compare the evolution of material and housing prices. Statistical models, such as linear regression and correlation, will test whether material cost changes precede shifts in housing prices.
Technologies used will include Python with Pandas and NumPy for data manipulation, and Matplotlib or Seaborn for data visualization.
Expected Challenges and How to Address Them:
One main challenge is the difference in data frequency between countries. This will be addressed through normalization techniques. Another challenge is distinguishing correlation from causation and the fact that some other variables interfere with the causality (demand, inflation, …) ; the project will focus on detecting patterns rather than drawing definitive causal conclusions. 
Success Criteria:
The project will be considered successful if it produces a clean, well-documented dataset, generates clear and interpretable visualizations, and provides evidence of potential relationships between raw material and housing prices.
Stretch Goals:
If time allows, the analysis could include other economic variables such as mortgage rates, expand to additional countries, other commodities (gold, silver,…) or integrate a simple predictive model for housing price evolution. 
