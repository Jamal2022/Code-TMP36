# Code-TMP36

## Using A TMP36 Temperature Sensor With Arduino
The TMP36 temperature sensor is an easy way to measure temperature using an Arduino! The sensor can measure a fairly wide range of temperature (-50°C to 125°C), is fairly precise (0.1°C resolution), and is very low cost, making it a popular choice. In this tutorial we will go over the basics of hooking the TMP36 up and writing some basic code to read the analog input it is connected to.

## The TMP36 Temperature Sensor
Since this sensor is very simple and does not require any supporting components we will be directly connecting the sensor to the Arduino. Start by bending the legs on the TMP36 sensor so they will fit into the breadboard.

## Powering The Sensor
This sensor has a fairly wide input voltage, meaning it isn’t terribly picky about the voltage required (anywhere between 2.7VDC and 5.5VDC). We will use the Arduino’s 5VDC power for this tutorial. Start by connecting a jumper wire from the Arduino’s 5VDC pin and running it to the sensor’s “pin 1”. Next, run another jumper wire from one of the Arduino’s ground pins to the sensor’s “pin 3”

## Connecting The Output
We are going to be using one of the Arduino’s analog input pins for this tutorial. Run a jumper wire from the sensor’s “pin 2” (the middle pin) to an analog input. We will be using analog input 0 in this tutorial.
