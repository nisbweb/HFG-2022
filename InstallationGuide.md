Install Arduino IDE from https://www.arduino.cc/en/software
To install the ESP32 board in your Arduino IDE, follow these next instructions:
In your Arduino IDE, go to File> Preferences
Enter https://dl.espressif.com/dl/package_esp32_index.json into the “Additional Board Manager URLs” field. Then, click the “OK” button:
Open the Boards Manager. Go to Tools > Board > Boards Manager…
Search for ESP32 and press install button for the “ESP32 by Espressif Systems“:
Set board to ESP32 Dev Module

This should do fine, if this is not working follow the below steps

Download necessary files from https://github.com/espressif/arduino-esp32 that is Click the “Clone or download” button in the center right of the screen and select “Download ZIP”.
Save these folders and files to the location where Arduino is installed e.g.) C:\Program Files (x86)\Arduino\hardware\espressif\esp32\
Next, start tools/get.exe from among the saved files and download the necessary files that is Click to start get.exe. Then, the command prompt screen appears, starting to download the necessary files.
Set board to ESP32 Dev Module