---
layout: post
title: 私人的用于整理一些喜欢的Linux软件和插件的清单
category: mac
description: 这两年记性总是太差的说，因为某些原因，还是避免不了要重装系统, 但是因为工作原因，都积累了平时可能不怎么用的到，但是关键时候就非常有用的小软件和插件，太多太多基本上记不住，所以还是老老实实的一个个记下来，以后好有个地方查好了。

---

为什么
------
嘛，记得刚学 Linux的时候和当年刚学 Windows时一个尿性，总是在系统文件夹里这个删删，那个删删，看看操作系统会不会有什么反映，当然结果从来都是以悲剧收场。刚学Linux的时候, 总是被视频里各种各样的特效吸引， 作为来自不折腾不舒服斯基星的我，自然是各种折腾，基本上系统是一天崩溃N次，三天系统彻底玩坏的节奏，技术又菜，所以每每都要重装系统，然后重复上一个循环。 每次都得重头再来，结果刚发现没几天觉得很有意思或者有用的软件又找不到了。
这两年记性总是太差的说，因为某些原因，还是避免不了要重装系统, 但是因为工作原因，都积累了平时可能不怎么用的到，但是关键时候就非常有用的小软件和插件，太多太多基本上记不住，所以还是老老实实的一个个记下来，以后好有个地方查好了。

怎么办
------
***俗话说,好记性不如烂笔头***

暂时就索性一个个分类整理好放在这里，以后有时间了整理个一键维护的shell脚本好了。

有什么
------
本人是[Archlinux][]的菜, 所以下面可能会有一些 aur的链接地址。
不因为什么特殊的原因，GNOME KDE太耗资源我的老爷机拖不动啊 (。_。)  。

+ __[gnome-globalmenu-xfce4][]__
  
  一个可以让 [xfce][xfce4] 的面板支持和macos一样的全局菜单的小东东，是[xfce4-panel][xfce4]上的一个小插件。  
  最近听讲还有个 [xfce4-macmenu-plugin][]的插件，据说会好一点，有空去试试。

+ __[xfce4-whiskermenu-plugin][]__

  xfce面板自带的启动器实在是太简陋了，还跟windows98一个样子，怎么说也得跟上XP的脚步啊，这个也是个
  [xfce4-panel][xfce4]上的一个小插件, 可以让 [XFCE4][xfce4]的开始菜单变得和 windows7 类似。

+ __[devilspie2][]__

  一个匹配窗口的工具，让你在某个窗口应用程序启动时执行一个脚本化的动作。我就用它在启动 mplayer时把
  边框去掉，然后指定一个一个大小。

+ __[WPS][]__

  这个就不用仔细介绍了吧，个人觉得，要说 Linux下面最好用的且符合国人使用习惯的办公软件，WPS最适合啊。
  虽然界面都是抄袭巨硬 Office的。

+ __MPD[]__ 和 __MPC[]__

  MPD是一个灵活的,强大的,服务器端音乐播放程序. 简单来说就是一个可以远程使用命令才操作的音乐云服务器,
  同普通的云服务不同的是,并不是将音乐以流形式返回客户端,而是直接在服务器上播放.  
  MPC是一个专为MPC打造的最小化的命令行接口.可以通过它轻松的控制MPD的行为.例如:
    
    mpc play
    mpc next
    mpc volume 80

+ ___ARANDR[]__
 
  XRANDR太难用了有木有, ARANDR是图形版的XRANDR,其实最后还是自动帮你生成了一个XRANDR命令而已.


[archlinux]: http://www.archlinux.org/ "Archlinux"
[xfce4]: http://www.xfce.org/ "XFCE4"
[gnome-globalmenu-xfce4]: http://code.google.com/p/gnome2-globalmenu/ "XFCE4 panel globalmenu"
[xfce4-macmenu-plugin]: https://aur.archlinux.org/packages/xfce4-macmenu-plugin
[xfce4-whiskermenu-plugin]: http://gottcode.org/xfce4-whiskermenu-plugin/ "XFCE4 start"
[devilspie2]: http://www.gusnan.se/devilspie2/ "devilspie2"
[WPS]: http://www.wps.com/ "WPS"
[MPD]: http://www.musicpd.org/ "mpd"
[MPC]: http://www.musicpd.org/clients/mpc/ "mpc"
