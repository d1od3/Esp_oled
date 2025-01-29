# Esp_oled
this code will help you to display data on the screen of esp32-s2mini You can customize the pins for yourself 
standard pins scl 35 sda 33 (customizable)
# what's display?
display 128x64 ssd1306
# what's esp?
esp32-s2mini v1
# how to change pins?
change this fragment 
U8G2_SSD1306_128X64_NONAME_F_SW_I2C u8g2(U8G2_R0, /* clock=*/ 35, /* data=*/ 33, /* reset=*/ U8X8_PIN_NONE);
