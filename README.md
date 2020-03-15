Bluetooth Flash Programmer
==========================

## Main Features

* Support JEDEC's SFDP standard SPI flash.
* Flash R/W speed can reach 260 KB/s via Bluetooth SPP.

## Pinmap

| FLASH | CS | SCLK | MOSI | MISO |
| :---- | -: | ---: | ---: | ---: |
| ESP32 | 15 |   14 |   13 |   12 |

## Commands

* `MTD+ERASE:ALL!`: Erase Full Flash Chip
* `MTD+ERASE:0x%x+0x%x`: Erase Flash: Addr Length
* `MTD+WRITE:0x%x+0x%x`: Write Flash: Addr Length
* `MTD+READ:0x%x+0x%x`: Read Flash: Addr Length
* `MTD+INFO?`: Flash Info

## Repositories

* [ESP32 Controller](https://github.com/redchenjs/bluetooth_flash_programmer_esp32)
* [QT Flash Tools](https://github.com/redchenjs/bluetooth_flash_programmer_qt)
