# xy_conda

- zh_CN [简体中文](README_zh_CN.md)
- zh_TW [繁体中文](README_zh_TW.md)
- en [English](README_en.md)


## 说明
简单Conda工具，提供不同平台conda的安装，加载，备份等功能。


## 安装

```
pip install xy_conda
```

## 使用

###### 1. 命令行
```
# 删除当前目录下所有 py 脚本文件
xy_file -w clean -g "*.py"

```

###### 2. python脚本

```
from xy_file.File import File
from pathlib import Path

touch_file_path = Path.cwd().joinpath("test.txt")
# 创建文件当该文件路径为空
file_path = File.touch(touch_file_path)
# 如果file_path不为空 说明创建空文件成功
```

## 捐赠

如果小伙伴们觉得这些工具还不错的话，能否请咱喝一杯咖啡呢
<br/>
![微信](WeChat.png)
![支付宝](Alipay.png)

## 联系方式

```
微信: yuyangitt
邮箱: 845262968@qq.com
```