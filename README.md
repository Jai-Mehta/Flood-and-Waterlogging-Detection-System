# Water-logging Prediction and Flood Detection System

## Overview

The Water-logging Prediction and Flood Detection System is a comprehensive solution designed to address the pressing issue of urban flooding by providing real-time monitoring and predictive insights. Leveraging IoT sensors, AWS cloud services, and a Flutter-based mobile application, this system offers a proactive approach to mitigating flood risks.

## Features

- **Real-time Data Transmission**: Utilizes AWS Lambda functions to facilitate seamless communication between Raspberry Pi sensors and AWS DynamoDB, ensuring timely and accurate data collection.
  
- **Predictive Insights**: Employs advanced algorithms to analyze sensor data and predict potential flood occurrences, enabling proactive measures to be taken.
  
- **Interactive Visualization**: The Flutter-based mobile application offers an intuitive interface for visualizing sensor data on a dynamic map, providing users with actionable insights and real-time updates.

## Installation

1. **Clone the Repository**: `git clone https://github.com/yourusername/water-logging-prediction.git`
   
2. **Set Up AWS Services**: Follow the instructions to configure AWS Lambda functions and DynamoDB tables.
   
3. **Deploy Raspberry Pi Code**: Upload the code in `raspberry-pi-code` to your Raspberry Pi devices to start collecting sensor data.

## Usage

1. **Start Data Collection**: Ensure that the Raspberry Pi devices are powered on and connected to the internet to begin transmitting sensor data to AWS DynamoDB.
   
2. **Launch Mobile Application**: Open the Flutter mobile application on your device to view real-time sensor data and flood predictions on the map interface.
   
3. **Stay Informed**: Monitor the status of sensor locations on the map and receive alerts or predictions for potential flood events.

## Contributors

- Jai Mehta
- Vighnesh Naik
- Pankti Nanavti
- Kunj Gala

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
