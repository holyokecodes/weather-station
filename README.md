# Holyoke Codes Weather Station
A Wunderground Personal Weather Station based on SparkFun Photon Weather Shield. This project measures temperature, barometric pressure, humidity, wind speed and direction, and rainfall. Weather data is uploaded to Wunderground as a Personal Weather Station.

Current weather conditions for this weather station are [here](https://www.wunderground.com/personal-weather-station/dashboard?ID=KMAHOLYO17).

## Hardware
This weather station is built with the [SparkFun Photon Weather Shield](https://www.sparkfun.com/products/13674). The shield includes the Si7021 temperature/humidity and MPL3115A2 barometric pressure sensors. Each shield comes with two RJ11 connectors (for optional hookup of [rain and wind sensors](https://www.sparkfun.com/products/8942)) and a 3-pin soil temperature and moisture hookup. 

The onboard temperature sensor was reading high by about 7-8 degrees F. I attached a DS18B20 Temperature Sensor Waterproof Digital Thermal Probe to the soil temperature connection. 

The Particle Photon is a Wifi-connected microcontroller with an STM32 ARM Cortex M3 microcontroller and a BCM43362 Wi-Fi chip. Particle provides Over-the-Air updates through a web-based development environment and a Dashboard to monitor the status of the device. The Photon board is similar to Arduino but has some differences, being specifically designed for developing internet-connected hardware.

## Software
The [Photon Guide](https://docs.particle.io/guide/getting-started/intro/photon/) is very useful to get started developing with the Photon board.

This weather station code is based on the SparkFun Photo Weather Shield examples:
https://github.com/sparkfun/Photon_Weather_Shield/tree/master/Firmware/SparkFun_Photon_Weather_Wunderground
https://github.com/sparkfun/Photon_Weather_Shield/tree/master/Firmware/SparkFun_Photon_Weather_Basic_Soil_Meters

Include the SparkFun_Photon_Weather_Shield_Library and OneWire libraries in your project.

Run the I2C Scanner to determine the device address for the DS18B20 temperature sensor.
