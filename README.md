# Holyoke Codes Weather Station
A Wunderground Personal Weather Station based on SparkFun Photon Weather Shield. This project measures temperature, barometric pressure, humidity, wind speed and direction, and rainfall. Weather data is uploaded to Wunderground as a Personal Weather Station.

Current weather conditions at Holyoke Codes are [here](https://www.wunderground.com/personal-weather-station/dashboard?ID=KMAHOLYO17).

This weather station is built with the [SparkFun Photon Weather Shield](https://www.sparkfun.com/products/13674). The shield includes the Si7021 temperature/humidity and MPL3115A2 barometric pressure sensors. Each shield comes with two RJ11 connectors (for optional hookup of [rain and wind sensors](https://www.sparkfun.com/products/8942)) and a 3-pin soil temperature and moisture hookup.

The [Photon Guide](https://docs.particle.io/guide/getting-started/intro/photon/) is very useful to get started developing with the Photon board.
Make sure to include the SparkFun_Photon_Weather_Shield_Library and OneWire libraries in your project.

This weather station code is based on the SparkFun Photo Weather Shield examples:
https://github.com/sparkfun/Photon_Weather_Shield/tree/master/Firmware/SparkFun_Photon_Weather_Wunderground
https://github.com/sparkfun/Photon_Weather_Shield/tree/master/Firmware/SparkFun_Photon_Weather_Basic_Soil_Meters
