# SignalScanner
An ESP32-Compatible sketch that detects nearby wireless networks.\
(Circuit Diagram to be added at a later time)
- This is the software for an embedded system (integrated to a 0.96 inch OLED Screen) that monitors the presence of wireless signals in the ~2.4 GHz band.
- v1.1 when compiled in the Arduino IDE consumes 88% of program storage space, which is mostly taken up by WiFi and BLE libraries, leaving sufficient room for additional, (and relatively) smaller features.
- As of v1.1, the system is only able to detect WiFi signals (both hidden and publicly displayed) as well as Bluetooth Devices advertising using BLE.
- Currently each scanning mode only shows up to 8 networks/devices, despite being able to detect many more. A future version will incorporate a page-selection feature to show *all* nearby signals, not only the first 8.
- The goal of this project is to become familiar with specific wifi and bluetooth libraries, in order to apply such knowledge to later, more complex projects.
- No Generative AI was used in the creation of this project, and will not be used in this project or any other by myself.
