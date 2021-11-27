<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>　
# QGIS向け：　今昔マップのXYZ-TilesのXMLデータ・データセット （2021.11.26改訂）

## 概　 要    
QGISへXYZ-TilesのAPIを使って，今昔マップの旧版地形図を表示させるためxmlデータセットです．
このxmlファイルを使うと一括登録ができます．  

本データセットは2021年9月11日現在の『[今昔マップ on the web](http://ktgis.net/kjmapw/tilemapservice.html   "今昔マップ on the web")』[1]で公開されている地域を収録しています．

<img src="image.png" width="1000px"> 



## データセット概要     
+ **データ形式**：　xml 
+ **構成**：　「今昔マップXYZ_tile全国版v20210429_1」フォルダの配下にあるxmlに，それぞれの地域のタイルマップが格納されています．

## 利用方法

1. ダウンロードは画面右上の「code」のボタンを押すとzip形式で本リポジトリ内のドキュメントが全てダウンロードされます．
1. zipを解凍すると「今昔マップXYZ_tile全国版v20210429_1」フォルダ内のxmlファイルを取得できます．
1. QGISを立ち上げ，「XYZ_tile」>「接続をロード」からお好みのxmlファイルを読み込んでください．

## 簡単なチュートリアル  
noteの以下の記事を御覧ください．  
https://note.com/smatsu/n/ne3f862f37401?magazine_key=m3a14836a1e82


## 引用 

1. 谷謙二: 時系列地形図閲覧サイト「今昔マップ on the web」  
 http://ktgis.net/kjmapw/index.html  


## ライセンス（著作権について）
* このデータセットはクリエイティブ・コモンズの[**CC BY-NC-SA 4.0**（表示 - 非営利 - 継承 4.0 国際）](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)の下に提供されています．

　　　　　<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

* CC BY-NC-SA 4.0条件であれば連絡は不要ですが，出版などの商用・営利目的で利用されたい場合には連絡をお願いいたします．  

## コンタクト先
動作確認などに不具合が認められる場合，商用・営利目的での利用は「コンタクト先」でご連絡をいただければ幸いです．  
japan.road.jp@gmail.com （国道愛好家　くにみち宛）
  
## 履歴
2021.11.26　岩手県南追加   
2021.09.12　近江・室蘭追加   
2021.04.29　東予・庄内追加  
2021.03.02　公開  
