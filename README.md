# robosys_kadai2
ロボットシステム学の課題2です. 

# 環境
Ubuntu 20.04 LTS  
ros noetic  

# 実行手順
## インストール・準備
`mkdir -p catkin_ws/src` でワークスペースの準備をする.  
`git clone 

##実行
1 `roscore`でrosを立ち上げる.  
2 `rosrun mypkg count.py`でパブリッシャを立ち上げる.   
3 `rosrun mypkg twice.py`でサブスクライバを立ち上げる. 
4 `rosnode list`, `rostopic list`で動いているか確認する. 
5 `rostopic echo /twice`で表示される. 

## 終了方法
Ctrl + c で終了
