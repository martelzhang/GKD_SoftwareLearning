# GKD_SoftwareLearning

## 安装Linux
+ 安装Ubuntu22.04，可以去bilibili搜索教程。***建议安装物理双系统，不要使用虚拟机***

## 科学上网
+ 安装配置科学上网软件，需要能正常访问使用 [Google](https://google.com/)、[ChatGPT](https://chat.openai.com/)、[Github](https://github.com) 等网络服务
+ 更换你的搜索引擎，***不要使用Baidu！会很影响你的搜索效率！！！*** 建议使用Bing、Google
+ 不会的内容可以先[ChatGPT](https://chat.openai.com/)，但不要完全相信
+ 注册[Github](https://github.com)，请仔细阅读[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)跟[别像弱智一样提问](https://github.com/tangx/Stop-Ask-Questions-The-Stupid-Ways/blob/master/README.md)
+ [这里是我们的代码仓库](https://github.com/zzLinus/NeoRMControl_OneForALL)，记得给我们一个star，这可以让你们更快找到我们的仓库（求你了，给个star吧）

## 配置环境
+ 强烈建议使用VSCode、Clion作为你们的开发环境
+ 安装配置git、ssh、gcc、cmake

当你配置完这些后，就可以编译我们的代码了！

+ 首先打开Terminal
+ 你可以选择在home目录创建一个文件夹作为你的工作空间（当然也可以是任何你想的位置）
```
mkdir ~/GKD_WorkSpace
```
+ 进入工作空间文件夹
```
cd ~/GKD_WorkSpace
```
+ 接着，你可以使用ssh来clone我们的仓库到本地
```
git clone git@github.com:zzLinus/NeoRMControl_OneForALL.git
```
+ 进入本地代码仓库
```
cd NeoRMControl_OneForALL
```
+ 创建一个文件夹用来存放我们编译出来的文件，并进入这个文件夹
```
mkdir build && cd build
```
+ 在此文件夹内执行编译指令
```
cmake .. && make -j8
```
+ 如果顺利的话，你可以得到
