# ROS/src's Backup

Overview
![ROS melodicと俺](https://github.com/yuki414/src_bck/blob/master/pic/title.png)

## Description
ROSの/catkin_ws/srcを管理するよう。  
特に新しいパッケージをビルド後、catkin_makeが通らなくなったらバックアップをするとよい。  
また安定しているときは新しいパッケージをインストールするまえにpushしてほしい。

## History
以下を参考にブランチをバックアップすればよい。  
commit name：内容の順に説明  

delete origin file:  
初代安定バージョン。しかしmy_robot程度しか入ってないので本当に何も通らなくなったら戻すのもあり。

stable version by tutorial of (7)re:  
安定バージョン。src内にgazebo_ros_pkgsを入れるという2代目ubuntuを殺した原因をしても動いたバージョン。
