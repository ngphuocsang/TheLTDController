# The LTD Controller
The Low Temperature Dehydration Controller
  - Using 3 DHT11 sensors to measure the temperature and moisture of the storage room. 
  - LEDs simulates for the operations of heater, heatpump and three fans.
  - Timer is set to 10ms.
  - Heater and Fan2 are initially turned ON and Heatpump and Fan3 is off. They are switched to OFF/ON if the predetermined time runs out.
  - When temperature measured by the sensors in the room reaches the preset value, all of them are off.
  - Fan3 operates similarly fan1 or fan2 that is based on the values of humidity sensors.
