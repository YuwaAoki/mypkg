# mypkg  
ロボットシステム学課題

# 概要  
0.1秒で2ずつ増える数値を端末に出力するROSパッケージ。  

# デモ  
https://youtu.be/BT6Ng314DvM  

# 使い方  
`git clone https://github.com/YuwaAoki/mypkg.git`  

端末を3つ用意し、それぞれの端末で以下のコマンド  
`cd scripts`  

端末1で  
`rosrun mypkg count.py`  

端末2で  
`rosrun mypkg twice.py`  

端末3で  
`rostopic echo /twice`  

# ライセンス  
BSD-2-Clause License  

# 著作者  
Copyright (C) 2021 Ryuichi Ueda. All rights reserved.
