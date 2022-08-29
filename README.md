# Arctic-Challenge-Hackathon

## Noise Level Monitoring application for classrooms

A Hackathon focusing on Blockchain, 5G, Lora WAN, IoT Platform, Edge Computing, Information security and more held in Skelleftea, Sweden.  Worked on a sound challenge where the noise level in the room is identified. A webpage is designed to show the noise level of the room specifically in a classroom. In this project, different noise levels are analyzed. 

* Hardware used:
  1. Arduino UNO 
  2. Sound Sensor
  3. Wifi Module
  4. Electrical Wires 
  
 * Software used:
   1. Arduino IDE
   2. Flask
   3. SSiO IoT platform
     
   
   
### Working

This application includes the whole architecture implementation.
There is a sensor installed on Arduino board. It measures the noise level and sends to the proxy(web) server.
The proxy server analyzes the data, checks for anomalies and sends it to SSiO IoT platform to store.

When a user wants to monitor the noise level in the room, he accesses the web server.
The web page includes all the realtime and historical data of noise levels.
The web page also informs the user if the noise level reaches a specified threshold.




