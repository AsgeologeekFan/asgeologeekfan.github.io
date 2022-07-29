---
title: "PFC中调用Python安装第三方库"
# excerpt: ""
date: 2022-07-29
# permalink: /posts/pfc
last_modified_at: 2022-07-29
categories:
  - 科研
  - PFC
tags:
  # - 科研

toc: False
toc_label: "目录"
toc_icon: "cog"
toc_sticky: False

header:
  teaser: "https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202206241629640.png"
---
介绍了在PFC中安装Python第三方库的步骤。


0. 环境变量选择PFC自带的Python： 
	系统变量Path内新建
	`C:\Program Files\Itasca\PFC600\exe64\python36\Scripts`
	`C:\Program Files\Itasca\PFC600\exe64\python36`
![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202207251949745.png)

1. 管理员身份运行cmd，`where pip`，查看是否指向PFC自带的Python
2. `python -m pip install --upgrade pip`
到这一步可以直接pip install在线安装
3. `pip install XXXXX` 
也可以先安装wheel库后按下面的步骤离线安装
4. `pip install wheel`
5. 将`.whl`文件放到`C:\Program Files\Itasca\PFC600\exe64\python36\Scripts`目录下
6. `cd C:\Program Files\Itasca\PFC600\exe64\python36\Scripts`
7. `pip install XXXXX.whl --user`


切换至Anaconda环境
系统变量Path内删除上面的两条变量，新建以下四条：
`C:\ProgramData\Anaconda3`
`C:\ProgramData\Anaconda3\Scripts`
`C:\ProgramData\Anaconda3\Library\bin`
`C:\ProgramData\Anaconda3\Library\mingw-w64\bin`
完成后cmd输入 `conda --version` 提示正确即可