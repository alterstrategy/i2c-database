# I2C Chip Address Database used in IoT modules and DIY electronics

This is a collection of universal hardware modules for IoT and other DIY electronics, which have built-in chips with I2C interface.

A separate row in the table is allocated for each such chip. This means that one module with several chips on board can take up more than one row in the table.
If you are the manufacturer or ambassador of such a module and it is not yet in our collection, please contact us and we will add your module to this table. 

## Data structure

| # | Module  | Type | Module Description | Chip | Address Mask(s) | Address Range(s) | Module Vendor Link | Module Project | 
| --- | ------------- | --- | ------------- | ------------- | ---------------------- | ------------- | ------------- | ------------- |
| 1 | I2CUI4_V1 | UI | User Interface 5-key I2C Keypad with RGB-LED and Buzzer | MCP230017  | 0100 A2 A1 A0 | 0x20 - 0x27 | site | project link |

- **\#** - row ID.

- **Module** - IoT module's unique part number.

- **Type** - IoT module designation type.

- **Module Description / Datasheet** - Module's name and Datasheet promoted by the vendor.

- **Chip** - Unique IC part name.

- **Address Mask(s)** - Possible mask or mask which can be used to address Slave IC on the I2C Bus by the Master.

- **Address Range(s)** - All possible HEX-values of addresses are available within the mask.

- **Module Vendor Link** - Link to the product page on the module vendor's site.

- **Module Project** - Link to the module's Project Page: Hackaday Project, GitHub Repository, Hackster, etc.

## Module types

- Sensors (S)
- Actuators (A)
- User Interface (UI) - like Displays, RGB LEDs, Keypads, Vibro, Buzzer, Button, Switch
- Basic I/O (IO) - like ADC, DAC, GPIO
- Connectivity (Conn) - like Hub, Splitter, Multiplexer, Buffer, Repeater, Converter, Modem, GNSS
- Main Control Units (MCU) - like CPU, SoC, SoM
- Core components (Core) - like RTC, Security IC, Tamper, EEPROM, RAM, SD, Flash
- Power Management Units (PMU) - like PSU, PMIC, UPS, Battery Charger, Intelligent Switch, Level Shifter
- Cables and Connectors (CC)

## Database

| # | Module  | Type | Module Description / Datasheet | Chip | Address Mask(s) | Address Range(s) | Module Vendor Link | Module Project | Home Assistant Support |
| --- | ------------- | --- | ------------- | ------------- | ---------------------- | ------------- | ------------- | ------------- | ---------------------- |
| 1 | I2CNavKey | UI | I2C NavKey: 7 functions joypad on the I2C bus | [PIC16F18345](https://www.microchip.com/en-us/product/PIC16F18345)  | 001 A3 A2 A1 A0 | 0x40 - 0x1F | [hackaday.io](https://hackaday.io/project/164886-i2c-navkey) | [github.com](https://github.com/Fattoresaimon/I2CNavKey) | no |
| 2 | [I2CUI3](https://go.iot-devices.com.ua/i2cui3) | UI | UI I2C module with 5-key RGB-LED & buzzer | [PCA9538](https://www.ti.com/product/PCA9538) | 11100 A1 A0 | 0x70 - 0x73 | [iot-devices.com.ua](https://iot-devices.com.ua/en/product-uk/i2cui-user-interface/) | [tindie.com](https://www.tindie.com/products/iotdev/i2cui3-ui-i2c-module-with-5-key-rgb-led-buzzer/) | no |
| 3 | [I2CUI4_V1](https://go.iot-devices.com.ua/i2c-keypad) | UI | [User Interface 5-key I2C Keypad with RGB-LED and Buzzer](https://iot-devices.com.ua/wp-content/uploads/2023/02/i2cui4_v1-product-description-eng.pdf) | [MCP230017](https://www.microchip.com/en-us/product/mcp23017)  | 0100 A2 A1 A0 | 0x20 - 0x27 | [iot-devices.com.ua](https://iot-devices.com.ua/en/product/i2cui4v1-user-interface-i2c-module-with-5keys-keypad-rgb-led-buzzer/) | [tindie.com](https://www.tindie.com/products/iotdev/i2cui4_v1-user-interface-i2c-keypad-with-5-keys/) | [ESPHome](https://esphome.io/components/mcp230xx.html?highlight=mcp23017#mcp23017-label) |
| 4 | [ESP12.OLED_V1](https://go.iot-devices.com.ua/esp8266-mcu-board) | UI | [Universal ESP8266 controller board with 0.96″ I2C OLED and RGB LED](https://iot-devices.com.ua/wp-content/uploads/2023/02/finished-esp12_oled_v1-product-description-eng.pdf) | [SSD1306](https://www.solomon-systech.com/product/ssd1306/)  | 011110 A0 | 0x3C - 0x3D | [iot-devices.com.ua](https://iot-devices.com.ua/en/product/esp12oled-universal-esp8266-mcuboard-oled-en/) | [tindie.com](https://www.tindie.com/products/iotdev/esp12oled-universal-esp8266096oled-mcu-board/) | [ESPHome](https://esphome.io/components/display/ssd1306.html?highlight=ssd1306#over-i2c) |
