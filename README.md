# B3課題
***
## 1. 単層パーセプトロンで論理演算orを実装しなさい. ##
### 学習例 ###
```
#!python
(x, y) = (0, 0) : 0
(x, y) = (1, 0) : 1
(x, y) = (0, 1) : 1
(x, y) = (1, 1) : 1
```
### 備考 ###
活性化関数は標準シグモイド関数を使用してください.
### 注意 ###
今回の課題に限らず,ニューラルネットワークを構築する際は,あらゆるパラメータの数を自分で試行錯誤しながら調整していく必要があるため,パラメータ(ニューロンの数やエポック数など)は基本的に決め打ちではなく変数に値を入れるようにしましょう.また,最初なのでchainerなどのライブラリは使わずにフルスクラッチで実装してみましょう.
***
## 2. 単層パーセプトロンで論理演算andを実装しなさい. ##
### 学習例 ###
```
#!python
(x, y) = (0, 0) : 0
(x, y) = (1, 0) : 0
(x, y) = (0, 1) : 0
(x, y) = (1, 1) : 1
```
***
## 3. 単層パーセプトロンでの論理演算xorを実装を試みなさい. ##
### 学習例 ###
```
#!python
(x, y) = (0, 0) : 0
(x, y) = (1, 0) : 1
(x, y) = (0, 1) : 1
(x, y) = (1, 1) : 0
```
### 注意 ###
輪講で話したとおり,単層パーセプトロンでは実現できません.
***
## 4. 多層パーセプトロンで論理演算xorを実装しなさい. ##
### 学習例 ###
```
#!python
(x, y) = (0, 0) : 0
(x, y) = (1, 0) : 1
(x, y) = (0, 1) : 1
(x, y) = (1, 1) : 0
```
### 備考 ###
中間層は1層で,そのニューロン数は5にしてください.
***
## 5. Pythonのプログラムに処理の時間を計測する機能を実装しなさい. ##
### 出力例 ###
```
#!python
elapsed_time:31.4190590382[sec]  
```
***
## 6. 4で作成したプログラムに,エポック毎でロスの値を保持し学習終了時にグラフで可視化する機能を実装しなさい. ##
### 備考 ###
可視化にはmatplotlibなどがオススメです.また,今回のように1エポックが一瞬でおわるようなものは、100エポックや1000エポック単位で処理したほうがいい場合もあります.
***
## 7. (おまけ)4で作成したプログラムの中間層中のニューロン数を100にして,4の場合と処理にかかる時間を比較しなさい. ##
