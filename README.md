Room Temperature and Humidity Monitoring

This repository offers a straightforward system for tracking and visualizing room temperature and humidity data using a DHT22 sensor. The collected data is presented in a graph for easy analysis.
Setup

    Hardware: Connect the DHT22 sensor to a microcontroller (e.g., Arduino, Raspberry Pi).

    Software: Install necessary libraries for the sensor on your microcontroller.

    Configuration: Adjust parameters in config.py such as data collection interval and sensor pin.

    Data Collection: Run the collection script on the microcontroller to store data in a CSV file.

    Data Visualization: Transfer the CSV file to a computer and use plot_data.ipynb to visualize the data as a graph.

Usage

    Power on the microcontroller to start data collection.

    Transfer and run the Jupyter Notebook (plot_data.ipynb) to see the temperature and humidity trends.

This project is under the MIT License. See LICENSE for details.
