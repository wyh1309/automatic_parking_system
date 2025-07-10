# Automatic Parking System

**SUSTECH EE207-17L project**

**南方科技大学数字电路实验课项目**
![_cgi-bin_mmwebwx-bin_webwxgetmsgimg__ MsgID=6008275743338740213 skey=@crypt_32a4aae9_4adb4c269953d5da2a1b9229b597cc92 mmweb_appid=wx_webfilehelper](https://github.com/user-attachments/assets/12af32a3-4913-4e6b-9975-b212cd61e74d)

## 介绍
本项目是一个以stm32f103c8t6作为主控，基于HAL库，通过惯性导航确定停车位置的小车。具体逻辑是小车在行驶固定距离后进行检测，检测到距离大于某个临界值时便开始倒车。

## 改进方法
这个项目的得分应该是85分左右。如果您想在本项目基础之上进行改进以便在这门课取得更好的分数，您可以在以下方面进行改进：
1. 在FreeRTOS框架下对代码进行重写。
2. 增加视觉模块，如OPENMV。
3. 探索闭环角度控制算法。
4. 对小车的机械结构进行重新设计。

## 警告
本项目的代码和PCB已经上交给老师，因此完全的抄袭可能会给您带来麻烦，建议学这门课并且做小车类项目的同学仅将该项目作为参考。

## 结尾
部分代码参考B站up主草履虫的平衡小车项目，在此表示感谢。如果您觉得该项目对您有用，麻烦您给我一个星星，谢谢。


