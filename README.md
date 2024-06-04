# megaTemp
Code for the arduino uno to display temperature on an OLED in both Fahrenheit and Celsius using a tmp36 temperature sensor. 

Included are the main file arduino, the makefile, and several support files for the OLED, uart, etc. 

Acknowlegement and License: i2c.c, ic2.h, SSD1306.c and SSD1306.h are user-defined libraries to operate the SSD1306/OLED over the i2C interface. These are open-source codes provided by Preston Sundar, via github, under the MIT license. That same licence covers all code herein. Contributed files are located here:
https://github.com/prestonsn/AVR-OLED-SSD1306-IIC-DRIVER and https://github.com/prestonsn/AtmegaXX-I2C-Library
