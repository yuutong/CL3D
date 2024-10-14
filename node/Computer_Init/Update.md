现有装机环境是在已有3D软件的情况下进行安装，有细碎步骤需要操作，具体如下：

1.	将含有安装包文件的U盘插到控制器上。

2.	控制器通电开机后按键盘`【WIN】`键，选择左侧边栏的文件夹。

3.  升级包名称为CL3DUpdatePack + 日期 + `.tar.gz` ，该文件夹下两个文件夹 `baselib` 和 `CLVision`。`baselib`文件夹内包含了软件的基础库文件。`CLVision`文件里包含了`toollib`、`cameralib`、`commlib`以及`CLVision`可执行程序。

4.	将U盘中的升级压缩包文件复制到`【/home】`路径下，然后在/home路径下解压。

5.	进入到解压后的文件夹，将`baselib`文件夹放入到 `【/home/usr/local/lib】`路径下，合并和替换。
    将`toollib`、`cameralib`、`commlib`以及`CLVision`可执行文件 放到`【/home/CLVision】`路径下，合并和替换。
    
6.  在终端进入`【/home】`路径，`【./copy_3D.sh】`运行脚本进行环境文件复制
    具体操作： 按下组合键`shift + alt + T` 打开`clTerminal`可执行程序打开终端，在`New Command` 中输入`.gnome-terminal` 打开终端，在终端输入以下命令：

```shell
cd /home/
./copy_3D.sh
```

7.	完成升级。





