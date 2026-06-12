🛡️ **Anomaly Detection**

A collection of machine learning-based anomaly detection projects built for a real-world SOC environment, using WAF logs. 
Each project targets a different detection angle, using a different modeling approach.



**Projects**


| # | Project | Method | Detection Target |
|---|---------|--------|-----------------|
| 01 | [Traffic Anomaly Detection](./01_traffic_anomaly_isolation_forest.md) | Isolation Forest | Hourly traffic spikes per site |
| 02 | [Operation Anomaly Detection](./02_operation_anomaly_stl.md) | STL Decomposition | Behavioral anomalies per operation |
| 03 | [Operation Anomaly Detection](./03_operation_anomaly_prophet.md) | Facebook Prophet | Forecast-based operation anomalies |



**Stack**

Language: Python
Core Libraries: pandas, numpy, scikit-learn, statsmodels, prophet, matplotlib, seaborn
Log Source: WAF logs



**Author**

Abdalhadi — SOC Analyst

GitHub
