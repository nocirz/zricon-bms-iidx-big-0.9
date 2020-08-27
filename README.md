# ZriCON BMS/IIDX BIG VER 0.9 相关资源
适用于**底部未粘贴标记的0.9版控制器**。<br>ZriCON BMS/IIDX BIG VER 1.0（控制器底部粘贴标记）不适用，请移步[ZriCON BMS/IIDX BIG VER 1.0 相关资源](https://github.com/nocirz/zricon-bms-iidx-big-1.0)<br>
+ [ZriCON_BMS_IIDX_BIG_VER_0_9_20200824_firmware.exe](https://github.com/nocirz/zricon-bms-iidx-big-0.9/raw/master/ZriCON_BMS_IIDX_BIG_VER_0_9_20200824_firmware.exe) 0.9_20200824版本固件更新程序。
+ [ZriCON BMS-IIDX BIG VER 0_9 音乐游戏控制器使用说明_20200824.pdf](https://github.com/nocirz/zricon-bms-iidx-big-0.9/raw/master/ZriCON%20BMS-IIDX%20BIG%20VER%200_9%20%E9%9F%B3%E4%B9%90%E6%B8%B8%E6%88%8F%E6%8E%A7%E5%88%B6%E5%99%A8%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E_20200824.pdf) 控制器说明书，适用固件为0.9_20200824。

因0.9版控制器在制作时缺乏对固件的版本管理，每一台控制器在制成时的初始固件都不尽相同，故建议0.9版控制器用户下载新版本固件并上传至控制器。更新后控制器的使用说明请参见与固件版本相对应的说明书。<br>
固件的更新方法：下载固件更新程序，将控制器与电脑连接，保证串口（COM）上无其它设备，且未同时连接多个控制器的情况下，直接运行固件更新程序。固件上传时，控制器的5号按键灯将闪烁，当控制器出现启动灯效时，表示更新成功。

固件版本0.9_20200824更新内容：
+ 更换使用的HID库，刷新率提升，延迟更稳定
+ 修改转盘输出手柄按键信号的逻辑，改善在LR2/beatoraja中出现的转盘“走火”问题
+ 增加按住CTRL1屏蔽转盘输出手柄按键信号的功能，以便于在beatoraja中为转盘绑定手柄X轴信号
+ 取消鼠标信号的输出，原键盘/鼠标信号输出模式改为键盘信号输出模式
+ 设置模式的数值增减操作改为按CTRL1减少，按CTRL2增加
+ 修复转盘灯光颜色无法正确保存的问题 （更新固件后可能出现转盘灯光颜色改变的情况，重新更改保存即可）
+ 修复搓盘时转盘灯光旋转过快的问题
