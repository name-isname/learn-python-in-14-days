# Day01 准备环境
前置条件：
网络环境没问题，能在网页和终端里同时直连
有能稳定使用的AI账号，最好是GPT等能联网的AI

## 安装软件
uv（Python包管理工具），Zed（高性能代码编辑器），Git（版本管理工具）
安装方式（任选其一，推荐包管理。使用第一种或第二种方式时注意环境变量Path的问题）
1. 搜索找到官方Document，按照Install步骤来安装。
2. 找到GitHub上仓库的Release/找到官方网站安装包下载。
3. 包管理工具下载。

*可选包管理工具*
教程中所有软件/命令行工具都推荐使用包管理工具安装。Windows使用scoop进行包管理，macOS使用Brew进行包管理。了解包管理工具的常用命令，学会如何搜索/下载/更新/删除软件。

*可选终端优化*
Windows方案：升级powershell 5为 Powershell 7，安装Windows Terminal，安装oh my posh。
macOS方案：安装ghostty终端模拟器，安装oh my zsh优化，主题`omz theme set ys`

## 学习初步使用终端
询问AI如何打开终端，快捷键是什么。
问AI最终端中常用的10个命令，理解每个命令在干什么，每个都去操作一遍。最终掌握基本命令行使用能力，学会如何在文件目录间移动（ls/cd/../~），理解$profile/.zshrc的功能。

## 使用uv
询问AI最高频的uv命令，并在终端里尝试使用，至少掌握init，add，run。
使用uv安装python3.13

使用uv下面的命令初始化一个项目，再运行这个项目，理解这里面的每行命令是什么意思
```zsh
uv init --no-package 项目名
uv run main.py
```
在zed里打开这个项目文件夹，无需做代码编辑，观察初始化项目的文件夹里有什么内容，询问AI，理解文件作用。
zed可以使用下面的命令用zed打开终端当前所在文件夹。
```zsh
zed .
```

---
