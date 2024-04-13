---
title: （未完成）全网最全：在你的移动设备/主机上运行Minecraft的基岩/Java/网易基岩/网易Java版
abbrlink: 38481
date: 2024-03-22 19:18:52
tags:
 - Minecraft
 - 配置
---

## 前言

之前遇到许多朋友想玩Minecraft，但是不知道如何入手，甚至不知道应该如何下载游玩，这一篇文章主要就是全面的讲解一下在各个设备运行Minecraft的教程和注意事项。

### 文章准备涉及到的操作系统

Windows10/11（Windows7已经不受支持，无法运行基岩版）：基岩版/Java版/网易双版本
MacOS：Java版
Linux：Java版
IOS：基岩版（使用特殊手段可以运行Java版，本文仅简略介绍）/网易基岩版
Android：基岩版/Java版/网易基岩版

### 基岩版与Java版的区别

简单来说：基岩版最初是为便携设备设计的版本（使用C++），而Java版主要为PC设计（使用Java），两者不互通。但目前便携设备与部分类型PC均可运行双版本。
网易版是中国大陆的代理分发，移动设备仅能运行基岩版，PC可以运行基岩/Java版

## 一.基岩版

通常来说，基岩版不需要环境配置，因此我直接讲解下载方法。

### Windows（10/11）

Windows中的基岩版仅支持正版，所以游玩前必须先进行购买

#### 1.购买

[基岩Java捆绑包（89¥）](https://www.xbox.com/zh-CN/games/store/minecraft-java-bedrock-edition-for-pc/9NXP44L49SHJ/0010)

{% note info::根据目前Microsoft的设置，你必须同时购买双版本才能游玩。%}

#### 2.下载游戏

打开Microsoft Store，登录你购买了游戏的账户，然后搜索“Minecraft”，点击“Minecraft: Java & Bedrock Edition for PC”，点击安装。
![安装界面（如图）](/img/MinecraftPC官方安装.png)

等待安装完成后在“开始”里面找到“Minecraft”，单击启动即可。

### Android（不包括鸿蒙NEXT）

#### 正版

打开手机上的Google Play，在商店内完成购买，下载和启动。

{% note info::并不是所有手机都有Google Play，而且访问Google Play需要魔法。%}

#### 盗版

打开[我的世界国际版全版本下载 (mcapks.net)](https://mcapks.net/)，选择你想要游玩的版本，点击“下载”，然后点击“下载游戏”，选择线路并下载。

### IOS（iPadOS）

#### 方法一（需要$6.99）

注册一个美区apple id，登录账户后进行购买和下载。
[【2024年】注册美国区Apple ID保姆级教程 - Kerry的学习笔记 (kerrynotes.com)](https://kerrynotes.com/register-american-apple-id/)

#### 方法二（使用AppStore特性进行白嫖，不稳定）

打开[苹果软件站 (iios.club)](https://www.iios.club/#/login)，进行注册登录。点击个人中心，去做任务领积分，然后完成任务。等待获得10积分后，回到首页推荐，点击“全部游戏”，搜索“Minecraft”，然后进行兑换。

{% note danger::警告：必须完整阅读教程并答题，严禁在设置中登录网站提供的appleid，否则你的设备可能会被锁定且被勒索。%}



## 二.Java版

Java版是绝大多数设备都能运行的版本，但是在移动设备上操作可能会不方便，推荐在PC上游玩Java版。

### 环境配置（Android/iOS设备无需此操作）

打开[Java下载网站](https://www.java.com/en/download/manual.jsp)，选择对应你系统的版本。
Windows：Windows Online（需要连接网络）
macOS：macOS x64/macOS ARM64
Linux：Linux
完成下载后按照各自操作系统的方式完成安装。

### 选择启动器并启动。

#### Windows

为保证公平性，本文会介绍官方启动器和御三家（HMCL,PCLII,BakaXL）

##### 官方启动器（仅支持正版）

前往Xbox进行购买
[基岩Java捆绑包（89¥）](https://www.xbox.com/zh-CN/games/store/minecraft-java-bedrock-edition-for-pc/9NXP44L49SHJ/0010)

{% note info::根据目前Microsoft的设置，你必须同时购买双版本才能游玩。%}

打开Microsoft Store，登录你购买了游戏的账户，然后搜索“Minecraft”，点击“Minecraft: Java & Bedrock Edition for PC”，点击安装。
![安装界面（如图）](/img/MinecraftPC官方安装.png)

##### 第三方启动器（御三家）

先后顺序无特殊含义，仅仅是笔者的习惯。

###### HMCL

打开[HMCL下载界面](https://hmcl.huangyuhui.net/download/)，选择开发版进行下载

{% note info::特别说明：jar和exe都可运行，不选择稳定版的原因是城通网盘下载速度过慢。下载过程中可能报毒，不必理会，坚持下载即可（这年头报毒的文件太多了吧）%}

下载完成后打开，**阅读用户协议与免责声明**后选择同意，你会看到这样一个界面：
![HMCL主界面](/img/HMCL界面.png)
点击“没有游戏账户”,选择游戏模式并按照提示添加账户
离线模式：也叫盗版模式，不能进入开启正版验证的服务器，不能设置皮肤，不能使用部分联机MOD。
微软账户：拥有Minecraft的完整功能。
添加完成账户后点击左上角的返回（在后文中缩写为“返回），回到主界面。
点击“没有游戏版本”，选择你想要安装的目录（推荐官方目录，但是如果你同时拥有正版启动器可能会导致冲突），然后点击“安装新游戏版本”，选择你想要安装的游戏版本，单击，选择你想要安装的附属（第一次游玩不推荐安装mod加载器，没有必要），最后点击安装。

{% note info::国内高速下载源使用的是BMCLapi下载源，请支持他们。安装时间可能较长，请耐心等待。%}

安装结束后点击完成，两次返回，回到主界面。点击“启动游戏”。此时可能会提示“你没有Java17以上版本...”，点击“是”，等待下载完成，随后会自动启动游戏。
之后每次打开HMCL后，只需要点击启动游戏即可。

###### PCLII

打开[爱发电](https://afdian.net/p/0164034c016c11ebafcb52540025c377)，选择下载地址1/2。
完成下载后解压打开，**阅读用户协议与免责声明**后选择同意，你会看到这样一个界面：
![PCLII主界面](/img/PCL界面.png)
左侧可以选择正版/离线登录，正版需要按照提示登录，离线直接输入用户名即可。然后点击上面的“下载”，选择你想下载的Minecraft版本，单击，选择附属（第一次游玩不推荐安装mod加载器，没有必要），然后点击“开始安装”。

{% note info::国内高速下载源使用的是BMCLapi下载源，请支持他们。安装时间可能较长，请耐心等待。%}

等待下载完成后返回“启动”，然后点击“启动游戏”。此时可能会提示“未找到Java...”，点击“自动下载”，等待下载完成，之后会自动启动游戏。
之后每次打开PCL后，只需要点击启动游戏即可。

###### BakaXL

尚未完成...
