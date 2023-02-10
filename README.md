# BPI-WiringPi README

This is a modified WiringPi for BPI boards. We call it BPI-WiringPi.
It is based on the original [WiringPi for Raspberry Pi created by Drogon](http://wiringpi.com/).
The modification is done by [BPI-Team](http://www.banana-pi.org/). The BPI-WiringPi API usage are the same to the original wiringPi.
You can donwload the original wiringPi from:
git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.

## Download
### For BPI-M1 / M1Plus
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M1_M1Plus
    
### For BPI-M2
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M2
    
### For BPI-M3
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M3    

### For BPI-M2P
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M2P
    
## Installation
    cd BPI-WiringPi
    chmod +x ./build
    sudo ./build
    
## Examples

You can go to folder "test folder" to test sample codes.

You can also use the examples and instructions provided by http://wiringpi.com/

And the source directory examples also has many demo.

Thanks!

BPI Team

## Tips:

  1. Please remove other versions of the wiringPi first.
  2. As for Armbian system, you need to update board.sh script file:
     * **BPI-M3**: `echo "BOARD=bpi-m3" > /var/lib/bananapi/board.sh`
     * **BPI-M2+**: `echo "BOARD=bpi-m2p" > /var/lib/bananapi/board.sh`
