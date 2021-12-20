![](/6.Docs/awtrix.jpg)

# Awtrix--多功能桌面像素屏

**官网地址：** https://awtrixdocs.blueforcer.de/#/en-en/README  

**官网GIT：** https://github.com/awtrix/AWTRIX2.0-Controller  

**B站教程：** https://www.bilibili.com/video/BV18Y411W7Qt

## 0. 关于本项目

> 一叶知秋君莫笑我注：本项目是德国的一个团队开源做的，硬件方案是基于
`ESP8266-12F`的，乐鑫的一个很实用的MCU芯片。固件及服务器APP开源，大家可以去看看官方网站看看说明，本仓库已经全部fork。

## 1. 硬件打样说明

**PCB打样的话暂时没发现有啥需要特别注意的。** PCB文件可以直接拿去工厂，免费打样，器件BOM的话也都是比较常用的，整板成本在30元以内。

> 自己画了一个conneter PCB, 大概画了10分钟左右，所以我称这一版为叙利亚战损版，有很多细节没有注意到，大家可以优化一下。

**外壳加工** `3D Model`文件夹外壳尺寸大小350MM × 110MM，参考B站UP主：`三三三三三文啊`。
> B站视频中的外壳尺寸为153MM × 46MM。

## 2. 固件编译说明

固件框架主要基于Arduino开发完成，玩过Arduino的基本没有上手难度了，基于PlatformIO，直接编译`Firmware`即可。

> 我使用的是VSCode上面的PlatformIO插件进行Arduino开发，因为对VSCode比较熟悉，大家选择自己喜欢的IDE就好了。

## 3. 服务器运行说明

安装JAVA环境后在CMD中运行如下命令，执行`Host`文件夹的文件，开启服务器。

	java -jar awtrix.jar

## 4. APP开发说明

基于B4J IDE编译(JDK 8) ，大家可以自行研究一下。

## 其他的后续再补充，有用的话记得点星星~

