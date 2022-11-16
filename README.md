# LoopMod

nea氏(https://github.com/nea-c)の開発したLoopスクリプトを個人的に使いやすくするべく改造しました。 

素敵なスクリプトを開発してくださったnea氏に感謝を。 

元ソース:https://github.com/nea-c/AviUtl-Scripts/tree/master/Loop  

個人利用用途で開発したのでソースコードグダグダです。すまん…  

## 軽い使い方とか

詳しい使い方は本家のREADMEを参考にしたほうがいいと思います  

とりあえずすべてデフォルトで動かす場合は、"MainDraw"エフェクトをかけてください  

後述のオプション指定エフェクトを使わなかったパラメータにおいては、ダイアログ内部の値が使われます  

### Option_loopNum
x方向, y方向, z方向のループする個数を指定します

### Option_Interval
x方向, y方向, z方向において各オブジェクトのループ間隔を指定します

### Option_Offset
x方向, y方向, z方向のループ時のズレを指定します

### Option_Alignment
x方向, y方向, z方向の開始位置を指定します
`(1)無効 (2)1列目で中央揃え (3)全体で中央揃え` です

### Option_Mirror
x方向, y方向, z方向を反転させるかどうかを指定します