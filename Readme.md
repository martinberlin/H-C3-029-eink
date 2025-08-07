### ESP32-C6 ULP mini PCB

This PCB design is based on [C3 design guidelines](https://docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32c3/schematic-checklist.html) and uses the Buck converter schematic of Seeed XIAO C6 [SGM6029](https://www.sg-micro.com/product/SGM6029)

> The SGM6029 family is a low voltage, efficient and miniature synchronous Buck converter with ultra-low quiescent current. Operating at high switching frequency (4.0MHz, TYP), miniature inductors and capacitors can be used to achieve minimal solution size.


#### Using low GPIOs to be able to access them from ULP

```
IO Description
0 Check schematics
1 EPD_
2 EPD_
3 EPD_
4 EPD_
5 EPD_
6 SDA --> I2C ↘
7 SCL --> I2C connected to RTC
```




