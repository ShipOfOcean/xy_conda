# xy_conda

- zh_CN [简体中文](readme/README_zh_CN.md)
- zh_TW [繁体中文](readme/README_zh_TW.md)
- en [English](readme/README_en.md)



## 说明
简单Conda工具，提供不同平台conda的安装，加载，备份等功能。

<a href="https://github.com/ShipOfOcean/xy_conda.git" target="_blank">Github地址</a>

## 安装

```bash
pip install xy_conda
```

## 使用

###### 1. 命令行

```bash
# 工作方式:
# "backup + [name]" 备份，环境名称可选,
# "install + [url]" 安装 miniconda,
# "install_pack" 安装pack包,
# "load + [name] + [target_path] + [filepath]" 加载环境包, name:conda环境名称, target_path:目标路径, filepath:环境包文件路径,

> xy_conda -w backup
> 是否备份当前环境 python_3_11_3 
> 输入 [Y/n]
> Y

> xy_conda -w backup -n conda_name
> 是否备份当前环境 conda_name
> 输入 [Y/n]
> Y

> xy_conda -w install

> xy_conda -w install conda安装包url

> xy_conda -w install_pack

> xy_conda -w load -f python_3_11_3_2024_03_19_20_15_22.tar.gz

```

## 捐赠
如果小伙伴们觉得这些工具还不错的话，能否请咱喝一杯咖啡呢
<br/>
![微信](readme/WeChat.png)
![支付宝](readme/Alipay.png)

## 联系方式


```
微信: yuyangitt
邮箱: 845262968@qq.com
```