# Smart-Lighting-Remote-Access
Using IoT

STEP 1: Download and Install Arduino IDE for coding.
LINK: https://www.arduino.cc/en/software OR download from Microsoft Store.

STEP 2:We have used Arduino IDE for human detection. And Arduino IoT cloud for Remote Access.

WORKING  OF THE MODEL:

1)The Automatic Room Lights using ESP-32 and IR Sensors is a project, where the lights in the room will automatically turn ON upon presence of a human and stay turned ON until the person has left.

2)It is placed near the entrance and is used to count the number of people in the room using 2 IR sensors.

3)There are two IR sensors which is used to detect weather the person is entering the room or leaving the room using which we count the number of people present in the room and control the lights accordingly.  

4)First IR sensor is used to detect the entrance of the person and the second sensor detects the leaving of the person.

5)While entering the person crosses the first IR sensor which makes the people in the room count increase by 1 and the lights are turned ON and if another person enters the count is further increased.

6)While a person leaving the room crosses the second IR sensor which decreases the room person count by 1. Similarly if all the people leaves the room the lights are turned OFF as the people count is zero.

7)The Arduino IOT cloud platform is used to monitor and control the smart lights remotely from anywhere using Dashboards.

Further read the "SMART LIGHT" document for referral.
