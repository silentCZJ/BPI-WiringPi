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

---

# BPI-WiringPi 简介

BPI-WiringPi是经修改后适用于香蕉派系列开发板的WiringPi版本。它基于WiringPi官方版本[WiringPi for Raspberry Pi created by Drogon](http://wiringpi.com/)，并由比派团队[BPI-Team](http://www.banana-pi.org/)进行修改。其接口的调用方法和官方版本相同。

git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.

## 下载方式
### BPI-M1 / M1Plus
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M1_M1Plus
    
### BPI-M2
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M2
    
### BPI-M3
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M3    

### BPI-M2P
    git clone https://github.com/BPI-SINOVOIP/BPI-WiringPi.git -b BPI_M2P
    
## 安装方式
    cd BPI-WiringPi
    chmod +x ./build
    sudo ./build
    
## 示例

你可以到"test folder"文件夹中测试示例代码。

你还可以参考官方提供的例子和指导： http://wiringpi.com/

源目录中也有很多示例文件。

感谢使用!

BPI Team

## 提示:

  1. 在使用该版本前请先将其他版本的wiringPi移除干净。
  2. 如果您使用的是Armbian系统，您需要修改board.sh脚本文件：
     * **BPI-M2Berry**: `echo "BOARD=bpi-m2u" > /var/lib/bananapi/board.sh`
     * **BPI-M2+**: `echo "BOARD=bpi-m2p" > /var/lib/bananapi/board.sh`
