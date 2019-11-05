# Web Controlled RGB Ledstrip Using ESP8266 and BLYNK app
BLYNK is an phone app that makes it easy for user to make IoT projects using ESP8266/32, Arduino, Raspberry PI and many other boards. 

# Steps for starting using BLYNK.

1. First download the BLYNK app from [Appstore](https://apps.apple.com/us/app/blynk-iot-for-arduino-esp32/id808760481) or [Playstore](https://play.google.com/store/apps/details?id=cc.blynk&hl=no). 
2. Create a BLYNK acount or log in using Facebook. 
3. Create a project by giving it a name (here Github Demo) and choose a board type (in my case the ESP8266).
<img src="img/1_Create_project.jpg" width="150">   <img src="img/2_Empty_project.jpg" width="150">

*NOTE! The app will send you an autorisation key to your E-mail which the board must have to connect to that project, each board must have it own autorisation key. you can add more board in the cogwheel at the top of the screen.*

4. Press the plus icon at the top to open the Widget Box, select the zeRGBa to place it in the workspace.
<img src="img/3_Select_item.jpg" width="150">    <img src="img/4_Insert_zeRGBa.jpg" width="150">

*NOTE! each widget cost energy, you start with 2000 energy, and you can buy more if you need more.*

5. Hold you finger on the zeRGBa widget to enter move and resize mode. Place the widget where you want it and make it bigger for ease of use. 

<img src="img/5_Resize_item.jpg" width="150">   <img src="img/6_Full_size.jpg" width="150">

6. Enter widget setting by tapping on the widget, and change the pin inputs to the pins used for RGB PWM output on the ESP8266. (I use GPO15, GPO13, GPO12 for RED, GREEN, BLUE)

<img src="img/7_zeRGBa_settings.jpg" width="150">

7. Close the widget settings. And start the project by pressing the play button at the top

<img src="img/8_Start_project.jpg" width="150">


# Making the circuit board
I used Frizing to make the circuit.

<img src="img/Breadboard.png" width="500">

<img src="img/Scematic.png" width="500">
