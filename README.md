Flashing TUYA CB3S BK72XX - 4channel switch Home Assistant ESPHome. 
In this video you can se how to connect,  backup and flash ESPHome  - BK72XX CB3S board.
This requires some soldering skills, but the rest is simple.
1. Desolder the board from the device
2. Solder the wires to the board according to the diagram.
3. Create new device on ESPHome
4. Fill WIFI SSID and PASSWORD
5. Download project UF2 file type
6. Use BK7231GUIFlashTool to create backup link - https://github.com/openshwprojects/BK7231GUIFlashTool
7. Short the CAN (RST) pin to ground to establish the connection.
8. Use ltchiptool to flash board link - https://github.com/libretiny-eu/ltchiptool/releases
9. Short the CAN (RST) pin to ground to establish the connection.
10. FINISH, you can solder back your board. 
