# BlueFly-Shield
The BlueFly-Shield is a plug-on module with WiFi/WLAN for Arduino based on an Atmel/Microchip WINC1500 WiFi Network Controller SoC.

![BlueFly-Shield](https://github.com/watterott/BlueFly-Shield/raw/master/hardware/BlueFly-Shield_v10.jpg)

* Compatible with [Arduino WiFi-Shield-101](https://www.arduino.cc/en/Main/ArduinoWiFiShield101)
* [Microchip ATWINC1500B](http://www.microchip.com/wwwproducts/en/ATWINC1500) WiFi Network Controller SoC
* [Microchip ATECC508A](http://www.microchip.com/wwwproducts/en/ATECC508A) Crypto Authentication (I2C address 0x60)
* Network standard: IEEE 802.11b/g/n 2.4GHz
* Wireless security: WEP, WPA, WPA2
* Security protocols: TLS, SSL
* Wi-Fi Direct and Soft-AP (Access-Point mode)
* Integrated WiFi and IPv4 stack (TCP, UDP, ARP, DHCP, HTTP, DNS)
* 3.3V - 5V tolerant IOs


## Shop
* [BlueFly-Shield (PCB antenna)](http://www.watterott.com/en/BlueFly-Shield)
* [BlueFly-Shield (uFL connector)](http://www.watterott.com/en/BlueFly-Shield-uFL)


## Hardware and Software
* [Schematics + Layout](https://github.com/watterott/BlueFly-Shield/tree/master/hardware)
* ATWINC1500 WiFi: [Arduino Library and Examples](https://github.com/arduino-libraries/WiFi101), [Firmware Update](https://www.arduino.cc/en/Tutorial/FirmwareUpdater) (WINC1500 Model B)
* ATECC508A Crypto: [Arduino Library and Examples](https://github.com/thiseldo/cryptoauth-arduino)
* [Arduino MQTT Library](https://github.com/knolleary/pubsubclient)
* Arduino IDE Example Sketches: ```File->Examples->WiFi101```
