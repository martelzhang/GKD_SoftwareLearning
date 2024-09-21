## 这里会教你如何编译运行我们的仓库
首先进入我们的工作空间
```
cd ~/GKD_WorkSpace
```
接着，你可以使用ssh来clone我们的仓库到本地
```
git clone git@github.com:zzLinus/NeoRMControl_OneForALL.git
```
进入本地代码仓库
```
cd NeoRMControl_OneForALL
```
创建一个文件夹用来存放我们编译出来的文件，并进入这个文件夹
```
mkdir build && cd build
```
在此文件夹内执行编译指令
```
cmake .. && make -j8
```
使用命令查看当前文件夹下的

