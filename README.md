# u-boot for Orange Pi Zero board - miZy MODs

## Features

* i2c - fixed & activated TWI0 (PA11 PA12)
* ready to display splash screen on boot time for
  ssd1306 i2c OLED 128x64 display
* script source - fixed/remove verify/check crc sum 
* spi flash boot - enabled
* some small another fixes

## Get Source Prepare and Build - need only 10-30 sec

    cd /tmp
    mkdir miZy
    cd miZy

    git clone https://github.com/hyphop/uboot-hyphop-mizy.git
    cd uboot-hyphop-mizy

    ./uboot_prepare
    ./uboot_build

## Output

u-boot-sunxi-with-spl0-i2c-mizy.bin -> ./uboot-mizy/u-boot-sunxi-with-spl.bin
451271 bytes
    
## Deps and cross compilation

toolchain-arm_cortex-a9+neon_gcc-5.3.0_musl-1.1.15_eabi
...

## miZy 
 
miZy - open source minimalistic tiny fast embedded Linux system
for OrangePi Zero board MODs

    ## hyphop ## - its aliase for same name file - read this one for more information about license and etc.
