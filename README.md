Diablo3WeaponReroller
===================

This is a python rebuild of the famous Diablo 3 Weapon Reroll Caculator

暗黑3 武器附魔计算器 Python 重制版

* Author :  Oicebot @ Ellesime
* Email  :  oicebot@qq.com
* Weibo  :  @游荡的坎德人
* Twitter:  @Oicebot

This file published under GPLv3. 

All Weapon Data came from Weapon Reroll Calculator at:  http://us.battle.net/d3/en/forum/topic/15699487088

Thanks to */u/Might\_be\_a\_terrorist*, /u/MFiftyOne & /u/Kortiah


* * *

In this Repo:
-----------

* _D3WeaponReroll.pyw_ is the main code, it can be run directly under Linux and/or other Python-installed OS 
* Weapon Data is stored in `self.WeaponTable` in the Application class. It could be updated manually.  
* I used [Visual Tkinter](https://github.com/cdhigh/Visual-Tkinter-for-Python) when build the GUI, so all other files were created by VB6.0 when design the interface.
* I used py2exe to build stand alone executables using setup.py 


ChangeLog
---------

####v0.13
1. 建立 github 仓库啦～
1. 增加小键盘区回车键支持
1. 修正了tab焦点的跳转顺序

####v0.12
1. 更新到原版 2015.4.28 的数据表格
1. 增加了单手重武器分类
1. 增加了将速度洗成10ed的计算结果
1. 更新了界面排版


