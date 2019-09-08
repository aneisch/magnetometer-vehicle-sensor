# Magnetometer Vehicle Sensor

D1 Mini Pro based vehicle detection sensor utilizing QMC5883L magnetometer. Features vehicle detection using megnetometer, gate staus with reed switch, battery voltage detection with voltage divider, and relay for gate actuation. 

Compile using ESPHome from https://github.com/esphome/esphome/pull/671 for QMC5883L support.

# Hardware
[D1 Mini Pro](https://www.banggood.com/Geekcreit-D1-Mini-Pro-16-Module-ESP8266-Series-WiFi-Wireless-Antenna-p-1144951.html): $4  
[D1 Mini Dual Base](https://www.aliexpress.com/item/32642733925.html): $1.00  
[D1 Mini Relay Shield](https://www.aliexpress.com/item/32596395175.html): $1.20  
[D1 Mini DC Power Shield](https://www.aliexpress.com/item/32790327733.html): $1.40  
[D1 Mini Proto Board](https://www.aliexpress.com/item/32627711647.html): $0.30  
[QMC5883L Triple Axis Compass Magnetometer](https://smile.amazon.com/gp/product/B008V9S64E): $6.59  
[Sonoff IP66 Junction Box](https://www.banggood.com/SONOFF-IP66-Waterproof-Junction-Box-Waterproof-Case-Water-resistant-Shell-p-1223669.html): $6.99  
[Voltage Divider](https://smile.amazon.com/gp/product/B06XHKZCD4) (to measure up to 25v): $1.38  
Miscellaneous cables: $0

# Wiring
QMC5883L: 3v or 5v, GND, D1 (SCL) D2 (SDA)
Reed Switch: GND, D7
Relay: D8 (you can modify the pin # on V2, or physically cut D1 pin and add bodge wire)


![Stack from the front](images/front.jpg)

![Stack from the back](images/back.jpg)
