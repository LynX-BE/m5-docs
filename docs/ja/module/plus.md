# PLUS モジュール {docsify-ignore-all}

<img src="assets/img/product_pics/module/module_plus_01.png" width="30%" height="30%"> <img src="assets/img/product_pics/module/module_plus_02.png" width="30%" height="30%">

***

:memo:**[概要](#概要)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:octocat:**[サンプルコード](#サンプルコード)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:electric_plug:**[回路図](#回路図)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🛒**[購入リンク](https://www.aliexpress.com/store/product/M5Stack-New-Arrival-PLUS-Module-Encoder-Module-with-MEGA328P-500mAh-Battery-ISP-IR-Transmitter-UART-GPIO/3226069_32949278724.html?spm=a2g1x.12024536.productList_5885013.pic_1)**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:clapper:**[関連動画](#関連動画)**

## 概要

**<mark>PLUS</mark>**モジュールは500mAhのバッテリ、ロータリエンコーダ、IR送信機、PORT B(GPIO)、PORT C(UART)そしてマイクジャックの為のパッドを備えています。M5Stackの下に重ねるだけで、機能を強化することが出来ます。M5Stackとの通信にはI2Cを使用します。I2Cアドレスは **<mark>0x89</mark>**です。

## 特徴

- 500mAh バッテリー
- プログラマブルロータリエンコーダ
- IR送信機
- PORT B (GPIO)
- PORT C (UART)

## パッケージ内容

- 1x PLUS モジュール

## 関連リンク

- **[公式ビデオ](https://www.youtube.com/channel/UCozgFVglWYQXbvTmGyS739w)**

- **[フォーラム](http://forum.m5stack.com/)**

- **[モジュール内のMEGA328ファームウェア](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Module/PLUS/firmware_328p)**

## サンプルコード

### 1. Arduino IDE

*完全なソースコードは[こちら](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Module/PLUS/Arduino)`plus_read_encoder.ino`。*

```clike
/*
* ギアポテンショメータのデータを読む
* 赤外線ライト
*/
#include <Arduino.h>
#include <M5Stack.h>

#define IrPin 13
#define PLUS_ADDR 0x62

// declaration
int32_t number = 0;
uint8_t press = 0;

// initialization
M5.begin(true, false, false);
Wire.begin();
ledcSetup(1, 38000, 10); ledcAttachPin(IrPin, 1);// IR Pin setting

// read data
Wire.requestFrom(PLUS_ADDR, 2);
while(Wire.available()) {
    int8_t encode = Wire.read();
    uint8_t press_n = Wire.read();
    number += encode;
    if(press_n == 0xff) {
        press = 0;//encoder was pressed
    }
    else {
        press = 1;//encoder was releaed
    }
}
```

## 回路図

<img src="assets/img/product_pics/module/plus_sch.png">

## 関連動画

**PLUS デモ - ツリーメニューの操作**

<video width="500" height="315" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201812/M5Stack%20Encoder.mp4" type="video/mp4">
</video>