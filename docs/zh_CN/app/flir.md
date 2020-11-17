# FLIR

<el-tag effect="plain">SKU:K021</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/app/app_flir_01.webp"><img src="assets/img/product_pics/app/app_flir_02.webp"></div>

## 描述

**FLIR** 是一款微型红外热成像仪.采用最新的FLIR Lepton 3.0长波红外（LWIR）摄像头内核，相对于2.x版本增强了2倍分辨率，4倍像素.

使用3D打印定制的底座外壳，完美兼容M5Core堆叠体系.模块通过I2C协议进行控制，默认生成分辨率为 160×120 的有效图像,你可以通过修改程序进行图像处理，使其显示不同的分辨率.功能强大的 FLIR 是非接触式温度测量的完美解决方案.

**注意:** 长时间工作的热成像仪 Lepton 存在发热现象，但并不会影响输出的图像.


## 产品特性

- 160×120 有效像素
- Lepton 低功耗工作 — 150 mW (典型工作), 650 mW (快门拍摄), 5 mW (待机)
- Field of view: 56°, with shutter
- Lepton 输入电源电压: 1.2V，2.8V，2.5V - 3.1V IO
- 快速成像 (< 0.5 second)
- 产品尺寸：54mm x 54mm x 29mm

## 规格参数

| *技术指标* | *参数值*  |
| :-----------: | :------:  |
| 有效帧频 | 8.7Hz      |
| 输入时钟  | 25-MHz|
| 像素尺寸  | 12µm       |
| 场景动态范围 | 低增益模式: -10 to 400°C; 高增益模式: -10 to 140°C |
| 波长范围 | 8 µm to 14 µm       |
| 热灵敏度	| ＜50 mK（0.050℃）       |
| 输入电压	| 2.8 V, 1.2 V, 2.5 V - 3.1 V IO       |
| 最佳温度范围	| -10 °C to +80 °C |

## 包含

- 1x FLIR

## 应用

- 车辆发动机故障检测
- 建筑除湿保温密封性检测
- 工业炉内壁耐火材料裂痕检测
- 夜晚户外观测动物

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>17g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>34g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>54*54*13mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>125*67*23mm</td>
   </tr>
 </table>

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Application/FLIR/EasyLoader_APP_FLIR_Lepton_Bot.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录

?>3.EasyLoader烧录前需要安装有CP210X（USB驱动程序），[点击此处查看驱动安装教程](zh_CN/related_documents/M5Burner#安装串口驱动)

## 相关链接

- **Datasheet** - [Lepton 3&3.5](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/lepton-3-3.5-datasheet_en.pdf)
- **[Lepton Engineering Datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/flir-lepton-engineering-datasheet_en.pdf)**
- **[Lepton Software Interface Description](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/flir-lepton-software-interface-description-document_en.pdf)**

## 案例程序

*如需获取完整代码， [请点击此处.](https://github.com/m5stack/Applications-Lepton3.0/tree/master/lepton3/Src/Lepton_Bot)。*

<img src="assets/img/product_pics/app/app_flir_03.webp">

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-application/products/flir-radiometric-lepton';
   anchor_search(purchase_link);
   scrollFunc();

</script>