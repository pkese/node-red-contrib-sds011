# node-red-contrib-sds011-sensor
This is a Node Red node to manage connection to the SDS011 sensor on a Raspberry Pi. It allows you to specify the variables that define the connections to the sensor.  This node is added to the Raspberry Pi section.

# Network server extension
Alternatively the sensor can be connected via network (TCP/IP). This is useful for running this node on [Android](https://nodered.org/docs/getting-started/android) in combination with one of the Bluetooth-to-TCP bridge apps. In this case you can specify the network server IP and PORT parameters as tcp://IP:PORT in the node parameter **port**, i.e.: `tcp://192.168.1.123:7777`
