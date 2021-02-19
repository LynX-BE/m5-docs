# M5Stick {docsify-ignore-all}

<img src="assets/img/product_pics/core/minicore/m5stick/m5stick_02.png" alt="gray_02" width="300" height="300">
<img src="assets/img/product_pics/core/minicore/m5stick/m5stick_04.png" alt="gray_02" width="300" height="300">

* * *

:memo:**[概要](#概要)**&nbsp;&nbsp;&nbsp;:bulb:**[クイックスタート](ja/quick_start/m5stick/m5stick_quick_start)**&nbsp;&nbsp;&nbsp;:octocat:**[サンプルコード](#サンプルコード)** &nbsp;&nbsp;&nbsp; :electric_plug:**[回路図](#回路図)** &nbsp;&nbsp;&nbsp; 🛒**[購入リンク](https://www.aliexpress.com/item/M5Stack-M5Stick-ESP32-1-3-OLED-80-mah-Ir/32947692973.html)**&nbsp;&nbsp;&nbsp;:clapper:**[関連動画](#関連動画)**

## 概要

<mark>**M5Stick**</mark> は1.3インチの白黒OLEDスクリーン(64x128)、LED、ボタン、ブザー、IR送信機と80mAhの電池を内蔵した開発用ボードです。小型なのでウェアラブルデバイスとして使用したり、壁などに固定して利用することが可能です。

**M5Stick** は２種類のモデルがあります。通常版と MPU9250 版です。MPU9250 版には９軸のIMUが搭載され、さらに`WATCH BELT`、`WALL/1515`、`BRICK`が付属します。

**ボタンAとベルト用の凹部**

<img src="assets/img/product_pics/core/minicore/m5stick/m5stick_06.png">

**電源操作方法：**

* 電源オン：シングルクリック（リセットボタン兼用）
* 電源オフ：ダブルクリック

## 特徴

- サポートプログラミング
  - Arduino
  - UIFlow (Blockly / MicroPython)
- ウェアラブル
- MEMS IMU(MPU9250版のみ)

## ピンマップ

 <img src="assets/img/product_pics/core/minicore/m5stick/m5stick_03.png" alt="gray_04" width="300" height="300">

**青色LED & ボタン & ブザー & IR送信機**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO17</td><td>GPIO19</td><td>GPIO26</td><td>GPIO35</td></tr>
 <tr><td>IR Transmitter</td><td>Transmitter Pin</td><td> </td><td> </td><td> </td></tr>
 <tr><td>Blue LED</td><td> </td><td>LED Pin</td><td> </td><td> </td></tr>
<tr><td>BUZZER</td><td> </td><td> </td><td>BUZZER Pin</td></tr>
<tr><td>BUTTON</td><td> </td><td> </td><td> </td><td>BUTTON Pin</td></tr>
</table>

**OLED**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO14</td><td>GPIO27</td><td>GPIO33</td>
 <tr><td>OLED</td><td>CS</td><td>DC</td><td>RST</td>
</table>

**GROVEインタフェース**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO13</td><td>GPIO25</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVEインタフェース</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

**GRAY (MPU9250有り):**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td>
 <tr><td>9-axis attitude sensor(MPU9250)</td><td>SCL</td><td>SDA</td>
</table>

**<mark>メモ:</mark>**

*各コアの主な仕様は以下の表の通りです。*

- *比較表の**チェック**は[こちら](https://github.com/m5stack/M5-Schematic/blob/master/Core/hardware_difference_between_cores_zh_CN.md)。*

- *比較表の**ダウンロード**は[こちら](https://github.com/m5stack/M5-Schematic/blob/master/Core/M5%20Core%20Detailed%20Comparison.xlsx)。*

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_table/core_comparison/core_main_comparison_04_ja.png">

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_table/core_comparison/core_main_comparison_05_ja.png">

## パッケージ内容

- 1x M5Stick including 80mAh-Battery
- 1x Type-C USB Cable

**GRAY (MPU9250有り):**
- アクセサリ: `WATCH BELT`、`WALL`、 `BRICK`

<img src="assets/img/product_pics/core/minicore/m5stick/m5stick_07.png" width=40% height=40%>
<img src="assets/img/product_pics/core/minicore/m5stick/m5stick_08.png" width=40% height=40%>

## 回路図

<img src="assets/img/product_pics/core/minicore/m5stick/m5stick_sch.png" width="500" height="500">

完全な回路図は[こちら](https://github.com/m5stack/M5-Schematic/tree/master/Core/m5stick)から。

## 関連リンク

- **データシート**
  - [ESP32](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_cn.pdf)
  - [MPU9250](https://www.invensense.com/wp-content/uploads/2015/02/PS-MPU-9250A-01-v1.1.pdf)

## サンプルコード

### 1. Arduino
  - [M5Stick Factory Test](https://github.com/m5stack/M5Stack/tree/master/examples/Stick/FactoryTest)
  - [M5Stick Watch](https://github.com/m5stack/StickWatch)

<video width="500" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201901/M5Stick%20Watch.mp4" type="video/mp4">
</video>

### 2. UIFlow

  - [White square game](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Core/M5Stick/UIFlow)

## 関連動画

- **M5Stick デモ - エアコンのリモコン制御**

<video width="500" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201901/M5Stick%20controll%20AC.mp4" type="video/mp4">
</video>

- **m5stick ケース - .OBJモデルビューワー**

<video width="500" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201903/Obj%20Model%20Viewer.mp4" type="video/mp4">
</video>