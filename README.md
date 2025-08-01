# cool642tb

![](img/img00019.jpg)

## What is cool642tb?

cool642tb is ortholiner keyboard with trackball.
<br>
cool642tb is splite keyboards.
<br>
cool642tb use seeed xiao ble,run zmk_firmware.
<br>
<br>

## firmware

[zmk-config](https://github.com/telzo2000/zmk-config-cool642tb)

<br>
keymap editor

https://nickcoutsos.github.io/keymap-editor/

<br>
zmk studio

https://zmk.studio/

<br>

自作キーボードへのzmk_firmwareのインストールについて

https://sizu.me/m_ki/posts/kvixkn2mec6a

<br>
zmk_firmwareでのキーマップ編集について

https://sizu.me/m_ki/posts/m3devs7be5km

<br>

## buildguide

https://github.com/telzo2000/cool642tb/blob/main/buildguide_for_cool642tb.md

※cool642tbとcool642tb_r2共通になります。

<br>
ボールベアリング採用のトラックボールについて

https://sizu.me/m_ki/posts/67xa3f8r2544

<br>

キーが反応しないときは（cool642tb用）

https://sizu.me/m_ki/posts/hmiznwmr0uhh

<br>

トラックボールが反応しない時のチェックリスト的なもの

https://sizu.me/m_ki/posts/w1ac1xtt9ds1

<br>

## BOM

<b>common parts</b>
| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|番号|名前|数|備考|調達先|参考価格（送料込）|<br>
|1|PCB|3|Rightside,Leftside,<br>Trackball|[elecrow](https://www.elecrow.com)<br>[JLCPCB](https://jlcpcb.com)<br>[ALLPCB](https://www.allpcb.com)||<br>
|2|Switch plate|2|3D Print|||
|3|Bottom plate|2|3D Print|||
|4|Ball case|1|3D Print|||
|5|pinheader<br>ピンヘッダ|1|7pin,L字形<br>コンスルーでも可|[秋月電子](https://akizukidenshi.com/catalog/g/g101627/)<br>[モノタロウ](https://www.monotaro.com/p/4372/1914/?srsltid=AfmBOooNFXhsyVNPPtl8VZ9vMxbrLr2A5btmrf5l_N4rMR9fy4N_bydG)<br>[マルツオンライン](https://www.marutsu.co.jp/pc/i/106993/)||
|6|Slide switch<br>スライドスイッチ|2||[秋月電子](https://akizukidenshi.com/catalog/g/g115370/)|１個30円|
|7a|AAAA Battery case<br>単４電池ケース|2|cool642tb用|[マルツオンライン](https://www.marutsu.co.jp/pc/i/59151/?srsltid=AfmBOoo5ctOn9kOUGJA7pCL4M2f4Y3IolfSweL7epFytDI-BLKNBKMa8)|１個81円|
|7b|AAAA Battery case<br>単４電池ケース|4|cool64tb_r2用|[秋月電子](https://akizukidenshi.com/catalog/g/g102670/)|１個40円|
|8|XIAO nRF52840|2|MCU Board|[seeed studio](https://jp.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html?msclkid=5541f7f3d0f911eca6023fe520de5bfa)<br>[秋月電子](https://akizukidenshi.com/catalog/g/g117341/)|1940円|
|9|Trackball<br>トラックボール|1|25mm級|[Amazon](https://www.amazon.co.jp/dp/B0D4DYH8XY?ref=ppx_yo2ov_dt_b_fed_asin_title)等|1300円ほど|
|10|PMW3610|1|Trackball senser|[アリエク](https://ja.aliexpress.com/item/1005007622547772.html?spm=a2g0o.order_list.order_list_main.45.72e8585aVqU7cH&gatewayAdapt=glo2jpn)|1000円ぐらい|
|11|Rotery Encoder<br>ロータリーエンコーダー|1|EC12互換|[遊舎工房](https://shop.yushakobo.jp/products/3762?variant=42672275226855)|１個330円ぐらい|
|12|Knob<br>ロータリーエンコーダー用ノブ|1|直径19mm以下のもの|||


<br>

<b>If you use choc switch...</b>
| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|13|Diode<br>ダイオード|42|SMD|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|100個で220円程度から|
|14|Swith socket<br>スイッチソケット|42|choc|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|10個で165円程度|
|15|Screw<br>ネジ|8|スリムヘッドM2 5mm|[遊舎工房](https://shop.yushakobo.jp/products/a0800s2?variant=37665432535201)|50本880円(遊舎工房)|
|16|Screw<br>ネジ|4|M2 4mm|DIY shop|10本200円程度|
|17|Screw<br>ネジ|8|M2 3mm|DIY shop|10本200円程度|
|18|Spacer<br>スペーサー|10|M2 3mm|DIY shop|10本400円程度|
|19|Keyswitch<br>キースイッチ|42|chocV1及びV2対応|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)|１個100程度|
|20|Keycap<br>キーキャップ|42|1U、ロープロが最適|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)||

<br>

<b>If you use cherryMX switch...</b>
| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|13|Diode<br>ダイオード|42|SMDまたはリードタイプ|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|100個で220円程度から|
|14|Swith socket<br>スイッチソケット|42|cherry MX|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|10個で165円程度|
|15|Screw<br>ネジ|8|M2 8mm|DIY shop|10本200円程度|
|16|Screw<br>ネジ|4|M2 4mm|DIY shop|10本200円程度|
|17|Screw<br>ネジ|8|M2 3mm|DIY shop|10本200円程度|
|18|Spacer<br>スペーサー|18|M2 3mm|DIY shop|10本400円程度|
|19|Keyswitch<br>キースイッチ|42|cherry MX|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)|１個100程度|
|20|Keycap<br>キーキャップ|42|1U|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)||

<br>


In addition, NiHM rechargeable batteries (4 AAA size), USB cable, etc. are required.
<br>
この他に、NiHM充電池（単４形４本）、USBケーブル等が必要です。
<br>

<br>



# license

[CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)

![](img/by-nc-sa.png)

![](img/img00020.jpg)
