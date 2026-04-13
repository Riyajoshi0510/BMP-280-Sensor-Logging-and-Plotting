# BMP-280-Sensor-Logging-and-Plotting
Integrated BMP280 barometric sensors with STM32 MCU via interrupt-driven SPI firmware

This project implements SPI-based communication between an STM32 microcontroller and the BMP280 sensor to read raw temperature data.

The system initializes the BMP280 sensor, verifies its identity, configures it for measurement, and continuously reads uncompensated temperature values at regular intervals.
