# ESPHome-SHTC3-Sensor

This project features a low-cost DIY temperature and humidity sensor for usage in conjunction with Home Assistant.

## Features
* ESPHome native integration with Home Assistant
* Humidity reporting
* Temperature reporting
* Battery monitoring
* USB-C charging via the XIAO onboard charger
* Low-power configuration with deep sleep for battery usage

## Hardware
* Seeed Studio XIAO ESP32-C6
* SHTC3 on an adafruit breakout board
* 1S Li-ion battery pack

### Pin mapping
```
| Sensor | XIAO        |
| ------ | ----------- |
| VCC    | 3V3         |
| GND    | GND         |
| SDA    | GPIO22 (D4) |
| SCL    | GPIO23 (D5) |

| Battery | XIAO |
| ------- | ---- |
| +       | BAT  |
| –       | GND  |
| + 1M R  | A0   |
| - 1M R  | A0   |
```
![Front.jpg](Pictures%2FFront.jpg)
![Back.jpg](Pictures%2FBack.jpg)
## License
This project is licensed under the MIT License. See the LICENSE file for details.