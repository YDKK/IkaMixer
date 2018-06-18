# IkaMixer
Audio Mixer Board for Nintendo Switch

Nintendo Switchの音声出力と，PCやスマートフォンなどの（ボイスチャットの）音声出力を同時に聞くことを可能にする，オペアンプを用いたオーディオミキサ基板です．  
4極のマイク付きヘッドセットの接続に対応し，マイクのミュートスイッチを有します．


![Figure1](https://raw.githubusercontent.com/YDKK/IkaMixer/master/figure/figure1.jpg)
![Figure2](https://raw.githubusercontent.com/YDKK/IkaMixer/master/figure/figure2.jpg)
![Diagram](https://raw.githubusercontent.com/YDKK/IkaMixer/master/figure/circuit_diagram.png)

# Parts List
|No.|秋月コード|Name|　Price　|Num|
|-|-|-|-:|-|
|IC1|I-01628|電圧ｺﾝﾊﾞｰﾀ LTC1144CN8　※オペアンプ負電源用|400円|1|
|IC2|I-00068|2回路入HiFiｵﾍﾟｱﾝﾌﾟ NJM2114DD|100円|1|
||P-00035|丸ﾋﾟﾝICｿｹｯﾄ (8P)<br>※必要であれば|15円|2|
|J1|K-05258|ﾌﾞﾚｯﾄﾞﾎﾞｰﾄﾞ用ﾐﾆBﾒｽUSBｺﾈｸﾀDIP化ｷｯﾄ|200円|1|
|J4|C-06070|3.5mm4極ﾐﾆｼﾞｬｯｸ 基板取付用 MJ-4PP-9|50円|1|
|C1~C8|P-04624|ｵｰﾃﾞｨｵ用無極性電解ｺﾝﾃﾞﾝｻｰ10μF25V85℃ ﾆﾁｺﾝMUSE･ES|15円|8|
|C9|P-08424|電解ｺﾝﾃﾞﾝｻｰ 1000μF10V105℃(ﾙﾋﾞｺﾝWXA)<br>※電源用パスコン，無くても可|20円|1|
|R1~R6|R-03406|金属皮膜抵抗 1/4W20kΩ (100本入)|300円|1|
||3.5mmΦｽﾃﾚｵﾐﾆﾌﾟﾗｸﾞ×1<br>3.5mm4極ﾐﾆﾌﾟﾗｸﾞ×1<br>お好きなものを<br>http://akizukidenshi.com/catalog/c/c35plug/|||1+1|
||ﾌﾟﾗｸﾞ用電線(3極+4極で7本必要になる)<br>P-11640 or P-10672あたりが良いのかな||
||P-06790など|熱収縮ﾁｭｰﾌﾞ　※ミニプラグ用　必要であれば||
|S1||お好きなｽﾗｲﾄﾞorﾄｸﾞﾙｽｲｯﾁ<br>ﾏｲｸﾐｭｰﾄ切り替え用<br>※不要であればS1をはんだブリッジ<br>ﾊﾟﾀｰﾝはP-08791用だけど,普通の3Pｽｲｯﾁならちょっと足を曲げれば大抵使える||1|
