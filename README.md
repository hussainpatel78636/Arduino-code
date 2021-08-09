# Arduino-code
This file connects the WiFi module 8266 to the available WiFi network.
It then connects to the Thingspeak.api where the data is written.
Inside the loop the pulse sensor detects the user's heart beat.
Based on the detected heart beat the Arduino calculates the Beats Per Minute.
This BPM information is then sent to the thingspeak.api webpage where it is plotten on a graph.
