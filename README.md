# mypkg2
This is a ROS pkg repository.  
***
ロボットシステム学　ROSパッケージ  
上田先生が授業で作成していただいたものを利用させていただきました。  
***
## 実行までの流れ  
`$ cd ~/catkin_ws/src`  
`$ git clone git@github.com:ryosukehayashi3/mypkg2.git`  
`$ cd ..`  
`$ catkin_make` 

1つ目の端末で  
`$ roscore`  
2つ目の端末で  
`$ rosrun mypkg2 count.py`  
3つ目の端末で  
`$ rosrun mypkg2 twice.py`  
4つ目の端末で  
`$ rostopic echo /twice`  
このようにそれぞれ実行していく  
rosrunをする際は`$ chmod +x ファイル名`としてからrosrunするようにしてください。
***
## 実行した動画
https://www.youtube.com/watch?v=WAhh1Q1Mjp4  
***
## ライセンス
[BSD 3-Clause License](https://github.com/ryosukehayashi3/mypkg2/blob/main/LICENSE)

