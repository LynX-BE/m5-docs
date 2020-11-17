# Module GSM

<el-tag effect="plain">SKU:M026</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\module\gsm\gsm_01.webp"><img src="assets\img\product_pics\module\gsm\gsm_02.webp"></div>

## 描述

**GSM** 是M5Stack堆叠模块系列中的一款，GSM通信模块.内部集成**M6315** GSM/GPRS 工业级通信模组. 支持 GPRS class12 和 GPRS CS-1,CS-2,CS-3,CS-4 编码，兼备性价比与出色的抗干扰性，可向电力、石油、水务、燃气、 交通、金融等行业客户提供稳定的 M2M 通信功能.

<img src="assets\img\product_pics\module\gsm\gsm_03.webp" width="30%" height="30%"> <img src="assets\img\product_pics\module\gsm\gsm_04.webp" width="30%" height="30%">


?>**M5Stack Fire** 中的 GPIO 16 / 17 默认与PSRAM连接，这使得GSM模块的TXD / RXD（GPIO16，GPIO17）与其产生冲突.因此，当你使用 M5Stack Fire 去驱动 GSM 模块时，你需要将 GSM 模块的 TXD 与 RXD 切断，然后通过飞线引至另一组 UART 引脚.

<img src="assets/img/product_pics/module/gsm/module_gsm_note01.webp" width="100%">

## 产品特性

- SIM卡类型: Nano
- 状态信号：两路LED指示灯
- 板载麦克风
- 串行通信：Uart2 16/17
- 板载双路扬声器信号输出：
    SPK1扬声器信号输出接口
    SPK2扬声器信号输出到主机
- 工作温度范围：-40°C 至+ 85°C
- 频段（MHz）:
    850/900/1800/1900 
- 数据传输:
    速率 (kbps) 85.6(UL)/85.6(DL) 
    GPRS 多时隙 Class12
    SMS 支持 PDU/TEXT 模式
    网络协议 IPV4/IPV6*/TCP/UDP/PPP/HTTP/FTP/MQTT 
- 耗流:
    <2mA@DRX=5 

- 补充说明：
    GPIO2维持高电平2s开机 
    GPIO2维持高电平8s 关机
    电源按钮长按2s开机 
    电源按钮长按8s关机
    GPIO26高电平模块复位


## 包含

-  1x GSM 模块

## 应用

-  无线通信系统
-  M2M通信


## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>13g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>23g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>54.2*54.2*12.8mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>60*57*17mm</td>
   </tr>
 </table>

## 相关链接

-  **Datasheet** - [MC6315](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/module/M6315_cn.pdf)

-  **Datasheet** - [MC6315 AT指令表](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/module/M6315%20AT_Command_Interface_Specification_cn.pdf)
  
## 原理图

- [GSM Module](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/Modules/module_gsm_sch.pdf)

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Module/EasyLoader_GSM_MODULE.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录

?>3.EasyLoader烧录前需要安装有CP210X（USB驱动程序），[点击此处查看驱动安装教程](zh_CN/related_documents/M5Burner#安装串口驱动)

## 案例程序

### Arduino IDE

[请点击此处下载Arduino代码](https://github.com/m5stack/M5Stack/tree/master/examples/Modules/GSM_M6315)

### 管脚映射

<table>
 <tr><td>M5Stack</td><td>GPIO16</td><td>GPIO17</td><td>5V</td><td>GND</td></tr>
 <tr><td>Module GSM</td><td>RX</td><td>TX</td><td>5V</td><td>GND</td></tr>
</table>

## MBUS引脚定义

<img src="assets\img\product_pics\module\module_bus.webp"/>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-module/products/m5stack-gsm-module';


   anchor_search(purchase_link);
   scrollFunc();

</script>