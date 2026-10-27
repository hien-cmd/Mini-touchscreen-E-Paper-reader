# Mini Touchscreen E-paper reader
## A mini reader built for the Waveshare ESP32-S3 1.54" E-ink touchscreen board.

##Hardware requirements
-ESP32-S3 1.54inch e-Paper AIoT Development Board
-SD card

##Software requirements
-Arduino IDE installed
-"GxEPD-2" library (by Jean-Marc Zingg) and Adafruit GFX library (by Adafruit) installed in Arduino IDE

##Set-up guide
1. Paste the code into Arduino IDE
2. Plug in your Waveshare board and select the device as "ESP32S3 Dev Module"
3. Flash the board
4. Get the SD card and put the plaintext of any book you want to read into its directory
5. Put the card inside the SD card slot of the board
6. Turn the board on again and your books should be there

##User guide
-To select a book, click on it's file name
-Swipe up/down to scroll
-Tap on the screen to go back to the main menu
-You don't need to turn it off, it will automatically sleep if inactive
