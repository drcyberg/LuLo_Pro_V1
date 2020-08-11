# LuLo Pro V1 Wireless Network Router

---

### Description:

The SKW92A module includes an 802.11n MAC and baseband, a 2.4GHz radio and FEM, a 580MHz MIPS CPU, a 5-port 10/100 fast Ethernet switch. Solution for low power, low-cost, and highly integrated AP router and consumer electronic devices, the module requires only an external 3.3V power supply. It supports 802.11n operating up to 144 Mbps for 20 MHz and 300 Mbps for 40 MHz channel respectively, and IEEE 802.11b/g data rates. The module supports bridge mode and AP Client mode and Gateway mode. The high performance Module can process advanced applications effortlessly, such as routing, security and VoIP. It also includes a selection of interface to support a variety of applications, such as a USB port for accessing external storage and 3G/LTE modem. Especially in the IOT, a wide range of applications.

---

### Specifications:

- Compliant to IEEE 802.11b/g/n.
- 2T2R mode with support for a 300Mbps PHY
data rate.
- DDR2 memory up to 1024Mb.
- Flash memory up to 256Mb.
- 4 LAN ports and 1 WAN port.
- Support USB 2.0 slave device for USB disk
and USB 3G/4G dongle and USB camera.
- Support SD card.
- Support interface: I2C, PCM,
I2S(192K/24bits), PWM, SPI slave, UART lite,
GPIO.
- Security: WEP64/128, TKIP, AES, WPA,
WPA2, WAPI.
- Support AP/Client/Router mode.
- Power Supply Adapter DC 5V/1A

---

### Extra Additionals:

- Fan/LED Strip (DC 5V/500mAh)
- Reset button
- Network traffic LEDs indicators
- ICSP header (Programming interface)
- USB connection interface (only debugging mode)
- SD Card interface

---

### V1.1

- Added slide switch (SW2) for standalone flashing mode with only DC 3,3V input power (support many [flashing USB keys](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200810135246&SearchText=ftdi+usb "Aliexpress")), say not necessary external power any more
- Hardware support for more performance and stability issue for the Ethernet ports (Know error: random lagging network)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/14.jpg)

---

### Applications:

- [x] USB WiFi Camera
- [x] IOT (internet of things)
- [x] WiFi AP
- [x] 3G/4G WiFi Router
- [x] WiFi Repeater
- [x] Building Automation
- [x] Home Automation
- [x] Smart Home Gateway
- [x] Industry Control

---

### Application Block Diagram:

![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/8.jpg)

---

### Samples:

![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/1.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/2.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/3.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/4.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/5.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/6.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/7.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/10.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/11.jpg)
![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/12.jpg)

---

### Schematic: [Download](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/lulo/lulo.pdf "Download")

![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/9.jpg)

---

### Firmware: [Download](https://openwrt.org/toh/hwdata/skylab/skylab_skw92a "skw92a") (OpenWrt)

![](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/pictures/13.jpg)

---

### How to flash:

- [Link](https://git.openwrt.org/?p=openwrt/openwrt.git;a=commit;h=e42327aa890e64f8bf5e620c2b2a1fd609ce20fb "Flash")
- [Download](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/lulo/flash.pdf "Flash")

### Important (Maintenance mode):
Before connect a LAN cable from PC to the Router, You must change Ethernet link speed to 10Mb/s, because dont knows upload correct the firmware to the Chip (###error, try again!!!###).

---

### Manual (Chip): [Download](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/lulo/SkyLab_SKW92A_V1.04_datasheet.pdf "Manual")

---

### BOM (Bill Of Materials): [Download](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/lulo/lulo.xlsx "Link") or [View](https://docs.zoho.eu/sheet/published.do?rid=42dfbe86e06a03a254c4d9cb06e8fa9b62792 "View")

---

### PCB Gerber file: [Download](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/manufacturing/lulo_v1.zip "Download")

---

### 3D Models:

- [Base](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/stl/lulo_base.stl "Base")
- [Frame](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/stl/lulo_frame.stl "Frame")
- [Cover](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/stl/lulo_top_cover.stl "Cover")
- [Cover With Fan And Lcd](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/stl/lulo_top_wf_wlcd.stl "Cover With Fan And Lcd")
- [Cover With Lcd](https://github.com/drcyberg/LuLo_Pro_V1/blob/master/stl/lulo_top_wof_wlcd.stl "Cover With Lcd")

---

### Thingiverse: [Link](https://www.thingiverse.com/thing:4262740 "Link")

---

### OpenWrt Forum: [Link](https://forum.openwrt.org/t/prototype-lulo-pro-v1-wireless-network-router/60118 "Link")

---

### If you want to support me: [Donate](https://www.paypal.me/Kunee82 "Donate")

---

### Have a nice day!
