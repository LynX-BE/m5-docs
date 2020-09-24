# ATOM Lite{docsify-ignore-all}

<el-tag effect="plain">SKU:C008</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/core/minicore/atom/atom_lite_01.webp"><img src="assets/img/product_pics/core/minicore/atom/atom_lite_02.webp"></div>

## 描述

**ATOM Lite** 是M5Stack开发套件系列中一款非常小巧的开发板，其大小只有24 * 24mm，提供更多GPIO供用户自定义，非常适合做嵌入式的智能硬件开发。主控采用了ESP32-PICO-D4方案，集成Wi-Fi和蓝牙模块，内置3D天线，拥有4MB的SPI闪存，提供Infra-Red、RGB Led、按键和GROVE/HY2.0接口。板载Type-C接口可以快速实现程序上传下载，背面提供一个M2螺丝孔用于固定。

## 产品特性

- 基于ESP32开发
- 机身小巧
- 内置红外发射功能
- 带有可编程按键
- RGB LED指示灯
- 可扩展的引脚与接口
- 开发平台: [Arduino](http://www.arduino.cc)、[UIFlow](http://flow.m5stack.com)

## 包含

-  1x ATOM Lite

## 应用

- 物联网节点
- 微型控制器
- 可穿戴设备


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
      <td>Flash</td>
      <td>4MB</td>
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
      <td>PIN接口</td>
      <td>G19, G21，G22，G23，G25, G33</td>
   </tr>
   <tr>
      <td>RGB LED</td>
      <td>SK6812 3535 x 1</td>
   </tr>
      <tr>
      <td>IR</td>
      <td>Infrared transmission </td>
   </tr>
   <tr>
      <td>按键</td>
      <td>自定义按键 x 1</td>
   </tr>
   <tr>
      <td>天线</td>
      <td>2.4G 3D天线</td>
   </tr>
   <tr>
      <td>工作温度</td>
      <td>32°F to 104°F ( 0°C to 40°C )</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>3g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>12g</td>
   </tr>
   <tr>
      <td>主机尺寸</td>
      <td>24 x 24 x 10 mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>24 x 24 x 10 mm</td>
   </tr>
   <tr>
      <td>外壳材质</td>
      <td>Plastic ( PC )</td>
   </tr>
</table>

## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/CORE/EasyLoader_ATOM%20_LITE_FactoryTest.exe">Windows</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Core/ATOM_LITE.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p>通过变色呼吸灯程序，测试RGB LED与按键是否工作正常.</p>
        </div>
    </div>
</div>

## 管脚映射

<table>
 <tr><td>RGB Led</td><td>G27</td></tr>
 <tr><td>Btn</td><td>G39</td></tr>
 <tr><td>IR</td><td>G12</td></tr>
</table>


## 原理图

<img src="assets\img\product_pics\core\minicore\atom\ATOM_LITE_SIMPLE_CIRCUT_20200514.webp">

## 相关链接

- **Datasheet**
    - [ESP32-PICO](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32-pico-d4_datasheet_cn.pdf)
    - [WS2812B-2020](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/WS2812B-2020_ZH_cn_V1.3.pdf)

## 案例程序

### 1. Arduino IDE

- 点击[这里](https://github.com/m5stack/M5Atom)获得Arduino示例
- <mark>程序编译前，请将开发板配置为M5StickC</mark>

### 2. UIFlow

- 点击[这里](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Core/Atom/Atom%20Lite)查看UIFlow相关示例

<img src="assets/img/product_pics/core/minicore/atom/atom_lite_example.webp" width="50%" height="50%">

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-core/products/atom-lite-esp32-development-kit';


   var quickstart_link = 'https://docs.m5stack.com/#/zh_CN/quick_start/atom/atom_quick_start';

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>

