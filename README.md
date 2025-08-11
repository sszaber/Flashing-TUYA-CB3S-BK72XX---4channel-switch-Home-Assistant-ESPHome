Flashing TUYA CB3S BK72XX - 4channel switch Home Assistant ESPHome. 
In this video you can se how to connect,  backup and flash ESPHome  - BK72XX CB3S board.
This requires some soldering skills, but the rest is simple.
link to video - https://www.youtube.com/watch?v=8wT5jUDrLpM
[![Watch the video](https://img.youtube.com/vi/8wT5jUDrLpM/maxresdefault.jpg)](https://youtu.be/8wT5jUDrLpM)

### [Watch this video on YouTube](https://youtu.be/8wT5jUDrLpM)

1. Desolder the board from the device
2. Solder the wires to the board according to the diagram. <img width="1737" height="739" alt="Image" src="https://github.com/user-attachments/assets/f7b3a4a4-0990-420b-81c0-17339b1830a8" />
3. Create new device on ESPHome
4. Fill WIFI SSID and PASSWORD
5. Download project UF2 file type
6. Use BK7231GUIFlashTool to create backup link - https://github.com/openshwprojects/BK7231GUIFlashTool
7. Short the CAN (RST) pin to ground to establish the connection.
8. Use ltchiptool to flash board link - https://github.com/libretiny-eu/ltchiptool/releases
9. Short the CAN (RST) pin to ground to establish the connection.
10. FINISH, you can solder back your board. 
