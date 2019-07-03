# trajectory_maker
平面移動ロボット用の軌跡を弧長パラメータ付けした曲率で生成します。

![スクリーンショット](./image/traj_img.png)

## 動かし方

### binder
binderというjupyter notebookのホスティングサービスを利用  


以下のアドレスに飛び、
    
    https://mybinder.org/

GitHub repository name or URLに以下を入力しlaunchを起動
    
    GanonKuppa/trajectory_maker

ブラウザ上でjupyter notebookが立ち上がるのでtrajectory_maker.ipynbを起動  

ココから起動した方が楽かも  

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/GanonKuppa/trajectory_maker/master)




### google colab
以下のアドレスを実行
https://colab.research.google.com/github/GanonKuppa/trajectory_maker/blob/master/trajectory_maker_for_colab.ipynb


### ローカル環境
以下を実行し、プログラム一式を落としてjupyter noteを起動し、trajectory_maker.ipynbを選択

    git clone https://github.com/GanonKuppa/trajectory_maker
    jupyter notebook


## ツールの概要と動作原理
ツールの概要と動作原理についてはREADME.ipynbを参照してください。


## マイクロマウス用のプログラム
もともと、trajectory_makerはマイクロマウス競技用の軌跡を作成することを目的としています。
マイクロマウス用の軌跡を作成したいときは以下のノートブックを使用して下さい。
    
    - trajectory_CL_mouse.ipynb (クラシック用)
    - trajectory_HF_mouse.ipynb (ハーフ用)

ココから上記のnotebookを起動するのが手っ取り早いです。
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/GanonKuppa/trajectory_maker/master)

<img width="465" alt="CL_img" src="https://user-images.githubusercontent.com/24890940/60568647-5bb27780-9da8-11e9-9079-78902240b418.png">



