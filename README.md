# Grafana Dashboards for ntopng Data

This repository contains Grafana dashboards designed to visualize ntopng data. The dashboards serve two main purposes: comparing historical data and alerting, as well as displaying the current state of the network.

## Dashboards

### 1. Historical Data Dashboard

The historical data dashboard is designed to provide a comprehensive view of the network's historical data. It includes various metrics and visualizations that help analyze past network performance and trends. This dashboard is particularly useful for comparing historical data and identifying any anomalies or patterns.

![2023-05-21 21_03_05-Presentatie project demo pptx - PowerPoint](https://github.com/birgerjanssens/ntop-grafana-dashboards/assets/91627590/bea03b31-ba41-4d4d-a6fa-1c6d113d9290)


### 2. Live Data Dashboard

The live data dashboard focuses on displaying real-time information about the network's current state. It provides up-to-date metrics and visualizations that enable monitoring network activity as it happens. This dashboard is particularly helpful for gaining insights into the current network status, identifying bottlenecks, and assessing overall performance.

![2023-05-21 21_04_09-Network DMS Brugge _ Live - Dashboards - Grafana – Mozilla Firefox](https://github.com/birgerjanssens/ntop-grafana-dashboards/assets/91627590/168c5110-7bc2-4a5f-b0dc-42683a8dfb0a)

## Getting Started

To use these Grafana dashboards with your ntopng data, follow these steps:

1. **Prerequisites**: Ensure you have Grafana and ntop installed

2. **Export flows to InfluxDB**: Setup ntop to use InfluxDB as timeseries drive [Documentation](https://www.ntop.org/ntop/ntopng-influxdb-and-grafana-a-step-by-step-guide-to-create-dashboards/)

3. **Import the dashboards**: Open Grafana in your web browser and navigate to the dashboard section. Click on "Import" and select the JSON file corresponding to the desired dashboard (historical or live data). Customize the settings as per your requirements and save the dashboard.

4. **Configure data source**: Configure ntopng (InfluxDB) as a data source in Grafana. Provide the necessary connection details, such as the URL, port, and authentication credentials.

5. **View and analyze data**: Once the dashboards are imported and the data source is configured, you can start viewing and analyzing your ntopng data. Use the historical data dashboard for comparing historical data and generating alerts. Utilize the live data dashboard to monitor the network's current state and track real-time metrics.

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the dashboards according to the terms specified in the license.

## Acknowledgements

The creation of these Grafana dashboards was made for an educational project (Howest - University of applied science | Associate Degree system and network management). I would like to acknowledge the contributions and efforts of Grafana and ntopng communities, whose tools and resources have made this project possible.
