STorM32 BGC
===========

<strong>STM32 32-bit microcontroller based 3-axis brushless gimbal controller board</strong>

scheme and design by OlliW (except of STorM32 v4.1)<br>
v0.17: layout by Martinez and OlliW<br>
v4.1: design by KrattWorks

latest board version: v3.3, v4.1

the STorM32 BGC boards and all other hardware published here are open source hardware, under the terms of the TAPR Open Hardware License as published by the Free Hardware Foundation, see http://www.tapr.org/ohl.html

the firmwares are free and the GUI is open source, for the details of the terms of usage/licenses see <a href="http://www.olliw.eu/2013/storm32bgc">here</a>

<strong>further resources:</strong><br>- project web page http://www.olliw.eu/2013/storm32bgc/<br>- thread at rcgroups http://www.rcgroups.com/forums/showthread.php?t=2055844<br>- wiki for the documentation http://www.olliw.eu/storm32bgc-wiki/

## v4.1 Board

Board specifically made for NT and TSTorM32 setups, with on-board motor drivers.

## v3.x Boards

Boards specifically made for NT and TSTorM32 setups.

### STorM32 v3.3m/i

General purpose version.

### STorM32 Raspberry Pi Hat

Hat for the Raspberry Pi.

### STorM32 Micro Series

Series of stackable boards with 20x20 mm hole pattern: Main board, NT Motor-Encoder module, NT Triple Motor module, NT Logger module. 

<strong>changes in v3.3:</strong><br>- board specifically designed for NT and T-STorM32<br>- no motor drivers on board<br>- 3 NT plugs to make it easy to connect several NT modules<br>- NT-X plug carrying also the battery voltage<br>- 5 V power rail on the NT bus, with sufficient "juice"<br>- Rx&Tx on NT bus swapped, to avoid cable crossing to connect with NT modules<br>- support of stacking with a "high-power" extension board<br>- MPU9250 on board, spi (no i2c anymore!)<br>- firmware update procedure via USB<br>- ESP8266 port for WIFI connectability<br>- CAN bus port<br>- no BOOT0 button, smaller RESET button<br>- 0402 size parts<br>- board size as small as I could get it with a 2 layer design: 40 x 25 mm<br>- mounting holes, 3 mm diameter, 35 mm apart

## v1.x Boards

<strong>changes in v1.3:</strong><br>- voltage regulator in DPak package<br>- AUX2 instead of 3.3V pin at AUX port<br>- solder jumper to disconnect bluetooth led<br>- values of resistors R12,R13,R22 changed
<br><strong>changes in v1.2:</strong><br>- minor issues of v1.1 corrected<br>- Futaba S-bus support<br>- Spektrum sattelite connector<br>- usb disconnect network modified to suite F4 processors (thanks ala42!)<br>- usb voltage protection diode added (as in v0.17)<br>- further minor changes in scheme and layout
<br><strong>changes in v1.1:</strong><br>- reverse voltage protection added<br>- layout supports TC4452 motor drivers in DFN package for increased power capabilities<br>- high-side pnp open collector output for driving an IR led added<br>- additional connector for I2C#2 port added<br>- larger solder holes and pads for battery power connection<br>- improved pin arrangement for easier use

## Pictures

<strong>pictures of the v2.4 board</strong><br>
<a href="http://www.olliw.eu/uploads/storm32-bgc-v242-board.png"><img src="http://www.olliw.eu/uploads/storm32-bgc-v242-board.png" width="600"/></a>

<strong>pictures of the v1.2 board (with DFN packages) and v1.3 board (with SOIC packages):</strong><br>
<a href="http://www.olliw.eu/uploads/storm32_bgc_v120_board_dfn_mpu-01-wp01.jpg"><img src="http://www.olliw.eu/uploads/storm32_bgc_v120_board_dfn_mpu-01-wp01.jpg" width="300" height="308"/></a> <a href="http://www.olliw.eu/storm32bgc-wiki/images/1/1c/Joepaisley-storm32-bgc-v13-board-wiki.jpg"><img src="http://www.olliw.eu/storm32bgc-wiki/images/1/1c/Joepaisley-storm32-bgc-v13-board-wiki.jpg" width="300"/></a>

