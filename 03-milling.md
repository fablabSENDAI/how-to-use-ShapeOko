---
layout: default
title: 03.加工
nav_order: 4
---

# 03.加工
<br><br>

<img src="assets/04-1.jpg" width="640" alt="hi" class="inline"/><br>
<br>

ShapeOkoの電源ケーブルをコンセントに挿す。<br>
すると、下図のように黄色いモジュール内の緑色のライトが点灯する。<br>
これはShapeOko本体の電源を入れるだけで、<br>
スピンドル（ドリル部分）の電源は別に入れる必要がある。<br>
<br>
<br>
<br>

<img src="assets/04-2.jpg" width="320" alt="hi" class="inline"/> <img src="assets/04-3.jpg" width="240" alt="hi" class="inline"/><br>
<br>

ShapeOkoをパソコンに接続し、Portを指定。<br>
**Baud**を **9600** に設定したら**「Open」**をクリックする。<br>
<br>
<br>
<br>

<img src="assets/04-4.jpg" width="640" alt="hi" class="inline"/><br>
<br>

※小野寺のパソコンでは上のようなエラーが表示されたので、ターミナルで下記のコマンドを入力しました。<br>

***
$ sudo mkdir /var/lock

$ sudo chmod 777 /var/lock
***
<br>
<br>
<br>

<img src="assets/04-5.jpg" width="640" alt="hi" class="inline"/><br>
<br>

File Modeタブの「Browse」から、加工に使用するGコードデータ（.nc形式）を開く。<br>
<br>
<br>
<br>

<img src="assets/04-6.jpg" width="320" alt="hi" class="inline"/> <img src="assets/04-7.jpg" width="320" alt="hi" class="inline"/><br>
<br>

Machine Controlタブを開くと、エンドミルの位置を操作するパネルが表示される。<br>
X,Yのボタンを押し、下記の写真の位置を参考にしてShapeOkoのヘッドを移動させる。<br>
**「Reset Zero」**をクリックすると、移動させた位置が原点となる。<br>
（もしくは、Connectionを一度Closeし、再度Openしなおしても原点を設定することができる。）<br>
<br>
<br>
<br>

<img src="assets/04-8.jpg" width="640" alt="hi" class="inline"/><br>
<br>

エンドミルのカバーを取り付ける。<br>
<br>
<br>
<br>

<img src="assets/04-9.jpg" width="640" alt="hi" class="inline"/><br>
<br>

File Modeタブの**「Visualuze」**をクリックし、エンドミルのプロセスを表示させる。<br>
<br>
<br>
<br>

<img src="assets/04-10.jpg" width="640" alt="hi" class="inline"/><br>
<br>

ヘッド上部の緑色のスイッチを押し、エンドミルの電源を入れる。<br>
<br>
<br>
<br>

<img src="assets/04-11.jpg" width="320" alt="hi" class="inline"/> <img src="assets/04-12.jpg" width="240" alt="hi" class="inline"/><br>
<br>

File Modeタブの「Send」を押し、加工を開始する。<br>
<br>
<br>
<br>

<img src="assets/04-13.jpg" width="480" alt="hi" class="inline"/><br>
<br>

加工が完了すると、経過時間が表示される。<br>
加工後は、ヘッドの緑色のスイッチを押し、エンドミルの電源を切る。<br>
<br>
<br>
<br>


<img src="assets/04-14.jpg" width="640" alt="hi" class="inline"/><br>
<br>

完成！<br>
<br>
<br>
<br>
<br>
<br>
<br>
