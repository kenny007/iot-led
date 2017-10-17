# IOT LED Example for WEMOS

This example is prepared for Introduction to Computers and Informatics class of TTU CyberSec Eng.

Details: https://wiki.itcollege.ee/index.php/Category:I600_Introduction_to_Computers_and_Informatics#Assignment:_Set_up_basic_IoT_scenario

## Requirements
* Python 3.x

## Running

First clone the repository to your computer via Git. Following commands are for Linux and Mac.
```sh
git clone https://github.com/yasinaydin/iot-led.git
cd iot-led
```

### On your machine

Run `main.py` like
```sh
python main.py
```
then browse to http://localhost:8080/

### On WEMOS

Run following command:

```sh
sudo ampy -p /dev/ttyUSB0 put main.py 
```
