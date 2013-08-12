Arduino Pilot Mega V2.5
=======================

Hello! This section holds several purposes. <br>
1.) Logs of interfacing the Raspberry Pi with the Arduino Pilot Mega V2.5 <br>
2.) Communication between Raspberry Pi and the Arduino Pilot Mega<br>
We aim to at least be able to receive data from the Arduino Pilot Mega at the end of the semester. <br>

As you should have noticed, there are three other files other than this readme file. The Arduino Code is for the APMv2.5. It bascially extacts data from its compass sensor and sends it to Serial 0 (USB). While on the other hand, the Raspberry Pi Code opens up the Serial port and receives the data from the Arduino. <br>

The third file, Thruster_SIM contains a code for the arduino that controls the output pins using Pulse Width Modulation (PWM). This is just a simulation to test out the thrusters.<br>

The fourth file, Yellow_Thrusters contains a code for the Raspberry Pi that uses the yellow detection computer vision module to send it's tracker location data via Serial communication to the APM.<br>

Arduino Code ----------> C <br>
Raspberry Pi Code -----> Python V2.7 <br>
Thruster_SIM ----------> C <br>
Yellow_Thrusters ------> Python V2.7<br>
