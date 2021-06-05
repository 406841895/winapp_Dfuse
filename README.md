# winapp_Dfuse
# 为什么做这个？
命令行工具被C#调用时不能实时获取输出
# 做了些什么？
基于官方的v3.0.4版
在printf之后增加了fflush，可以将io缓存输出
vs版本为2019
需要MFC库
