# trajectory_maker
マイクロマウスハーフ競技用のターン軌跡を弧長パラメータ付けした曲率で生成します。
スリップ角を考慮したシミュレーションにも対応しています。

![スクリーンショット](./image/traj_img.png)

## 動かし方

### binder
binderというjupyter notebookのホスティングサービスを利用  


以下のアドレスに飛び、
    
    https://mybinder.org/

GitHub repository name or URLに以下を入力しlaunchを起動
    
    GanonKuppa/trajectory_maker

ブラウザ上でjupyter notebookが立ち上がるのでtrajectory_HF_mouse_slip_angle.ipynbを起動

ココから起動した方が楽かも  

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/GanonKuppa/trajectory_maker/master)



### ローカル環境
以下を実行し、プログラム一式を落としてjupyter noteを起動し、trajectory_maker.ipynbを選択

    git clone https://github.com/GanonKuppa/trajectory_maker
    jupyter notebook


## ツールの概要と動作原理
ツールの概要と動作原理についてはREADME.ipynbを参照してください。


## マイクロマウスのターン
もともと、trajectory_makerはマイクロマウス競技用のターン軌跡を作成することを目的としています。
90度、180度、135度、45度、斜め90度のターンをnotebookのセル毎に生成します。

<img width="465" alt="CL_img" src="https://user-images.githubusercontent.com/24890940/60568647-5bb27780-9da8-11e9-9079-78902240b418.png">


## スリップ角
スリップ角はcp_coefというパラメータの大小で滑りやすさが変わります。値が大きい程スリップしにくくなります。
目安としては80～500くらいの値をセットしてください。


