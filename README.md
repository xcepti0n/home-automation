# home-automation
All the scripts and steps that I plan to use for home automation

## Home Assistant

As most of open source community already uses, I am also using home assitant for the home automation.

More details here: https://www.home-assistant.io/


## Esphome
Esphome home provides a simple way to code esp32's without coding (funny way to say isn't it).

As their website says (as of now)
> " ESPHome is a system to control your microcontrollers by simple yet powerful configuration files and control them remotely through Home Automation systems. "

More details here: https://esphome.io/index.html

### esphome-multisensor
This contains yaml file on connecting multiple sensors like humidity and temperature, light sensor and also a OLED display.

I am currently using the same exact file in esphome in home assistant. (name, SSID and password changed)

Esphome can be used without without home assistant, home assistant just makes it easy to install and manage it, while allowing connecting it to homme assistant ecosystem. This way the sensors and their metrics are used as entities which can be used for automation, Like, turning on a fan automatically if room temperature is above 28 °C, its awesome, isn't it!

**Board used:** esp32-devkit (got it frpm amazon)
**Sensors used:**
1. DHT11 - humidity and temperature sensor
2. LDR sensor - Light sensor (to tell if its dark or light in room)

**Display:** OLED display Model SSD1306 128x64