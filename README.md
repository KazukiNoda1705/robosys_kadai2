# robosys_kadai2
ロボットシステム学の課題2です.  
n + 1 ずつ増えるデータを2倍にして表示するプログラムです. 

# 環境
Ubuntu 20.04 LTS  
ros noetic  

# 実行手順
## インストール・準備
`mkdir -p catkin_ws/src` でワークスペースの準備をする.  
`git clone https://github.com/KazukiNoda1705/robosys_kadai2.git` でsrcのフォルダにクローンする.  
`cd ..`で１つ上のディレクトリに戻る.  
`catkin_make`

## 実行
1 `roscore`でrosを立ち上げる.　＜端末１＞  
2 `rosrun mypkg count.py`でパブリッシャを立ち上げる.　＜端末２＞   
3 `rosrun mypkg twice.py`でサブスクライバを立ち上げる.　＜端末３＞  
4 `rostopic echo /twice`で表示される.　＜端末４＞  

## 終了方法
Ctrl + c で終了

# 映像
[youtube](https://youtu.be/95Y3kBO6yjE)
