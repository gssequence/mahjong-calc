# 使用方法

手牌を入力すると、待ち牌や点数を確認することができます。麻雀を打っていて点数計算が分からなくなったときはもちろん、点数計算のトレーニングやメンチンの待ち牌の確認などにも活用できます。

## ルール設定

<img src="https://user-images.githubusercontent.com/7447366/106902025-b279f300-673b-11eb-9a6c-9a09a88466a7.png" width="428" alt="Rule Configuration" />

最初に下部までスクロールして、ルールを設定します。

### 数え役満

- `オフ`: 飜数が 13 以上でも役満にならず、三倍満となります。
- `13 飜以上`: 飜数が 13 以上の際は役満となります。

### 役満の複合

- `オフ`: 役満が複合しません。ダブル役満がシングル役満扱いとなります。
- `オン`: 役満が複合します。

### 切り上げ満貫

- `オフ`: 基本点が 1920 点 (30 符 4 飜 や 60 符 3 飜) の場合でも、点数をそのまま計算します。
- `基本点 1920 点`: 基本点が 1920 点の場合、基本点を 2000 点に切り上げて満貫とします。

### 連風牌の雀頭

- `2 符`: 連風牌 (ダブ東やダブ南) の雀頭を 2 符として計算します。
- `4 符`: 連風牌の雀頭を 4 符として計算します。

### 国士無双十三面待ち・四暗刻単騎待ち・大四喜・純正九蓮宝燈

それぞれの特殊な形の役満について、設定します。

- `役満`: 役満扱いとします。
- `ダブル役満`: ダブル役満扱いとします。

## 場の設定

<img src="https://user-images.githubusercontent.com/7447366/106902250-f4a33480-673b-11eb-8217-8930b1e088ba.png" width="428" alt="Table Configuration" />

局に関する設定を行います。

### 場風

場風を設定します。ゲーム開始時は通常 `東` です。

### 自風

自風を設定します。親の場合は `東` です。

### 積棒

積棒を設定します。例えば、「東三局一本場」の場合、積棒は 1 です。

### 供託

供託立直棒の本数を設定します。

## 手牌

<img src="https://user-images.githubusercontent.com/7447366/106904711-d985f400-673e-11eb-9a80-024169a413be.png" width="428" alt="Hand" />

手牌を設定します。

パレットの牌をタップすると、フォーカス (青色の枠) エリアに牌を入力することができます。入力された牌をタップすると、牌を消去することができます。

### ポン・チー・明槓・暗槓

`ポン` `チー` `明槓` `暗槓` ボタンをタップすると、フォーカスが副露した牌に移り、副露した牌を入力することができます。チーの場合は、順子の最初の牌を入力します。

入力された牌をタップすると、牌を消去することができます。牌が消去された状態でさらにタップすると、副露を取り消すことができます。

フォーカスは、タップで切り替えることができます。

## 手牌・役の設定

<img src="https://user-images.githubusercontent.com/7447366/106903068-e1449900-673c-11eb-879b-947370f67844.png" width="428" alt="Hand Configuration" />

手牌の状況の設定を行います。

### ドラ

ドラの枚数を設定します。

### 立直

立直の状態を設定します。他家の副露が無い状態での 1 巡目立直はダブル立直となります。

### 一発

立直後 1 巡以内に和了した場合、設定します。ルールにより無い場合もあります。

### 嶺上開花

嶺上開花で和了した場合、設定します。

### 槍槓

槍槓で和了した場合、設定します。

### 海底 / 河底

山の最後の牌でツモ和了した場合、または他家の最終打牌でロン和了した場合、設定します。

### 天和 / 地和

親の配牌で和了している場合、または子の第 1 ツモで和了した場合、設定します。

## 結果

牌の入力後、計算結果が表示されます。

### 不聴時

<img src="https://user-images.githubusercontent.com/7447366/106907999-359e4780-6742-11eb-8193-5bbced36e8da.png" width="428" alt="Not Tempai" />

不聴の場合は、向聴数を表示します。七対子や国士無双は特殊な手なので、面子手と併せて表示しています。

### 聴牌時

<img src="https://user-images.githubusercontent.com/7447366/113403289-58b34380-93e1-11eb-83f7-9458985fa2c1.png" width="852" alt="Tempai" />

聴牌の場合は、待ち牌と点数のリストが表示されます。

積棒や供託が設定されている場合、それらによって追加で得られる点数を `(+1600)` のように表示しています。

ツモ和了などで点数申告が複雑になる場合は、点数の下に表示されている `8000 は 8600` などの文をそのまま申告の文言として使用することができます。

リストのアイテムをタップして展開すると、役の内訳などの詳細情報が表示されます。

点差表示は、和了した場合につく点差を表しています。積棒や供託の値によって、点差は変動します。
