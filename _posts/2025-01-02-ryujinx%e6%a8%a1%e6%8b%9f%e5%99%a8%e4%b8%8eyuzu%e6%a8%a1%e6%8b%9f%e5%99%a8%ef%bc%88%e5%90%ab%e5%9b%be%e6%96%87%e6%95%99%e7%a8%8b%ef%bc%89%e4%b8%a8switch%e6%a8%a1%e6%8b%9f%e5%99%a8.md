---
title: "Ryujinx模拟器与Yuzu模拟器（含图文教程）丨Switch模拟器"
date: 2025-01-02
tags: ["其他", "合集", "工具", "教程", "模拟", "模拟器", "硬件", "补丁", "软件"]
categories: ["Switch游戏"]
excerpt: "简介 Ryujinx是Nintendo Switch的免费开放源代码模拟器，由gdkchan创建并使用C＃编写的开源Nintendo Switch仿真器。 Yuzu是一个开源模拟器，由GPLv2（或者任何更高版本）授权，Yuzu的设计也考虑到了可移植性，可用于Windows，Linux和MacOS。&hellip;"
layout: post
---

<p style="text-align: center;"><img style="display: block; margin-left: auto; margin-right: auto; width: 100%; height: auto;" src="https://2cy.202588.cn//wp-content/uploads/2025/01/20250103_677756ac703c3.webp" alt="Ryujinx模拟器与Yuzu模拟器（含图文教程）丨Switch模拟器" /></p>

<h2>简介</h2>
Ryujinx是Nintendo Switch的免费开放源代码模拟器，由gdkchan创建并使用C＃编写的开源Nintendo Switch仿真器。

Yuzu是一个开源模拟器，由GPLv2（或者任何更高版本）授权，Yuzu的设计也考虑到了可移植性，可用于Windows，Linux和MacOS。

本次分享内容为：ryujinx和Yuzu模拟器以及图文教程
<h1 style="text-align: left;"><strong>Ryujinx安装使用教程</strong></h1>
<strong>Ryujinx是由gdkchan用C＃编写的switch开源模拟器，相对于另一个模拟器yuzu，它的兼容性更好，但运行速度更慢。</strong>

<strong> </strong>
<h3>一、安装教程</h3>
1.把下载的压缩包解压到一个没有中文的路径下
2.进入目录，双击打开Ryujinx.exe，有弹窗点ok就行了
3.在模拟器最上方依次点击File→Open Ryujinx Folder
4.弹出Ryujinx目录后，进入system文件夹，把prod.keys（文件到评论置顶下载）放进去
5.关闭目录，关闭模拟器，重新打开模拟器(这时应该不会再有弹窗了)
<h3>二、安装Firmware(固件)</h3>
在模拟器最上方依次点击Tools→Install Firmware→Install a firmware from XCI or ZIP
在弹出的窗口中选择固件Firmware 9.2.0.zip，然后点open
若出现报错，是因为步骤三的prod.keys文件与Firmware不匹配，prod.keys文件要与Firmware匹配才可以安装成功，因此你若想安装新的firmware，则需要你自己去找对应的prod.keys
<h3>三、如何安装游戏Updates</h3>
1.选中游戏，右键，点击Manage Title Updates
2.在弹出的界面点击Add
3.在弹出的界面中浏览你的update文件，选中，点击Add
PS：Update只需要安装最新的一个就可以了
4.点击Save，就完事了
<h3>四、如何安装游戏DLC</h3>
1.选中游戏，右键，点击Manage DLC
2.在弹出的界面点击Add
3.选择DLC文件，然后点击Add
DLC安装无顺序要求，但需要全部安装！！！
4.选中DLC，点击Save
<h3>五、如何安装MOD？</h3>
1.选中游戏，右键，点击Open Mods Directory
2.在弹出的文件夹中放入你的Mod文件
<h2>Yuzu安装使用教程</h2>
<h3>PC配置要求如下：</h3>
硬件部分：

处理器：需要64位CPU，单核性能最好在3.5Ghz以上，部分游戏需要4.0Ghz以上

支持tsx指令集最好

内存：最低建议8G（DDR3-1333，DDR4-2133）以上，推荐16G（DDR3-1333，DDR4-2133）以上

显卡：支持Vulkan渲染，yuzu模拟器不是很吃显卡，当然性能越高越高，集显核显（AMD Ryzen APU除外）就放弃吧

软件部分：

显卡驱动OpenGL版本4.3以上

需要安装Microsoft Visual C++ 2015-2019，网络搜索微软VC运行库合集即可
<h3>运行游戏的必要环境：</h3>
1、Yuzu模拟器，模拟器需要放在非中文路径下

2、游戏本体（XCI，NSP格式）

3、密钥（keys），否则不能运行商业游戏

4、存档、DLC、升级补丁、系统文件等文件（可能需要）

5、一台Windows（或者Linux，AMC）系统的电脑
<h3><span style="color: #333333; text-indent: 2em;">使用教程</span></h3>
&nbsp;

<strong>一、安装</strong>

1.把下载的压缩包解压到一个没有中文的路径下，没有中文的路径！！！没有中文的路径！！！

2.进入解压的目录，在yuzu.exe的同级目录下，新建user目录

新建user目录

3.双击打开yuzu.exe，弹窗点ok、no

点击ok

点no

4.进入第2步创建的user目录，可以看到生成了一些目录和文件

进入keys目录，把key文件（一般包括prod.keys和title.keys，请到评论置顶下载key文件）放进去

5.关闭模拟器，重新打开yuzu.exe，若没有弹窗，则配置成功

<strong>二、添加游戏</strong>

双击模拟器中间，添加游戏目录，游戏目录也不要有中文

注意！！！这里选择游戏所在的目录就行了，不是让你选的游戏，是让你选的游戏所在目录，你看不到你的游戏文件是正常的，让你选的是游戏所在的目录

添加完目录之后在模拟器中就能看到添加的目录了

可以看到虽然有目录，但没有显示游戏

因为模拟器默认只搜索你选择目录的下一级，更深的目录它是不扫描的，所以如果你的游戏文件在更深的子目录下面，它是不会显示的

这时可以右键目录，勾选扫描子文件夹，就可以显示了

如果还没显示，那么要么是你目录没选择对，要么是你的游戏下载的不对，游戏格式一般是.nsp或者.xci结尾的

<strong>三、安装固件</strong>

虽然yuzu模拟器不是必须安装固件，但我还是建议你安装一下固件，因为不安装固件的话，有些游戏可能会出现字体乱码或者卡启动之类的问题，安装固件更好一点

yuzu安装固件需要先使用Ryujinx生成一些文件，具体的可以往下看，如果你不想下载安装Ryujinx，我也在评论区置顶分享链接里分享了这些文件，你可以可以直接跳到下面第3步那里把我分享的文件复制到指定目录就行了。如果还嫌麻烦，那就直接下载解压即用版。

首先，安装固件需要用到Ryujinx模拟器生成一些文件

参考我另一篇文章的第四步安装Firmware(固件)，先成功安装固件

Ryujinx安装使用教程

零.懒人必看，解压即用 如果你嫌教程麻烦，看不懂，评论区置顶分享了解压即用版（只提供Windows版，其他系统请按照下面的正式教程自己配置），直接解压即可使用。解压即用版本的配置文件在压缩包内的portable目录中，你玩游戏的存档、安装的DLC和update、我帮你安装好的固件、我帮你配置好的key文件全在这个portable目录中。配置目录 如果想更新模拟器，记得备份portable目录，可以直接去官网下载最新的模拟器，解压之后，直接把原来的portable目录放到最新模拟器与ryujinx.exe同

<strong>四、模拟器设置</strong>

手柄玩家按键设置

选择你的手柄即可加载默认手柄设置，此时所有按键都已自动设置好，不需要你再一个一个去设置，如果你没有想修改的，那就直接点ok就可以了，如果有想修改的，就用鼠标左键点击对应的按键，再设置就行了

键盘玩家按键设置

&nbsp;
<h3><span style="color: #333333; text-indent: 2em;">运行问题集锦</span></h3>
一、怎么安装DLC和升级补丁？

File-Install File to NAND

&nbsp;

二、怎么安装Amiibo？

注意Amiibo只有打开游戏或才可以加载

三、游戏有中文但是玩的时候没有中文

需要安装字体，参考上文font部分

还需要设置System-Language，倒数两个是简体中文和繁体正文

四、怎么安装其他Shader着色器

五、弹框“xxx missing”或者“xxx key could not be found”

没有正确安装密钥，网络搜索密钥安装教程

六、为什么说GPU不支持某些OpenGL扩展？

显卡或者显卡驱动需要升级

七、缺失MSVC visual C++？

需要安装Microsoft Visual C++ 2015-2019，网络搜索微软VC运行库合集即可

八、模拟器卡死？

游戏文件是否有损坏，电脑内存是否足够（8G内存加虚拟内存），开启多核模式后会疯狂加载内存，32GB也不一定够，显卡OpenGL版本是否4.3以上，电脑硬件配置是否足够

九、提示“32bit not implemented”？

yuzu不支持32位游戏

十、配置足够游戏还不能运行？

yuzu还在开发阶段，部分游戏还不能完美模拟，相信yuzu模拟器会越来越好的

十一、游戏能运行，但是图像错误，卡顿?

同上一条，yuzu还在开发阶段，部分游戏还不能完美模拟，相信yuzu模拟器会越来越好的

可以尝试降低图形配置的选项，更改OpenGL和Vulkan，关闭垂直同步，降低分辨率，不要锁帧等等用付费版开启多核模式也是一种方案

十二、其他设置更改说明

System

Birthday、Sound output mode、console ID这三项没有实际用处

设置了也没用，如果以后可以用console ID了，别点Regenerate，可能导致存档失效

Language：游戏语言，如果需要设置的话

Custom RTC：修改系统时间，可以触发某些游戏的特定彩蛋之类的功能。

RNG seed：随机数种子，一般情况别改改。

Profile Manager

这里可以改switch用户名称、头像。可以设置多个用户

Audio

游戏卡就开audio stretching，不卡就不开，output engine选auto或者cubeb才有音频

Audio device一般情况下自动就行，没声音的话手动选PC的声音设备

右键游戏菜单

Open Save Data Location，打开存档目录

Open Mod Data Location，打开Mod目录

Copy Title ID to Clipboard，复制游戏ID到剪贴板

Dump RomFS：提取游戏RomFS，适合用于解包数据

Properties：属性，有很多有用的信息和功能

Navigate to GameDB entry：跳转到当前游戏运行兼容性报告网站，比方说可以运行，运行不好等信息，用红绿黄等颜色展示

File：文件

Install File to NAND：安装XCI、NSP格式的游戏，一般没必要安装游戏本体，也可以用来安装游戏DLC、升级补丁，安装完在C盘的yuzu文件夹

Load File：加载游戏文件

Load Folder：加载游戏的文件夹

Select Game Directory：选择游戏的目录，选好后游戏会在游戏列表展示

Recent Files：最近打开的文件

Select NAND Directory：没什么事别点

Select SD Card Directory：没什么事别点

Load Amiibo：加载Amiibo

Open yuzu Folder：打开yuzu的配置目录，相当于Citra的user文件夹

Emulation：模拟

开始暂停停止重启

Configure：设置，yuzu重要设置都在这里

View：视图

Fullscreen：全屏，快捷键F11

Single WIndow Mode：单窗口模式

Display Dock Widget Header：开发人员选项，对平常使用没有影响

Show Fliter Bar：显示搜索条，可以不勾

Show Status Bar：显示状态，看帧率等

Debugging：开发人员选项

Tools：工具

Reinitialize keys：重新引导密钥，最好别点

Capture Screenshot：截图

Help：帮助

Report Capability：向官网报告游戏兼容性，需要Citra账号

About yuzu：查看各种帮助信息

General：通用 这里的一般默认即可 列出关键的

Limit Speed percent：游戏运行速度，默认即可，可加快或限速

Theme：模拟器界面主题，Light，Dark等

Pause emulation when inbackground：退到后台模拟器暂停运行

Hide mouse inactivity：运行时鼠标隐藏

Prompt for user for game boot：游戏启动时选择哪个账户游玩

（即System中的Profiles账户），玩过Switch的玩家应该知道这个账户的意思

Web：

yuzu web service：填了用户名和令牌以后可以向官网报告游戏兼容性

Telemetry：开了以后能让yuzu开发者查看你的使用情况，以便改善模拟器

Discord Presence：在discord中显示你的游戏状态

Debug：

全都是开发者选项，我们不用管

Game List

Show Add-Ons Column：显示“附加项”列

Icon size：游戏图标大小

Row text：游戏显示哪些名称

&nbsp;
<h2 style="white-space: normal; text-align: left;"></h2>

---
📖 **下载地址/原文地址：** 本文最初发布于我的博客网站：[https://2cy.202588.cn/2025/01/2893/](https://2cy.202588.cn/2025/01/2893/)
