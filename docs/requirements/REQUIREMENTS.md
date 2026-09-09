## Suitable Technologies, Tools and Frameworks

* **ESP32:** Collects water-quality sensor data.
* **Sensors:** pH, Turbidity, TDS/EC and Temperature.
* **Wi-Fi/MQTT:** Sends sensor data to the cloud.
* **Firebase:** Stores real-time and historical data.
* **Python:** Used for data processing and ML.
* **Pandas & NumPy:** Data cleaning and preprocessing.
* **SciPy:** Correlation and regression analysis.
* **Scikit-learn:** Machine learning model development.
* **Random Forest & XGBoost:** Water-quality prediction/classification.
* **SHAP:** Explains ML predictions.
* **Streamlit:** Creates the monitoring dashboard.
* **Firebase Notifications:** Sends alerts when water quality becomes unsafe.

### Flow

**Sensors → ESP32 → Firebase → Data Preprocessing → Statistical Analysis → ML Models → Prediction → Dashboard + Alerts**