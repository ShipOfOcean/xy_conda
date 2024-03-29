# xy_conda

- zh_CN [简体中文](README_zh_CN.md)
- zh_TW [繁体中文](README_zh_TW.md)
- en [English](README_en.md)

## Description
Simple Conda tool that provides installation, loading, backup and other functions of conda on different platforms.

<a href="https://github.com/ShipOfOcean/xy_conda.git" target="_blank">Github</a>

## 安装

```bash
pip install xy_conda
```

## How to use

###### 1. Terminal
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

## Donate
If you think these tools are pretty good, Can you please have a cup of coffee?
<br />
![WeChat](WeChat.png)
![Alipay](Alipay.png)

## Contact


```
Wechat: yuyangitt
Mail: 845262968@qq.com
```