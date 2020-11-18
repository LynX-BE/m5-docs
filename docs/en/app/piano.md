# PIANO

<el-tag effect="plain">SKU:A047</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/app/app_piano_01.webp"><img src="assets/img/product_pics/app/app_piano_02.webp"></div>

## Description

**PIANO** is a application base related to music or sound performing. Comes with two touch sensors(TS20) which communicate with M5 core via I2C protocol,I2C address is 0x6A and 0x7A.

## Include

- 1x PIANO

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>114g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>115g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>240*53*8mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>250*550*6mm</td>
   </tr>
 </table>

## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/APPLICATION/EasyLoader_PIANO_APPLICATION.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/APPLICATION/EasyLoader_PIANO_APPLICATION.dmg">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/App/PIANO.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p>触摸钢琴键盘，驱动扬声器发出不同的音调.</p>
        </div>
    </div>
</div>

## PinMap

**Touch Sensor (TS20) & LED**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO7</td><td>GPIO6</td><td>GPIO5</td><td>GPIO26</td><td>GPIO2</td></tr>
 <tr><td>TS20</td><td>RESET</td><td>EN</td><td>SCL</td><td>SDA</td></tr>
 <tr><td>RGB LED</td><td> </td><td> </td><td> </td><td> </td><td>Signal Pin</td></tr>
</table>

## Example

- [Github](https://github.com/m5stack/M5-ProductExampleCodes/blob/master/App/PIANO/Arduino/M5PIANO/M5PIANO.ino)

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-application/products/acrylic-piano-board-with-rgb-led';

   anchor_search(purchase_link);
   scrollFunc();

</script>