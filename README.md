# CR123A PowerSupplyAttachment


<img src="https://github.com/akita11/CR123A_PowerSupplyAttachment/blob/main/CR123A_PowerSupplyAttachment.jpg" width="240px">

IoT機器等でよく使われるリチウム電池CR123Aの形状の筐体に電極がついた部品です。
CR123Aの代わりに機器に装着し、ACアダプタなどから+3Vを給電して機器を動作させることができます。

SwitchBotスマートロックなど動作時に消費電流が大きなものはACアダプタからの給電能力が不足してリセットがかかる場合があります。そのような場合の電源補強のための、市販の100uF程度の直径6.3mm・高さ5mmの電解コンデンサ（[秋月電子で扱っている16MH5100MEFC6.3X5](https://akizukidenshi.com/catalog/g/g105002/)など）をとりつける場所もあります


## 用意するもの

- +3V/+3.3Vの電源（ACアダプタ）など
- 電源と本機を接続するケーブル（＋・ーの2本） 

※+3V/+3.3V以外の電圧を加えると、装着機器が破損する場合がありますので、電圧にご注意ください。

## 組み立て

<img src="https://github.com/akita11/CR123A_PowerSupplyAttachment/blob/main/CR123A_PowerSupplyAttachment_parts.jpg" width="240px">

以上の部品を使い、以下のように組み立てていきます。

まず(5)（圧着金具（プラス用））に、電源のプラス側と接続するケーブルを固定します（圧着を推奨）。
続いて、(6)（圧着金具（マイナス用））に、電源のマイナス側と接続するケーブルを固定します（圧着を推奨）。

<img src="https://github.com/akita11/CR123A_PowerSupplyAttachment/blob/main/CR123A_PowerSupplyAttachment_step1.jpg" width="240px">

<img src="https://github.com/akita11/CR123A_PowerSupplyAttachment/blob/main/CR123A_PowerSupplyAttachment_step1b.jpg" width="240px">

(5)と(3)（プラス極用ナット）を、筐体(7)のプラス極側（穴がすりばち状になっていない方）にさしこみ、(1)（プラス極用ねじ）で固定します。

<img src="https://github.com/akita11/CR123A_PowerSupplyAttachment/blob/main/CR123A_PowerSupplyAttachment_step2.jpg" width="240px">

(6)と(4)（マイナス極用ナット）を、マイナス極側（穴がすりばち状になってる方）にさしこみ、(2)（マイナス極用ねじ）で固定します。

その後、両極の金具を、筐体にあわせて折り曲げます。

<img src="https://github.com/akita11/CR123A_PowerSupplyAttachment/blob/main/CR123A_PowerSupplyAttachment_cap.jpg" width="240px">

なお機器の動作が不安定な場合は、機器の動作に伴う電源電圧の変動が原因の場合があります。市販の100uF程度の電解コンデンサをプラス・マイナス間に接続することで改善される場合があります。直径6.3mm・高さ5mmの電解コンデンサ（[秋月電子で扱っている16MH5100MEFC6.3X5](https://akizukidenshi.com/catalog/g/g105002/)など）であれば、本機の中央部に埋め込むことができます。



## 使い方

対象機器のCR123Aホルダに、本機を装着します。＋／ーを間違えないようにご注意ください。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
