# RFID Data Analysis and Predictive Modeling

This project focuses on improving the efficiency and accuracy of a logistics company's RFID-based inventory and order tracking system through data analysis and predictive modeling. 
RFID (Radio Frequency Identification) technology has become widely utilized in the field of logistics, offering numerous advantages such as precise inventory management and error reduction in billing. 
However, challenges can arise during the deployment of this technology, which is where this project comes into play.

## Project Overview

- **Data Collection**: RFID data, including timestamp, RFID tag information, signal strength (RSSI), and antenna location, is collected from the logistics system.

- **Data Integration**: RFID data is integrated with barcode information to accurately identify and track items within each shipping carton.

- **Anomaly Detection**: Machine learning algorithms are employed to detect anomalies or discrepancies in the RFID data, such as items placed in the wrong cartons or missing items.

- **Predictive Analytics**: Predictive models are implemented to forecast potential issues in the order fulfillment process, allowing for proactive intervention.

## Project Components

1. **Data Preprocessing**: Clean and preprocess the RFID data to address data overlap and discrepancies from adjacent conveyor zones.

2. **Data Integration**: Combine RFID data with barcode information for accurate item tracking.

3. **Anomaly Detection**: Develop machine learning models to identify and flag anomalies in the RFID data.

4. **Predictive Modeling**: Implement predictive models to anticipate and prevent potential logistics issues.

## Project Structure

- `data_anonymous/`: Contains the anonymized data files used in the project.

- `notebooks/`: Includes Jupyter notebooks for various project phases, including data preprocessing, anomaly detection, and predictive modeling.
