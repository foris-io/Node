# Node

This repository will have the code running on the node of the new hardware setup. Node is an Arduino Due board with Dragino LoRa hat mounted on it. 
There are 4 sensors connected to this Arduino Due. 
1. Temperature
2. Humidity
3. Moisture 
4. Salinity

The optimal way of sending the data from Node to Master/Gateway is sending a string packed with all the sensor values. We also assume that every node has been shipped with a unique id associated with it. Using this id we identify the node. Node id is sent along with the string to the master/gateway.

For any suggestions or improvements please create an issue on Github. 
