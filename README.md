# Supply-Chain-Optimization

### Summary

This notebook is dedicated to analysing sales data, leveraging a suite of Python libraries to facilitate data manipulation, visualisation, and clustering. The analysis includes the following steps:

1. **Library Imports and Environment Setup**:
    - Libraries such as `pandas`, `numpy`, `seaborn`, `matplotlib`, `os`, `folium`, `sklearn`, and `plotly` are imported to handle various data processing, visualization, and clustering tasks.

2. **Data File Paths Definition**:
    - File paths for different datasets are defined, including orders, customers, geolocation, order items, payments, reviews, products, sellers, and product category translations.

3. **Data Loading**:
    - The datasets are read into pandas DataFrames for subsequent analysis.

4. **Initial Data Exploration**:
    - Although not explicitly shown in the first few cells, it's common practice to perform initial data exploration, such as examining DataFrame structures and performing basic statistical analysis.

5. **Geospatial Analysis**:
    - The presence of the `folium` library suggests that geospatial analysis and mapping of customer or sales data might be conducted.

6. **Clustering Analysis**:
    - Utilization of the `KMeans` algorithm from `sklearn` indicates clustering of data points, possibly to segment customers or sales regions.

7. **Advanced Visualization**:
    - Libraries like `plotly` and `seaborn` are included for creating interactive and detailed visualizations to uncover insights from the data.
