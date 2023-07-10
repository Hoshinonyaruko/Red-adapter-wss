# betterQQNT-adapter-wss
bqnt simple onebot adapter wss

这个适配器主要用于连接獭獭

7月10日，目前已知一个bug，可能导致自动崩溃，将在v4版本修复。

请记得redtata.exe要和这个仓库的4个dll放在同一目录，否则报错

https://xn--v9x.net/

没有公开源码是因为经过Betterqqnt作者microblock提醒，二次开发可能会带来不可控的风险。

请不要在官方群聊等内提及本教程。

请不要发送视频，帖子等来宣传此教程。

本教程请不要大规模传播，请不要在视频或论坛投稿。


# 操作【一】

一加入bqnt频道获取 dll (https://t.me/betterqqnt)

（不可以分发所以请自行在原项目仓库获取：https://github.com/BetterQQNT/BetterQQNT）

一将 better-qqnt-x64.dll 重命名为 version.dll 并放入 QQNT 安装文件夹。

一进入QQ在设置-插件 RedProtocol确认开启打勾

一关闭QQ窗口防止崩溃


# 操作【二】

获取适配器

https://wwcr.lanzoul.com/redtata


# 操作【三】

获取TOKEN

—在路径【C:\Users\你的用户名(默认是administrator)\AppData\Roaming\BetterUniverse\QQNT\】

下找到文件 【RED_PROTOCOL_TOKEN】，用记事本打开复制出token 内容，这在下一步有用


# 操作【四】

—在操作二获取的red.exe同一目录下，

创建1.txt文件，

复制模板内容并将举例中的机器人号码、机器人ws地址、red密钥、red的ws地址(如果你的red不在本地,否则保持不变)，

修改为对应您自己的参数

然后将1.txt改为1.bat并运行


title 标题，可自定义

red wss://xn--v9x.net:443/ws red密钥 机器人号码 ws://127.0.0.1:16530 你的獭獭accesstoken 主人qq号

wss地址可以是其他獭窝，一共是6个参数，空格分开

举例：
```
title tata
redtata wss://xn--v9x.net:443/ws 7dcb37d1b0874368e0e21b3242e7d5084bd6851b84108f3b1bde61c0055fd322 3570577015 ws://192.168.0.134:16530 mytoken 主人q号
```

# 操作【五】

运行刚刚修改的1.bat，如果遇到问题，请到交流群at作者询问

免费开源，禁止任何形式的倒卖盈利。

作者不承担因此产生的任何后果。

若您发现有人正在进行此类行为，请发邮件上报

或您有侵权和任何问题以及争议之处，

请发送邮件给我，通过邮件，友好沟通协商解决问题

applegm@me.com

# Addition License

Copyright (c) [2023] [Hoshinonyaruko]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, and distribute the Software, and to
permit persons to whom the Software is furnished to do so, subject to the
following conditions:

1. Redistributions in any form must retain the above copyright notice,
   this list of conditions and the following disclaimer.

2. Redistributions of the Software must not be sold or used for any
   commercial purpose without the express written consent of the copyright
   holder.

3. Modifications to the Software must include the original author's
   name as well as a clear indication of the changes made.

4. The Software is provided "as is", without warranty of any kind, express
   or implied, including but not limited to the warranties of
   merchantability, fitness for a particular purpose and noninfringement.
   In no event shall the authors or copyright holders be liable for any
   claim, damages or other liability, whether in an action of contract,
   tort or otherwise, arising from, out of or in connection with the
   Software or the use or other dealings in the Software.

   purpose without the express written consent of the copyright holder.

4. The author is not responsible for any consequences resulting from the use
   or redistribution of the Software.
