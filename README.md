🛡️ Anomaly Detection

A collection of machine learning-based anomaly detection projects built for a real-world SOC environment, using WAF logs. 
Each project targets a different detection angle, using a different modeling approach.

Projects

#   Project                      Method                        Detection Target
01  Traffic Anomaly Detection    Isolation Forest              Hourly traffic spikes per site
02  Operation Anomaly Detection  STL DecompositionBehavioral   anomalies per operation
03  Operation Anomaly Detection  Facebook Prophet              Forecast-based operation anomalies


Stack

Language: Python
Core Libraries: pandas, numpy, scikit-learn, statsmodels, prophet, matplotlib, seaborn
Log Source: WAF logs



Author

Abdalhadi — SOC Analyst

GitHub
