# 小鹤音形
小鹤音形内容来自官方网盘。

# ArchLinux环境
Linux小鹤音形需要挂载使用。 
我选择Rime做为挂载平台，Rime是个优秀的输入工具，在Mac/Windos/Linux/Andrido/ios平台都有对应的实现。  
Linux平台的Rime依赖fcitx。  

## 安装依赖
```sh
sudo pacman -S fcitx-rime
sudo pacman -S fcitx-configtool
```

在程序里找到fctix配置，如果是英文系统，需要取消only show current language的勾选，中文系统则不需改变

将rime-data目录下的`*.yaml`和`*.txt`复制到rime的软件目录:  
```sh
 /usr/share/rime-data/
 ```

将build文件夹下`*.bin`文件放到下面目录
```sh
 /usr/share/rime-data/build
 ```
下面这个是用户目录
```
 ~/.config/fcitx/rime/             
 ```

rime的皮肤用的是fcitx的皮肤，自定义皮肤目录为:
```sh
/usr/share/fcitx/skin
```

## Rime配置
禁用Rime的英文模式
从输入方案中 `engine/processor`列表里注视`ascii_composer`
  
# 参考链接
[小鹤双拼方案](http://flypy.ys168.com/)



