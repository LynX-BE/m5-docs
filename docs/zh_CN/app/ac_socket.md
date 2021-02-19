# AC Socket

<el-tag effect="plain">SKU:K031</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\app\ac_socket\ac_socket_01.webp"><img src="assets\img\product_pics\app\ac_socket\ac_socket_02.webp"></div>

## 描述

**AC Socket** 是一款增强性AC插座.支持定制RS485通信方式，将多个AC插座串联在同一RS485总线上，通过串行通信能够同时控制多个AC插座，能够应用于一般的工业应用场景.

**AC Socket**的整体构造由插座面板与BASE26底座拼接而成，底座侧面嵌入了一个3pin接口，这是AC插座的电源入口.

<br>

<img src="assets\img\product_pics\app\ac_socket\p01.webp" width="30%" height="30%">

- 顶部是AC插头接口，其内部的继电器控制将开启和关闭电源.

<img src="assets\img\product_pics\app\ac_socket\p02.webp" width="30%" height="30%">

- 为了让更多的AC插座串联，插座的另一侧提供了HT3.96端子连接器.(图中的橙色端子).

<br>

<img src="assets\img\product_pics\app\ac_socket\p03.webp" width="30%" height="30%">

- 底部的电路板主要负责将AC电源220V转换为DC 5V，为微处理器STM32F030F4和RS485相关电路供电,从图中可以看出，这两部分通过M-Bus插座和一对电源线连接.在插座的顶部提供了一颗红色LED指示灯.

<img src="assets\img\product_pics\app\ac_socket\p04.webp" width="30%" height="30%">

## 产品特性

- RS485 接口
- 串行通信协议:ModBUS-RTU
- 支持多个设备串行连接
- 内置STM32F030F4
- 采用BASE26底座 
- 内嵌4x M3螺母
- 输入: 100-240V
- 输出: 10A
- 电源状态指示灯

## 包含

- 1x AC Socket

## 应用

-  智能AC插座

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>120g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>158g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>52*52*60mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>72*102*72mm</td>
   </tr>
 </table>

## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/APPLICATION/EasyLoader_AC_Socket_APPLICATION.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/APPLICATION/EasyLoader_AC_Socket_APPLICATION.dmg">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/App/AcSocket.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p>按下B键接通电源，按下A键关闭电源.</p>
        </div>
    </div>
</div>

## 案例程序

### 1. Arduino

- [请点击此处获取Arduino示例程序](https://github.com/m5stack/M5Stack/tree/master/examples/Modules/AC-SOCKET)

## ACSocket Modbus RTU 协议

### 说明：

- 1.通信采用RS485， 1位起始位 + 8位数据位 + 1位结束位
- 2.波特率9600
- 3.Device ID默认为AAH
- 4.地址00H为广播地址，从机无回复

### 指令：（十六进制）(Modbus RTU格式)

### 1.	写线圈

主机发送：

`AA 05 00 00 FF 00 95 E1`(闭合线圈)

`AA 05 00 00 00 00 D4 11`(断开线圈)

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>发送内容</td>
      <td>字节数</td>
      <td>发送报文</td>
      <td>备注</td>
   </tr>
   <tr style="text-align:center">
      <td>模块地址</td>
      <td>1</td>
      <td>AAH</td>
      <td>00H为广播地址</td>
   </tr>
   <tr style="text-align:center">
      <td>功能码</td>
      <td>1</td>
      <td>05H</td>
      <td>写单个线圈</td>
   </tr>
   <tr style="text-align:center">
      <td>起始寄存器地址</td>
      <td>2</td>
      <td>0000H</td>
      <td>线圈0地址</td>
   </tr>
   <tr style="text-align:center">
      <td>写入数据</td>
      <td>2</td>
      <td>FF00H</td>
      <td>FF00H：表示线圈闭合 | 0000H：表示线圈断开</td>
   </tr>
   <tr style="text-align:center">
      <td>CRC校验</td>
      <td>2</td>
      <td>XXXXH</td>
      <td>前面所有数据的CRC码（CRC16）</td>
   </tr>
</table>

从机应答：

操作成功返回原始数据：

`AA 05 00 00 FF 00 95 E1`

操作失败返回：

`AA 85 错误码 CRC_L CRC_H`

### 2.	读线圈

主机发送：

`AA 01 00 00 00 01 E4 11`

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>发送内容</td>
      <td>字节数</td>
      <td>发送报文</td>
      <td>备注</td>
   </tr>
   <tr style="text-align:center">
      <td>模块地址</td>
      <td>1</td>
      <td>AAH</td>
      <td>00H为广播地址</td>
   </tr>
   <tr style="text-align:center">
      <td>功能码</td>
      <td>1</td>
      <td>01H</td>
      <td>读线圈</td>
   </tr>
   <tr style="text-align:center">
      <td>起始寄存器地址</td>
      <td>2</td>
      <td>0000H</td>
      <td>线圈0地址</td>
   </tr>
   <tr style="text-align:center">
      <td>读出数量</td>
      <td>2</td>
      <td>0001H</td>
      <td>只能为0001H</td>
   </tr>
   <tr style="text-align:center">
      <td>CRC校验</td>
      <td>2</td>
      <td>XXXXH</td>
      <td>前面所有数据的CRC码（CRC16）</td>
   </tr>
</table>

从机应答：

操作成功返回： 

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>地址</td>
      <td>功能码</td>
      <td>返回数据长度</td>
      <td>线圈状态</td>
      <td>CRC_L</td>
      <td>CRC_H</td>
   </tr>
   <tr style="text-align:center">
      <td>AA</td>
      <td>01</td>
      <td>01</td>
      <td>01</td>
      <td>B0</td>
      <td>6C</td>
   </tr>
</table>

线圈状态：`01H -> 线圈闭合` \ `00H -> 线圈断开`

操作失败返回：`AA 81 错误码 CRC_L CRC_H`

### 3.	写设备地址

主机发送：

`AA 41 00 00 00 12 A4 13`

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>发送内容</td>
      <td>字节数</td>
      <td>发送报文</td>
      <td>备注</td>
   </tr>
   <tr style="text-align:center">
      <td>模块地址</td>
      <td>1</td>
      <td>AAH</td>
      <td>00H为广播地址</td>
   </tr>
   <tr style="text-align:center">
      <td>功能码</td>
      <td>1</td>
      <td>41H</td>
      <td>设置模块地址</td>
   </tr>
   <tr style="text-align:center">
      <td>起始寄存器地址</td>
      <td>2</td>
      <td>0000H</td>
      <td>地址</td>
   </tr>
   <tr style="text-align:center">
      <td>模块新地址</td>
      <td>1</td>
      <td>12H</td>
      <td>1个字节</td>
   </tr>
   <tr style="text-align:center">
      <td>CRC校验</td>
      <td>2</td>
      <td>XXXXH</td>
      <td>前面所有数据的CRC码（CRC16）</td>
   </tr>
</table>

从机应答：

操作成功返回原始数据：

`AA 41 00 00 00 12 A4 13` 

操作失败返回：

`AA C1 错误码 CRC_L CRC_H`

### 4.	广播恢复设备地址

主机发送：

`00 42 00 00 A0 30 `

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>发送内容</td>
      <td>字节数</td>
      <td>发送报文</td>
      <td>备注</td>
   </tr>
   <tr style="text-align:center">
      <td>广播地址</td>
      <td>1</td>
      <td>00H</td>
      <td>00H为广播地址</td>
   </tr>
   <tr style="text-align:center">
      <td>功能码</td>
      <td>1</td>
      <td>42H</td>
      <td>恢复地址为AAH</td>
   </tr>
   <tr style="text-align:center">
      <td>起始寄存器地址</td>
      <td>2</td>
      <td>0000H</td>
      <td>地址</td>
   </tr>
   <tr style="text-align:center">
      <td>CRC校验</td>
      <td>2</td>
      <td>XXXXH</td>
      <td>前面所有数据的CRC码（CRC16）</td>
   </tr>
</table>

从机应答：`无`

<script>

   var purchase_link = 'https://m5stack.com/products/m5-ac-socket';

   anchor_search(purchase_link);
   scrollFunc();

</script>