
# Citibike Network Analysis

## Introduction
This project analyzes Citibike trip data from September 2018 to understand the network characteristics. The analysis includes various visualizations and metrics such as the busiest stations, longest trips, most trips between stations, the most central station, and the bottleneck node. The analysis is segmented by all riders, male riders, and female riders.

## Installation

### Prerequisites
To run this project, you need to have Python installed along with the following packages:
- `pandas`
- `numpy`
- `matplotlib`
- `networkx`
- `folium`
- `jupyter`

You can install these packages using `pip`:

```sh
pip install pandas numpy matplotlib networkx folium jupyter
```

### Getting Started
1. **Clone the repository:**
   ```sh
   git clone https://github.com/bilalkamal/citibike-network-analysis.git 
   cd citibike-network-analysis
   ```

2. **Run Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```

3. **Open and Run the Notebook:**
   - Open the `citibike_network_analysis.ipynb` notebook in the Jupyter interface.
   - Run the cells sequentially to perform the data analysis and generate the insights.

## Data
The project uses Citibike trip data for September 2018. Ensure you have the data file named `201801-citibike-tripdata.csv` in the project directory.

## Visualizations and Insights
The notebook generates various visualizations to provide insights into the Citibike network, including:
- Network graphs showing the connectivity between stations.
- Degree distribution histograms.
- Trip duration distribution histograms.
- Bar charts for the most active stations.
- Maps displaying the locations of Citibike stations.

### Key Metrics
- **Busiest Stations:** Identify the stations with the highest number of trips.
- **Longest Trips:** Determine the trips with the longest average duration.
- **Most Trips Between Stations:** Find the pairs of stations with the highest number of trips.
- **Most Central Station:** Identify the most central station based on closeness centrality.
- **Bottleneck Node:** Identify the bottleneck node based on betweenness centrality.

## Conclusion
The analysis highlights Pershing Square North as a critical hub in the Citibike network for all rider demographics. While there are some anomalies in trip duration data, the overall network shows a healthy distribution of trip durations and station connectivity. Further investigation into data anomalies and a deeper dive into geographical patterns could provide additional insights.

