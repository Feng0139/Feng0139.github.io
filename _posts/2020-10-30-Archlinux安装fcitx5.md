---
layout:     post   				    # 使用的布局（不需要改）
title:      Archlinux安装Fcitx5 	  		# 标题
subtitle:                   		#副标题
date:       2020-10-30 				# 时间
author:     Feng 					# 作者
header-img: img/post-bg-desk.jpg 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签
    - Archlinux
---

# 安装Fcitx5中文输入法+皮肤
```
sudo pacman -S fcitx5 fcitx5-chinese-addons fcitx5-gtk fcitx5-qt kcm-fcitx5 fcitx5-material-color
```

## 配置环境变量
```
sudo vim ～/.pam_environment
```
执行命令，添加以下内容
```
INPUT_METHOD  DEFAULT=fcitx5
GTK_IM_MODULE DEFAULT=fcitx5
QT_IM_MODULE  DEFAULT=fcitx5
XMODIFIERS    DEFAULT=@im=fcitx5
```