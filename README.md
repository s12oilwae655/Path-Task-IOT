# Path-Task-IOT
Convert Speech to text 
https://speecttotext1.000webhostapp.com/
![image](https://user-images.githubusercontent.com/107873476/178418982-a107e8a5-e43c-4d2c-9061-5b5be647be02.png)


Writing the ESP32 algorithm
Setup ESP32:
1-Download Arduino ID , for we can write program code on ESP32
2. then plug in the ESP32 to the computer

3.  setup ESP32 with the IDE we need library , so we should go to File > click on preferences, then write “https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json” on Additional boards manger URLs
  Then we click OK.
  
4. then select the board 
From the list of tools > Board "Arduino Uno" > ESP32 Arduino > WEMOS D1 MINI ESP32 

5. we can check if the board is working
 choosing an example from file > Examples > ESP32
 
7. We know the port from the list of tools we choose the port and then click on COM6

8. We upload the code to the device
 
If port is not defined we follow the following steps "
إذا لم يتم تعريف المنفذ ، فإننا نتبع الخطوات التالية "

1. We write in Google Chrome the name of the piece
 CP2104USB Driver

2. We download
CP210x USB to UART Bridge VCP Drivers

3. Uncompress the entire folder and choose CP210x-Universal
windows driver Click on CP210x and right-click 
Extract to selected folder and click OK

4. From the list of downloads select
CP210x-Unviresal-Windows-Driver folder
 
5- We install the driver by copying the path ->This PC-Download CP210x unviresal windows driver

6. We go to the device manager and choose CP2104x USB to UART Bridge Controller, right-click and choose Update driver 

Then we choose Browse Computer Drives

7. Paste the path This PC-Download-CP210x unviresal windows driver and click Next

8. Return to the Arduino ID

9. From the Tools menu, click on Port and select COM6

10- We upload the code to the device

