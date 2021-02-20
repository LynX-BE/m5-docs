# FIRE

<el-tag effect="plain">SKU:K007</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/core/fire/product_pic_fire.webp"> <img src="assets/img/product_pics/core/fire/m5_fire_01.webp"></div>

## Tutorial&Quick-Start

Choose the development platform you want to use, view the corresponding tutorial&quick-Start.

<a href="/#/en/quick_start/m5core/m5stack_core_get_started_MicroPython"><el-tag effect="plain">UIFlow</el-tag></a>
<a href="/#/en/arduino/arduino_development"><el-tag effect="plain">Arduino</el-tag></a>

## Description 

**M5Stack FIRE Kit**, as one of the M5Stack developing kit series, is an upgrade from the Gray kits. Providing 9-Axis IMU sensor(6-Axis posture acceleration measurement + 3-Axis magnetic measurement), it equips with more hardware resources : 16M Flash + 4M PSRAM , enhanced Base (M5GO Base and M5GO CHG Base), larger battery, etc. For those developers who ask for hardware performance, Fire will be a good choice.

With a IMU posture sensor, there are a lot of situations which you can apply this kit to: detecting acceleration, angulation, and trajectory. You can make relative products like sports data collector, 3D remote gesture controller and more base on the above functions.

**FIRE** is M5 Core device. Its modular, stackable, scalable, and portable device is powered with an ESP-32 core, which makes it open source, low cost, full-function, and easy for developers to handle new product development on all stages include circuit design, PCB design, software, mold design and production.

M5Stack Fire comes with three separable parts. The top part ,just like Basic and Gray Kit, has all kinds of processors, chips ,sockets, 2.4G antenna, ESP32, power management IC , a LCD screen and some other interface components. The middle part is called M5GO base which provides a lithium battery, M-BUS socket , LED bar and three more GROVE Ports. The bottom part is a charge table, which can be connected to the M5GO base via POGO pins.

If you want to explore the fastest way of IoT prototyping, M5Stack development board is the perfect solution. Not like others, M5Stack development board is highly efficient, covered with industrial grade case and **ESP32-based** development board. It integrates with Wi-Fi & Bluetooth modules and contains a dual-core and 16MB of SPI Flash . Together with 30+ M5Stack stackable modules , 40+ extendable units and different levels of program language, you can create and verify your IoT product in a very short time. 

Supportive development platforms and programming languages: Arduino, Blockly language with [UIFlow](http://flow.m5stack.com), Micropython. Regardless of what level programming skill you have, M5Stack would guide you in every step of the way to realize your idea as well as to the final productlization.

If you ever played with ESP8266, you would realize that ESP32 is a perfect upgrade out of ESP8266. In comparison, ESP32 has more GPIOs, more analog inputs and two analog outputs, multiple extra peripherals( like a spare UART ). Official developing platform ESP-IDF has transplanted with FreeRTOS. With dual-core and real time OS you can get more organized code and much high speed processor.


**Notice:**

The GPIO 16 / 17 in Fire is connected to the PSRAM by default, so when you connect or stack other function modules, you need to avoid conflicts with these two pins to prevent the device from working improperly and causing instability.

**Power on/off:**

* Power on: click the red power button on the left

* Power off: Quickly double-click the red power button on the left

## Product Features

- ESP32-based
- Speaker, 3 Buttons, LCD(320*240)
- TF card slot (16G Maximum size)
- Battery Socket & Lipo Battery
- Extendable Pins & Holes
- M-Bus Socket & Pins
- Development Platform [UIFlow](http://flow.m5stack.com), [MicroPython](http://micropython.org/), [Arduino](http://www.arduino.cc)

## Include

-  1x FIRE
-  1x M5GO CHG Base
-  2x LEGO block
-  5x LEGO connector
-  1x M3 hex wrench
-  1x Type-C USB(100cm)
-  1x User Manual

## Applications

- Internet of things terminal controller
- Stem education product
- DIY creation

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>ESP32</td>
      <td>240MHz dual core, 600 DMIPS, 520KB SRAM, Wi-Fi, dual mode Bluetooth</td>
   </tr>
   <tr>
      <td>Flash Memory</td>
      <td>16MB</td>
   </tr>
   <tr>
      <td>PSRAM</td>
      <td>4MB</td>
   </tr>
   <tr>
      <td>Power Input</td>
      <td>5V @ 500mA</td>
   </tr>
   <tr>
      <td>Port</td>
      <td>TypeC x 1, GROVE(I2C+I/0+UART) x 1</td>
   </tr>
   <tr>
      <td>IPS Screen</td>
      <td>2 inch, 320x240 Colorful TFT LCD, ILI9342C, max brightness 853nit</td>
   </tr>
   <tr>
      <td>Speaker</td>
      <td>1W-0928</td>
   </tr>
   <tr>
      <td>Button</td>
      <td>Custom button x 3</td>
   </tr>
   <tr>
      <td>MEMS</td>
      <td>BMM150 + MPU6886</td>
   </tr>
   <tr>
      <td>Battery</td>
      <td>500 mAh @ 3.7V</td>
   </tr>
   <tr>
      <td>Antenna</td>
      <td>2.4G 3D Antenna</td>
   </tr>
   <tr>
      <td>Operating Temperature </td>
      <td>32°F to 104°F ( 0°C to 40°C )</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>62.3g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>162g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>54mm x 54mm x 30.5mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>105mm x 65mm x 40mm</td>
   </tr>
   <tr>
      <td>Case Material</td>
      <td>Plastic ( PC )</td>
   </tr>
</table>


### M5GO Bottom

[Click to view details parameters](en/base/m5go_bottom)

## EasyLoader

>EasyLoader is a concise and fast program writer, which has a built-in case program related to the product. It can be burned to the main control by simple steps to perform a series of function verification. Please install the corresponding driver according to the device type. M5Core host [Please click here to view the CP210X driver installation tutorial](en/arduino/arduino_development), M5StickC/V/T/ATOM series can be used without driver)

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/CORE/EasyLoader_UIFlow_v1.4.5.exe">Windows</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Core/FIRE.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>Description:</p>
            <p>Load UIFlow firmware, built-in demo program supports testing of accelerometer, LED BAR, microphone, buttons and some peripheral sensors. The firmware can be used for UIFlow graphical programming.</p>
        </div>
    </div>
</div>

## Peripherals Pin Map

**LCD & TF card**

LCD ：320x240
TF card Maximum size 16GB

<table>
 <tr><td>ESP32 Chip</td><td>GPIO23</td><td>GPIO19</td><td>GPIO18</td><td>GPIO14</td><td>GPIO27</td><td>GPIO33</td><td>GPIO32</td><td>GPIO4</td></tr>
 <tr><td>ILI9342C</td><td>MOSI/MISO</td><td>/</td><td>CLK</td><td>CS</td><td>DC</td><td>RST</td><td>BL</td><td> </td></tr>
 <tr><td>TF Card</td><td>MOSI</td><td>MISO</td><td>CLK</td><td> </td><td> </td><td> </td><td> </td><td>CS</td></tr>
</table>

**Button & Speaker**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO39</td><td>GPIO38</td><td>GPIO37</td><td>GPIO25</td></tr>
 <tr><td>Button Pin</td><td>BUTTON A</td><td>BUTTON B</td><td>BUTTON C</td><td>/</td></tr>
 <tr><td>Speaker</td><td> </td><td> </td><td> </td><td>Speaker Pin</td></tr>
</table>

**GROVE Port A & IP5306**

We've use the customized I2C version of IP5306, on power management.

Its I2C address is 0x75. Click [here](https://github.com/m5stack/M5-Schematic/blob/master/Core/IIC_IP5306_REG_V1.4.pdf) to check its datasheet

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVE A</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
 <tr><td>IP5306</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

**IP5306 charging/discharging，Voltage parameter**

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>charging</td>
      <td><td>
      <td>discharging</td>
   </tr>
   <tr>
      <td>0.00 ~ 3.40V -> 0%</td>
      <td><td>
      <td>4.20 ~ 4.07V -> 100%</td>
   </tr>
   <tr>
      <td>3.40 ~ 3.61V -> 25%</td>
      <td><td>
      <td>4.07 ~ 3.81V -> 75%</td>
   </tr>
   <tr>
      <td>3.61 ~ 3.88V -> 50%</td>
      <td><td>
      <td>3.81 ~ 3.55V -> 50%</td>
   </tr>
   <tr>
      <td>3.88 ~ 4.12V -> 75%</td>
      <td><td>
      <td>3.55 ~ 3.33V -> 25%</td>
   </tr>
   <tr>
      <td>4.12 ~   /   -> 100%</td>
      <td><td>
      <td>3.33 ~ 0.00V -> 0%</td>
   </tr>
</table>

**6-Axis MotionTracking Sensor MPU6886**

MPU6886 I2C address 0x68

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>MPU6886</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

**3-Axis Geomagnetic Sensor BMM150**

BMM150 I2C address 0x10

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>BMM150</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

## M5GO Base Port

**GROVE Port B**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO36</td><td>GPIO26</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVE B</td><td>GPIO36</td><td>GPIO26</td><td>5V</td><td>GND</td></tr>
</table>

**GROVE Port C**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO16</td><td>GPIO17</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVE C</td><td>RXD</td><td>TXD</td><td>5V</td><td>GND</td></tr>
</table>

**LED Bar & Micphone & Speaker**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO15</td><td>GPIO34</td><td>GPIO25</td></tr>
 <tr><td>Hardwares</td><td>SIG Pin</td><td>MIC Pin</td><td> Speaker Pin</td></tr>
</table>



## M5PORT EXPLAIN

<table>
      <thead>
         <th>PORT</th>
         <th>PIN</th>
         <th>Note:</th>
      </thead>
      <tbody>
      <tr>
         <td>PORT-A(Red)</td>
         <td>G21/22</td>
         <td>I2C</td>
      </tr>
      <tr>
         <td>PORT-B(Black)</td>
         <td>G26/36</td>
         <td>DAC/ADC</td>
      </tr>
      <tr>
         <td>PORT-C(Blue)</td>
         <td>G16/17</td>
         <td>UART</td>
      </tr>
    </tbody>
</table>

## ESP32 ADC/DAC

<table>
      <thead>
         <th>ADC1</th>
         <th>ADC2</th>
         <th>DAC1</th>
         <th>DAC2</th>
      </thead>
      <tbody>
      <tr>
         <td>8 channels</td>
         <td>10 channels</td>
         <td>2 channels</td>
         <td>2 channels</td>  
      </tr>
      <tr>
         <td>G32-39</td>
         <td>G0/2/4/12-15/25-27</td>
         <td>G25</td>
         <td>G26</td>
      </tr>
    </tbody>
</table>

## M-BUS

<img src="assets/img/product_pics/core/M-BUS.webp" alt="M_BUS"  width="60%" height="36%">

When using the RGB LED of gpio15, it is recommended to initialize,pinMode(15, OUTPUT_OPEN_DRAIN);
For more information about Pin assignment and Pin Remapping, Please refer to [ESP32 Datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_en.pdf)


## Schematic

- [Schematic](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/Core/M5-Core-Schematic(20171206).pdf)

## Related Link

-  **Datasheet** 

    - [ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_en.pdf)
    - [MPU6886](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/MPU-6886-000193%2Bv1.1_GHIC_en.pdf)
    - [BMM150](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/BMM150_datasheet_en.pdf)
    - [SH200Q](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/SH200Q_en.pdf)
    - [IP5306](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/IIC_IP5306_REG_V1.4_cn.pdf)

-  **API**

   - [Arduino API](en/arduino/arduino_home_page?id=m5core_api)

## Version Change

<div class="table-wrapper">
    <table class="fl-table">
        <thead>
        <tr>
            <th>Release Date</th>
            <th>Product Change</th>
            <th>Note:</th>
        </tr>
        </thead>    
        <tbody>
        <tr>
            <td>2018.6</td>
            <td>Initial public release</td>
            <td>/</td>
        </tr>
        <tr>
            <td>2019.7</td>
            <td>MPU9250 changed to SH200Q+BMM150, TN screen changed to IPS screen</td>
            <td>before use . pls upgrade your M5Stack lib to the latest version (after 0.2.8) to solve screen reverse color problem.</td>
        </tr>
        <tr>
            <td>2019.8</td>
            <td>SH200Q changed to MPU6886</td>
            <td>/</td>
        </tr>
        <tr>
            <td>2019.11</td>
            <td>Battery capacity changed from 600mAh to 500mAh</td>
            <td>/</td>
        </tr>
        <tbody>
    </table>
</div>

## Example

### Arduino IDE

- Click[here](https://github.com/m5stack/M5Stack/tree/master/examples/Basics)to get Arduino code

## Video

**m5stack instroduce**

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/LukeVideo/Introducing%20M5Stack.mp4" type="video/mp4">
</video>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-core/products/fire-iot-development-kit';

   var quickstart_link = 'https://docs.m5stack.com/#/en/quick_start/m5core/m5stack_core_quick_start';

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>