﻿### AndroidStudio模拟器的按键

> Android SDK2.0.1自带的虚拟机尺寸都比较小（不针对机型，只为了在PC上看的舒服一点，当然越大越好了，我最大设置成1050*450，但是自带的屏保会不够宽，900*450的话，正好。），而且没有横屏的。设置Resolution可以把尺寸变大，但又显示不出键盘来(至今未解决)，所以在网上搜集了一下模拟器的快捷键备忘，模拟器不显示键盘也可以用！

######Home键（小房子键）

在键盘上映射的就是home键，这倒是很好记。

#####Menu键

用于打开菜单的按键，在键盘上映射的是F2键，PgUp键同样可以。另外，看英文原文的意思，貌似这个键在某些机型上会被设计为左软件（left softkey)

######Start键

这个键在模拟器和G1真机上我都没有找到到底是哪个键。映射的是Shift+F2或PgDn，某些机型会被设计为右软键(right softkey)。

######Back键

返回键，用户返回上一个UI或者退出当前程序。键盘上映射ESC键。

######Call/Dial键（电话键）

接听来电或启动拨号面板，这是一部手机最基本的功能键。PC键盘映射为F3键。

######Hangup/Light Off键（挂机键）

挂断电话或关闭背灯用。键盘映射F4键。

######Search键

在提供了Search功能的应用里快速打开Search对话框，比如在Browser里可以快速打开地址搜索栏。键盘映射F5。

######Power Down键（关闭电源）

对应模拟器左上边缘的电源按钮，不过似乎在模拟器上按这个键并没什么用处。键盘映射F7。

######Volume Up （增大音量）

键盘映射Ctrl+5，也可以使用小数字键盘的”+”键。

######Volume Down（减小音量）

键盘映射Ctrl+6，也可以使用小数字键盘的”-”键。

######Camera 键

键盘映射Ctrl+F3。不过也许是我设置有问题，在模拟上用这个快捷键似乎没任何反应。

######Switch Screen Orientation （旋屏）

旋转模拟器屏幕方向，键盘映射Ctrl+F11。这是非常有用和常用的快捷键，几乎所有应用都会受到屏幕方向带来的Layout变化困扰，在开发程序时候，一定要测试屏幕方向的兼容性。

######Cell Networking On/Off （手机网络开关）

这里说的手机网络指的是GPRS/3G这种数据网络，并不影响GSM网络。对于编写基于网络应用的同学，这个快捷键非常有用，可以测试网络异常中断的情况。键盘映射F8

######Code Profiling

不知此为何物-.-，快捷键F9。英文原文：F9 (only with -trace startup option)

######Fullscreen Mode （全屏模式）

一个没什么用的鸡肋功能。也许对于测试画面比较精细的游戏能有点帮助。快捷键是大家喜闻乐见的Alt+Enter。

######Trackball mode （轨迹球模式）

这是一个非常有用的功能，按F6之后，可以打开轨迹球模式，模拟器左上角会显示一个小轨迹球。通过鼠标移动，可以模拟轨迹球的转动。对于测试利用轨迹球操作的应用会非常方便。

Trackball mode Temporaily （临时轨迹球模式）

这个功能很有意思，如果你有比较短暂的使用轨迹球的操作，那么可以按住Delete键滑动鼠标。释放Delete键会自动结束轨迹球模式。

四方向键和中心键

对应键盘四方向键和Enter键，当然也可以用数字小键盘，KEYPAD_5(KEYPAD键为小键盘把Num Lock关掉后，应对为KEYPAD键，关闭后数字5就是KEYPAD_5)对应中心键。

