# W5200 Driver for Parallax Propellar - spin

## Description
-. [Parallax Propellar chip](http://parallax.com/microcontrollers/propeller)

-. [WIZnet W5200 Ethernet controller](http://www.wiznet.co.kr/Sub_Modules/en/product/Product_Detail.asp?cate1=5&cate2=7&cate3=56&pid=1144)

-. I changed Mike Gebhard's SPI assembler routine to SPIN language for better understanding and easy migration to next version chip W5500

## Connection
  SPI_SCK       = 12 ' SPI clock from master to all slaves
  
  SPI_MISO      = 13 ' SPI master in serial out from slave
  
  SPI_MOSI      = 14 ' SPI master out serial in to slave
  
  SPI_CS        = 15 ' SPI chip select (active low)
  
  PWDN          = 24 ' Power donwn (Not used)
  
  RESET_PIN     = 6 ' Reset

![image](https://raw.github.com/jbkim/Parallax_W5200/master/Photo/Propeller_WIZ820io.jpg)