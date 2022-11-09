Name of project

ESP32-CAM Face Recognition and Video Streaming with Arduino IDE

 Why are you doing this project?
 i chose this project because im trying to test differnt securty application 
 
  Links to Documentation
  https://www.youtube.com/watch?v=AB0SphP3apo
  
   Steps you followed, note where you had problems in red. 
   
   1. downlaod arduno ide version 1.8.19
   2.search for a file name to add the esp32 borad need for the camara 
   https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
   3.go tools click borad and choose the esp32 borad you are using 
   4.select the port your borad there should be only one borad attacted tothe port
   5.go down until you see partition scheme and select "default 4MB with spiffs(1.2MB APP/1.5 SPIFFS)"
   6. go to file and scroll down till you see examples and scroll down until you see esp32 then cam and then click camerawebserver.
   7. change ssid and password
   8.make sure their are no \\ with #define CAMERA_MODEL_AI_THINKER // Has PSRAM
   9.upload yourcode to your esp32 board it may take a moment based on your internet 
   10. hit ctrl,shift,m to open seairl port to get an ip adress of your carmera 
   11.open a web broswer and verify your camera works
   
   
