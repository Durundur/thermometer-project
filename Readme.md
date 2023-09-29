The aim of this academic project was to build a thermometer, the following were used: 

* MSP430 
* MLX90614 - infrared thermometer 
* ESP32 
* REST API 
* React Application

MSP430 was the main component combining a thermometer and ESP. I2C and SMBus were used to communicate with these components. ESP was receiving. After receiving data from MSP, ESP connected to the WI-Fi network was sending the measurement to the REST API, which added it to the MongoDB database. The task of the react application was to display the history and lastest measurement

