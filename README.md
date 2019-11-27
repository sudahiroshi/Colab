# 実習内容

パスワードのハッシュ化について，実際にプログラムを開発して確認する．

すべて読んで作業を勧めてください.

## グループ作成

まず3人グループを作ってください.

原則は3人で１グループですが溢れてしまった人は溢れた人同士でグループを作るか４人グループでも良いものとします.

１人または２人で作業をすることがないようにしてください.

グループが作れなかった方は担当教員まで言いに来てください

## 役割分担

今回はグループ内で役割を決め,その人がある一定の作業している時の責任者となります. 

担当になったものが一人で作業を進めるのではなく,その責任者が中心となって作業を進め他の二人はサポートしてください.

１人目：『構想』　プログラミングをする前にどのように課題を完成させるのか考える

２人目：『プログラミング』　構想を元にプログラミングをしていく

３人目：『検証』　プログラミング後システムがしっかりと動作しているか確認し,問題があれば修正を行う



## 作成課題

【Google colaboratory上で擬似ログインページを作成する】

注意すること　 

①	事前学習で学んだ知識を使って作成する.

②	salt値は実際使うときはユーザーによって違うが今回は同じ値を使う.

③	パスワードをハッシュ化し、そのハッシュ値とsalt値をあわせた値（６＆＋salt +ハッシュ値）を保存しておく.

④	登録したIDとパスワードの一覧が見られるようにする.

⑤	ログインできたかどうかしっかりと表示する.

この注意することを上から順にできるようにしていくと進めやすいです. 

［イメージ図］

登録
ID: 入力欄
Passward:  入力欄
↓
↓
一覧表示
1832000: abcd
1832999: efgh 
↓
↓
ログイン
ID: 入力欄
Passward:  入力欄
↓
↓
ログインできましたorログインできませんでした


### 環境

開発言語 | Python

実行環境 | Google Colaboratory

### 進め方（目次）

1. ハッシュ化の使い方を学習する
2. 辞書型の使い方を学習する
3. その他Pythonの基本など
4. 構想を練る


### 1. ハッシュ化の方法を学習する

[こちら](https://colab.research.google.com/github/uemotota/Colab/blob/master/hash.ipynb)を開いて，Google Colabolatory上でハッシュ化の使い方を学習します．

### 2. 辞書型の使い方を学習する

[こちら](https://colab.research.google.com/github/uemotota/Colab/blob/master/List.ipynb)を開いて，Google Colabolatory上で辞書型の使い方を学習します．

### 3.その他Pythonの基本など

[こちら](https://colab.research.google.com/github/uemotota/Colab/blob/master/List.ipynb)を開いて，Google Colabolatory上で上記以外のPythonの構文を学習します．

基本的にはここまでの内容で作成できます.
これらの説明だけでは足りなかった時の補足[こちら](https://qiita.com/AI_Academy/items/b97b2178b4d10abe0adb)

### 4. 構想を練る　担当『構想』

『構想』を担当する人がメインになって作業を進めてください. 

すぐにプログラミングに移るのではなく，まずはここまでで学んだことを元にどのようにして完成させるのかを考える.


### 5. プログラミング　担当『プログラミング』

『プログラミング』を担当する人がメインになって作業を行ってください.

新しいノートブックを開いて作業を始めてください.

構想を元にプログラミングを行ってください

細かいエラーの修正や不必要な構文の削除などは次の担当に任せる

### 6. 検証　担当『検証』

『検証』を担当する人がメインになって作業を行ってください.

プログラミング後にエラーの修正と不要な部分を消すなどの作業を行う.

正常に動作しているかの確認一覧
ⅰ：複数のIDとパスワードを登録してもエラーにならないか？
ⅱ：正しく一覧が表示できているか
