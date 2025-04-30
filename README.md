Robotic Arm with 5 Degrees of Freedom: Gripper, Pivot, Wrist, Elbow, Shoulder, Base.<br />
- Designed and implemented a 5-degree-of-freedom Robotic Arm using ESP8266 microcontroller and 
MQTT protocol (Mosquitto Broker) for wireless communication.<br /> 
- Developed a responsive HTML interface with six sliders to control each joint and gripper in real-time.<br /><br />

Hardware Interface:<br />NodeMCU ESP8266, MG995 Servo(x3), SG90 Servo(x3).<br />
MG995 Servos(Elbow,Shoulder,Base) and SG90 Servos(Gripper,Pivot,Wrist) are 12V and 5V Rated Respectively.<br />
Follow the Servo Pin Configuration in the File "esp8266.ino" during the Robotic Arm Assembly.<br /><br />
Software Interface:<br />
Upload the File "esp8266.ino" in the ESP8266 using Arduino IDE.<br />
Run the File "web.html" using VSCode and control the Robotic Arm through the Webpage.

