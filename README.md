# Project1
Project designing and building a hub board for our monitoring service. 


This project is the combined effort of several members of our team. 
We have run into several issues with the designs of this board in our application. 
The software we are running is proprietary and so I cannot get too detailed here, however I can say that we are using this board to monitor bluetooth signals and send the information back to our surver for analysis and action. 
The boards are powered by a 10000mAh li-po batter which is charged by an 18w solar pannel. 

The designs are in the repo, and we are open to suggestions and help. 


For the 'hubs' we need two major things:
1 - BLE (Bluetooth Low Energy) or Bluetooth 5.0
2 - LTE or another cellular connection to report the Bluetooth data to our server

For the Bluetooth we are currently using an nRF-52840 chip/microcontroller. For the LTE connections we are using the nRF-9160 chip which is M1/NB-IoT compatible. 

Additionally we are building in a solar charge controller, as this project will run on solar power and li-po batteries. 
No integrated BMS is necessary as the batteries we are using have thier own. 

Problems: Plug J-Tag into the programming board (nRF9160 Dev Kit) and it would fry it. The programming board would be totally ruined. The connection chip got extremely hot. We dont understand why or what is happening. We need the communities help here. 


Our designs are currently in the process of being open sourced and will be available to anyone who wishes to use them. We are using a https://solderpad.org/licenses/ license. 


If anyone has any ideas of already existing boards out there that can do exactly what we want, please let me know. 
You can reach me at shawn@lightningkite.com or text me at 801---854---0069
