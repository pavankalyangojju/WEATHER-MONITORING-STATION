# WEATHER-MONITORING-STATION

## OVERVIEW :-
To maintain the humidity & temperature levels in the hospitals house and
factories , in ordered to prevent any disasters.
## PROBLEMS :-
For the working people in factories , and patients in hospital , maintaining
the humidity and temperature is much essential , increase in temperature in the
factories like ceramic rolls, metal products , and glass industry, where the
temperatures are very high and humidity is low , if humidity goes below it will
affect the human body ,so monitoring the temperature and humidity levels are
important In hospitals for wellbeing of patients who are in bed cannot walk
## Solutions :-
In order to solve this problem came up with an idea of WEATHER
MONITORING STATION, It will help to monitor the temperature and humidity
levels with the help of raspberry pi, Temperature sensor , LCD , and Pressure
sensor, Sensors send the data to Raspberry pi which process the data and
display in LCD and also data will be backed up in cloud server, (Thing speak
server) any fluctuation in temperature will be shown on LCD in graph
representation that will alert users

## Components:-
### RasbperrPi 3+
![RasbperryPi3B+](https://user-images.githubusercontent.com/95854682/185202010-57ecfa96-362c-406e-aada-b845b6d3de4e.jpg)
### DHT11 Humidity & temperature sensor
![T H](https://user-images.githubusercontent.com/95854682/185202630-29afa255-1ee7-46da-8ca4-c32a8796b5f9.jpg)
### BM180 Pressure sensor
![P](https://user-images.githubusercontent.com/95854682/185203766-4d257910-5764-4e9d-9383-c8bda0b818fc.jpg)
###  LCD Display
![LCD](https://user-images.githubusercontent.com/95854682/185204211-b02d9917-7686-4e6c-ae54-00bca2b16a91.jpg)


## Images of the Project
### Circuit
![cricute2](https://user-images.githubusercontent.com/95854682/185200419-ee4d1f14-da13-49a2-8052-cd6cb5e22879.png)
![circuit](https://user-images.githubusercontent.com/95854682/185200469-c0609731-827e-40f5-bded-7ab1db5a9ca0.jpg)

### Block Diagram
![Block daigram](https://user-images.githubusercontent.com/95854682/185201005-44b51ebc-1635-486c-8e4d-66b74d65f78a.jpg)

### Sensors
![sensors](https://user-images.githubusercontent.com/95854682/185201081-172ec90e-2263-4437-88e7-c089ee6ce11a.jpg)

### Monitoring Humidity, Temperature and Pressure Graph
![Graph](https://user-images.githubusercontent.com/95854682/185201480-48fde762-19f8-4f58-afd2-a4c9ef30cf3e.png)

#### Install Adafruit Python DHT Sensor Library files to run this project on Raspberry Pi commands
-->  sudo apt-get install git-core <br>
-->  sudo apt-get update <br>
--> git clone https://github.com/adafruit/Adafruit_Python_DHT.git <br>
--> cd Adafruit_Python_DHT <br>
--> sudo apt-get install build-essential python-dev <br>
--> sudo python setup.py install
#### enable Raspberry Pi I2C by going into RPi Software Configuration command
-->  sudo raspi-config <br>
![configi2c](https://user-images.githubusercontent.com/95854682/185206758-6db1c935-0ae3-4cde-b24c-cd40054b1b52.gif)
![i2cmain](https://user-images.githubusercontent.com/95854682/185206774-238fc7b7-8ee0-487c-940a-ff7fd20c878d.png)

### Programming part

