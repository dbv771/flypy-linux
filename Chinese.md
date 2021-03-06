# 小鹤音形Linux挂接版镜像
[英文介绍](https://github.com/imaojun/flypy-linux/blob/master/README.md)

本仓库为小鹤双拼Linux Rime挂接版镜像,挂接内容来自官方网盘。 

- 网盘地址：
http://flypy.ys168.com/  


## 支持的输入法框架
GNU/Linux小鹤音形无直接对应程序，需要挂载Rime或者YONG(小小输入法）使用。

- RIME
- YONG
- ~~IBUS~~

> 警告:未在IBUS框架上测试,请自行参阅IBUS官方手册进行挂接。



## 更新记录

官网更新说明:
https://flypy.com/bbs/forum.php?mod=viewthread&tid=8&extra=page%3D1


## 结构

小鹤双拼挂接RIME:
```
fcitx/rime-data
├── build
│   ├── flypydz.prism.bin
│   ├── flypydz.reverse.bin
│   ├── flypydz.table.bin
│   ├── flypyplus.prism.bin
│   ├── flypyplus.reverse.bin
│   ├── flypyplus.table.bin
│   ├── flypy.prism.bin
│   ├── flypy.reverse.bin
│   └── flypy.table.bin
├── default.yaml
├── flypyplus.schema.yaml
├── flypy.schema.yaml
├── flypy_sys.txt
├── flypy_top.txt
├── flypy_user.txt
└── rime.lua

```

小鹤双拼挂接小小输入法:
```
yong
├── mb
│   ├── english.txt
│   ├── pinyin.txt
│   ├── pypre.bin
│   ├── xhbc.txt
│   ├── xhup.ini
│   ├── xhup.txt
│   ├── xhzcm.txt
│   └── yb.txt
├── skin
│   ├── ....
└── yong.ini

```



## 安装和使用

详情参看wiki:

https://github.com/imaojun/flypy-linux/wiki

