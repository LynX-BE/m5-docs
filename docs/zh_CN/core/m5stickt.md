# M5StickT {docsify-ignore-all}

<el-tag effect="plain">SKU:K016-T</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/core/minicore/m5stickt/m5stick_T_01.webp"><img src="assets/img/product_pics/core/minicore/m5stickt/m5stick_T_03.webp"><img src="assets/img/product_pics/core/minicore/m5stickt/m5stick_T_04.webp"></div>

## 描述

**M5StickT** 是一款精致小巧的红外热成像仪,采用最新的FLIR Lepton 3.0长波红外（LWIR）摄像头内核,有效分辨率为160*120,成像画面清晰稳定,是大面积非接触式红外测温的优秀解决方案.其主控芯片采用了ESP32,支持WIFI与蓝牙连接,高达240Mhz的运算能力,为图像输出提供了有利保证,FPS达到7+.屏幕为1.14寸,分辨率135 * 240,此外内置硬件资源也较为丰富,在交互操作方面提供了两个可编程按键和一个拨轮编码器.内部板载一个6轴IMU(MPU6886),麦克风(SPM1423),电源管理芯片为AXP192,并内置300mAh电池.为了方便用户连接外设,在侧面提供了一个4P HY2.0接口.机身为黑色尼龙材质通过3D打印而成,此外在机身的下方提供一个M3螺丝孔和一个1/4螺丝孔用于固定.在固件方面,提供了多达5种色彩显示模式,可指定测量最大最小值或中心值,并且显示温度色域范围可调.

**开关机操作：**

* 开机：按复位按键，持续至少 2 秒

* 关机：按复位按键，持续至少 6 秒

## 使用介绍

按压复位按键进入开机画面，开机默认进入RGB显示模式，左侧为温度图像，右侧上方为电量显示，右侧下方为直方图和温度范围，温度范围随目标温度自动调整。默认靶心自动跟踪温度最大值，按压机身右侧按键(B键)切换跟踪模式（最小值/中心值/最大值），按压机身正面按键A键切换图像显示模式（GRAY/GOLDEN/RAINBOW/IRONBLACK/RGB），拨轮编码器控制显示灵敏度（调整显示温度色域范围），长按复位键6秒关机。

<img src="assets/img/product_pics/core/minicore/m5stickt/m5stick_T_05.webp" width="30%" height="30%">
<img src="assets/img/product_pics/core/minicore/m5stickt/m5stick_T_02.webp" width="30%" height="30%">

## 产品特性

- 基于 ESP32开发
- 外壳: 3D打印尼龙材质
- FLIR Lepton 3.0
- 内置3轴陀螺仪与3轴加速计
- 集成麦克风
- IPS LCD(1.14 寸)
- 带有拨轮编码器与可编程按键
- 内置电源管理芯片
- 内置锂电池供电
- 支持拓展的GROVE/HY2.0接口


## 包含

-  1x M5StickT
-  1x Type-C USB(20cm)

## 应用

-  车辆发动机故障检测
-  建筑除湿保温密封性检测
-  工业炉内壁耐火材料裂痕检测
-  夜晚户外观测动物

**Lepton 3.0参数**

<table>
 <tr><td>有效像素</td><td>160*120</td>
 <tr><td>视野角度</td><td>56°</td>
 <tr><td>快速成像时间</td><td>< 500ms</td>
 <tr><td>有效帧率</td><td>8.7Hz</td>
 <tr><td>输入时钟</td><td>25MHz</td>
 <tr><td>像素尺寸</td><td>12μm</td>
 <tr><td>功耗</td><td>150 mW (典型工作);650 mW (快门拍摄);5 mW (待机)</td>
 <tr><td>动态范围</td><td>低增益-10~400°C;高增益-10~140°C</td>
 <tr><td>波长范围</td><td>8 to 14µm</td>
 <tr><td>热灵敏度</td><td>＜50 mK(0.050°C)</td>
 <tr><td>最佳温度范围</td><td>-10°C to +80°C</td>
</table>


## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>主控资源</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>ESP32</td>
      <td>240MHz dual core, 600 DMIPS, 520KB SRAM, Wi-Fi, dual mode Bluetooth</td>
   </tr>
   <tr>
      <td>Flash闪存</td>
      <td>4MB Flash</td>
   </tr>
   <tr>
      <td>输入电压</td>
      <td>5V @ 500mA</td>
   </tr>
   <tr>
      <td>主机接口</td>
      <td>TypeC x 1, GROVE(I2C+I/0+UART) x 1</td>
   </tr>
   <tr>
      <td>IPS屏幕</td>
      <td>1.14 inch, 135x240 Colorful TFT LCD, ST7789</td>
   </tr>
   <tr>
      <td>麦克风</td>
      <td>SPM1423</td>
   </tr>
   <tr>
      <td>按键</td>
      <td>自定义按键 x 2</td>
   </tr>
   <tr>
      <td>电源管理IC</td>
      <td>AXP192</td>
   </tr>
   <tr>
      <td>天线</td>
      <td>2.4G 3D天线</td>
   </tr>
      <tr>
      <td>MEMS</td>
      <td>MPU6886</td>
   </tr>
      <tr>
      <td>电池容量</td>
      <td>300mAh</td>
   </tr>
    <tr>
      <td>编码器</td>
      <td>拨轮编码器</td>
   </tr>
    <tr>
      <td>热成像IC</td>
      <td>Lepton 3.0</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>26g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>82g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>48*30*29mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>144*44*43mm</td>
   </tr>
<table>

## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/CORE/EasyLoader_M5StickT_FactoryTest.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/CORE/EasyLoader_M5StickT_FactoryTest.dmg">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Core/StickT.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p>热成像操作说明：A键切换跟踪模式，B键切换显示模式，拨轮调整灵敏度.</p>
        </div>
    </div>
</div>

## 管脚映射

**按键 BUTTON A & 按键 BUTTON B**

 <tr>
    <td>ESP32 芯片</td><td>GPIO37</td><td>GPIO39</td>
</tr>
<tr>
    <td>按键 BUTTON A</td><td>按键管脚</td><td></td>
</tr>
<tr>
    <td>按键 BUTTON B</td><td></td><td>按键管脚</td>
</tr>
</table>

**彩色IPS屏幕** 

驱动芯片：ST7789

分辨率：135 * 240

<table>
 <tr><td>ESP32 芯片</td><td>GPIO15</td><td>GPIO13</td><td>GPIO23</td><td>GPIO18</td><td>GPIO5</td></tr>
 <tr><td>IPS 屏幕</td><td>MOSI</td><td>CLK</td><td>DC</td><td>RST</td><td>CS</td></tr>
</table>

**HY2.0 接口**

<table>
 <tr><td>ESP32 芯片</td><td>GPIO33</td><td>GPIO32</td><td>5V</td><td>GND</td></tr>
 <tr><td>HY2.0 接口</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

**麦克风 MIC (SPM1423)**

<table>
 <tr><td>ESP32 芯片</td><td>GPIO0</td><td>GPIO34</td></tr>
 <tr><td>麦克风 MIC</td><td>SCL</td><td>SDA</td></tr>
</table>

**六轴IMU (MPU6886) & 电源管理芯片 (AXP192)**

<table>
 <tr><td>ESP32 芯片</td><td>GPIO22</td><td>GPIO21</td>
 <tr><td>六轴姿态传感器</td><td>SCL</td><td>SDA</td>
 <tr><td>电源管理芯片</td><td>SCL</td><td>SDA</td>
</table>

**拨轮编码器**
<table>
 <tr><td>STM32 芯片</td><td>PA2</td><td>PA3</td><td>PA4</td>
 <tr><td>拨轮编码器</td><td>SW</td><td>EN_B</td><td>EN_A</td>
</table>

**电源管理芯片 (AXP192)**

<table>
 <tr><td>Microphone</td><td>RTC</td><td>TFT backlight</td><td>TFT IC</td><td>ESP32/3.3V MPU6886</td><td>5V GROVE</td>
 <tr><td>LDOio0</td><td>LDO1</td><td>LDO2</td><td>LDO3</td><td>DC-DC1</td><td>IPSOUT</td>
</table>

## 相关链接

-  **Datasheet**

    - [ESP32-PICO](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32-pico-d4_datasheet_cn.pdf)
    - [MPU6886](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/MPU-6886-000193%2Bv1.1_GHIC_en.pdf)
    - [AXP192](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/AXP192_datasheet_cn.pdf)
    - [SPM1423](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/SPM1423HM4H-B_datasheet_en.pdf)
    - [Lepton datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/lepton-3-3.5-datasheet_en.pdf)
    - [Lepton enigneering datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/flir-lepton-engineering-datasheet_en.pdf)
    - [Lepton software interface description](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/flir-lepton-software-interface-description-document_en.pdf)

- **3D打印 STL文件**
   - [STL](https://github.com/m5stack/m5-structural-design-file/tree/master/M5StickT)

## 案例程序

### ArduinoIDE

- 点击[这里](https://github.com/m5stack/M5-StickT)获取Arduino示例





<script>

   var purchase_link = 'https://m5stack.com/collections/m5-core/products/m5-stickt-esp32-thermal-camera-development-kit-lepton-3-0';

   anchor_search(purchase_link);
   scrollFunc();

</script>