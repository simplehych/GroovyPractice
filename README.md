# README

---

学习自：https://github.com/qingmei2/ShanbayAutoReader

本项目主要学习了：Groovy 的使用和 adb 命令的使用

将 Android Groovy 转换成 Kotlin 看另一个项目 

https://github.com/simplehych/JetpackDemo

## adb： android debug bridge

https://developer.android.com/studio/command-line/adb?hl=zh-cn

https://juejin.im/entry/57c00fe4c4c971006179838a


点击HOME 键： `adb shell input keyevent 3` 

点击屏幕坐标：`adb shell input tap 400 1000`

滑动屏幕：`adb shell input swipe 300 1000 300 500` 

屏幕截取：`adb shell screencap /sdcard/screencap1.png`

屏幕录制：`adb shell screenrecord /sdcard/screenrecord1.mp4`

这里电脑相当于本地 local，手机相当于远程 remote

文件复制 手机 - 电脑：`adb pull remote local`

文件复制 电脑 - 手机：`adb push local remote`

keycode代码:

https://developer.android.com/reference/android/view/KeyEvent#KEYCODE_HOME


grep: global search regular expression and print out the line 全面搜索正则表达式并把行打印出来
