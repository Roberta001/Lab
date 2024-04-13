---
title: 使用IPv6进行Minecraft Java版联机
tags:
  - Minecraft
  - 配置
  - 联机
abbrlink: 18456
date: 2024-03-19 20:08:24
---
## 前言
之前做过一个视频，讲如何使用IPv6进行联机，但是已经比较老了，有些东西也已经过时/更新，所以重新做了一篇文字教程，当然还是会出视频教程。
听着音乐开始吧！
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=1404469236&auto=1&height=66"></iframe>

## 一.进行IPv6网络连通性测试
打开[IPv6地址查询](https://ipw.cn/ipv6/)，如果这里显示“您的网络 IPv6 访问优先”代表你可以进行IPv6连接，此时复制你的IPv6地址。
![你的IPv6地址（可能与我的不同）](/img/IPv6地址查询.png)
{% note info::玩家和房主都需要支持IPv6，但只需要房主复制自己的地址。%}

{% note warning::显示不支持IPv6？可以参考网站提供的解决办法。%}

## 二.房主下载mod并启动Minecraft，开启房间
打开[curseforge的Lan Server Properties下载界面](https://www.curseforge.com/minecraft/mc-mods/lan-server-properties/files/all?page=1&pageSize=20)，选择对应你游戏的版本（支持Forge和Fabric）。
打开游戏，进入你的单人游戏，按下ESC，选择对局域网开放，会打开这样一个界面：
![配置界面](/img/局域网联机mod配置界面.png)
游戏模式：玩家默认的游戏模式。
允许作弊：是否允许玩家使用gamemode这一类的作弊命令。
在线模式：是否允许离线（盗版）玩家进入。
~启用：开启正版验证，仅允许正版玩家进入。
~离线模式+UUID修复：同时允许正版和离线玩家进入，同时针对正版玩家的UUID进行优化，防止无法读取皮肤与背包数据错乱的BUG。
~关闭：允许离线玩家进入，不进行任何UUID修复。
允许PVP：是否允许玩家间攻击。
监听端口：可以为1024-65535的任意值。
{% note warning::设置较低的端口可能会出现问题，建议使用默认的25565，同时需要你记住这里的端口号%}

最大玩家数：字面意思。
点击创建局域网世界。
## 三.玩家连接至房主房间
玩家启动游戏（不需要装载Lan Server Properties），点击多人游戏，添加服务器，按照以下格式输入服务器地址：
~~~
[IPv6地址]:端口
~~~
例如：房主IPv6地址是2409:8a00:####:####:####:####:40c3:6b67，端口选择的是11451，那么玩家需要输入这个地址：
~~~
[2409:8a00:####:####:####:####:40c3:6b67]:11451
~~~
{% note danger::不要向陌生人透露你的IPv6地址，否则你可能会遭遇网络攻击。%}

然后点击完成。
在服务器列表找到他，双击即可进入。
