# I2C Chip Address Database used in IoT modules and DIY electronics

This is a collection of universal hardware modules for IoT and other DIY electronics, which have built-in chips with I2C interface.

A separate row in the table is allocated for each such chip. This means that one module with several chips on board can take up more than one row in the table.
If you are the manufacturer or ambassador of such a module and it is not yet in our collection, please contact us and we will add your module to this table. 

Data structure:

| # | Module  | Module Description | Chip | Address Mask(s) | Address Range(s) | Module Vendor Link | Module GitHub | 
| --- | ------------- | ------------- | ------------- | ---------------------- | ------------- | ------------- | ------------- |
| 1 | I2CUI4_V1 | User Interface 5-key I2C Keypad with RGB-LED and Buzzer | MCP230017  | 0100 A2 A1 A0 | 0x20 - 0x27 | site | github link |

**\#** - row ID.

**Module** - IoT module's unique part number.

**Module Description** - Module's name promoted by the vendor.

**Chip** - Unique IC part name.

**Address Mask(s)** - Possible mask or mask which can be used to address Slave IC on the I2C Bus by the Master.

**Address Range(s)** - All possible HEX-values of addresses are available within the mask.

**Module Vendor Link** - Link to the product page on the module vendor's site.

**Module GitHub** - Link to the module's GitHub Repository.
