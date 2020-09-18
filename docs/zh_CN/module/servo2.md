# Module SERVO 2

<el-tag effect="plain">SKU:M014</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\module\servo\servo_01.webp"></div>

## 描述

**SERVO 2** 是M5Stack堆叠模块系列中的一款舵机驱动模块，内部采用PCA9685 16通道PWM控制器，可以同时控制16路舵机。采用直流电源输入（6-12V）设计，通过两片SY8368AQQC进行降压，双通道输出最大总功率35W (5V/3.5A*2)，单通道输出最大功率25W(5V/5A)，当使用电池底座供电时最高支持5V/2A输出。模块与主机直接通过I2C进行通讯（默认0x40），通过拨码开关可改变I2C地址，这也意味着多个SERVO2可以堆叠使用，板上有一个电源切换开关，可控制SERVO2电源通断。


## 产品特性

-  16x 舵机驱动通道
-  2x 电源指示灯
-  I2C地址可调
-  支持内部/外部供电
-  DC 输入: 6-12V
-  DC 连接器类型: XT30 (母头)

## 包含

-  1x Servo2 模块

## 应用

-  人形机器人
-  仿生多关节机器人
-  3轴舵机云台

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>54.2*54.2*13.2mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>mm</td>
   </tr>
 </table>

## 相关链接

- **[PCA9685](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/module/PCA9685.pdf)**

## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="">Windows</a>
            <a href="">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p></p>
        </div>
    </div>
</div>

## 案例程序

### 1. Arduino IDE

[请点击此处下载Arduino代码]()

## 原理图

<img src="assets/img/product_pics/module/servo2/servo2_sch.webp">


<script>

   var purchase_link = '';

   anchor_search(purchase_link);
   scrollFunc();

</script>