---

title: "Zotero 使用手册"
# excerpt: "A Guide for Zotero"
date: 2022-05-04
permalink: /posts/ZoteroGuide
categories:
  - 教程
  - 科研
  - 软件 
tags:
  - 教程
  - 科研

toc: true
toc_label: "目录"
toc_icon: "cog"
toc_sticky: true

header:
  teaser: "https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205042035494.svg"
---
这篇文章介绍了Zotero和相关必备插件，可以按照本文给出的操作步骤进行设置。




# 账号注册及软件安装
1. [官网](https://www.zotero.org/)  注册账号并下载客户端
2. 安装客户端，准备好两个文件夹备用
	`~/Download/Literature`   网上下载下来的文章临时存放的位置
	`~/Zotero文献库`  存放经过Zotfile重命名后的文件，存放所有文献的地方，谨慎执行重命名和删除操作
    截图中的绿色文件夹路径和名称需要保持一致
3. 软件设置

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041212581.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041216449.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041217080.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041217956.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041218992.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041218848.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041218386.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041218592.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041219594.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041219737.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041219491.png)


# 插件安装及配置

- **[Zotfile](http://zotfile.com/)  文件重命名同步（必装）**
- **[Jasminum](https://github.com/l0o0/jasminum) 识别中文文献的元数据（必装）**
- [Zotero PDF Translate](https://github.com/windingwind/zotero-pdf-translate)  划词翻译（可选）
- [Zotero IF](https://github.com/qnscholar/zotero-if)   自动更新期刊影响因子和中科院分区（可选）
- [Zotero Citation Counts Manager](https://github.com/eschnett/zotero-citationcounts) 自动更新引用次数（可选）
- [打包下载链接](https://pan.baidu.com/s/1HGfWWL7SUFsya6zMUFCJ0Q) 提取码：zb7k

按下图指示加载 .xpi 文件

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205052056639.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205052057128.png)


## Zotfile配置
注意红框中的内容

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041220776.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041220078.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041220643.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041220144.png)

## Jasminum配置
![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041222762.png)


### PDFtk Server配置
下载的PDF格式学位论文一般不带书签，不方便阅读，PDFtk的功能是将学位论文按目录添加书签进PDF文件内

[官网](https://www.pdflabs.com/tools/pdftk-server/) 下载并安装，

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041222034.png)


安装完成后打开cmd输入pdftk，出现信息证明安装成功，关闭cmd 

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041222142.png)

回到zotero设置好安装目录即可

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041223890.png)



## Zotero PDF Translate配置
![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041227170.png)

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041221728.png)


## Zotero IF配置

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041222889.png)



## Zotero Citation Counts Manager 配置

默认即可

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041223202.png)


至此，设置完成，下面开始讲使用。

---

# 工作流程
## 下载文献
- 无论中文还是英文均下载pdf文件至`~/Download/Literature`文件夹，从此可以抛弃caj格式。
- 英文文献命名随意，中文文献命名为 `题目_作者.pdf`   
- Tips：可通过[知网海外版](https://chn.oversea.cnki.net/index/) 来下载学位论文的pdf版本

## 导入
1. My Library 根目录下右键新建 `00Inbox`分类，新导入的文件均放到此分类下
2. 拖到`My Library - 00Inbox` 文件夹内
3. 题录会自动开始识别，对于不同类型的文献操作略有不同

### 中文期刊论文

右键条目点击CNKI-Update CNKI citation可更新引用次数

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041223774.png)


### 中文学位论文

需调用pdftk添加书签，右键条目Manage Attachments - Rename and Move


### 英文期刊论文

Library Catalog栏自动生成中科院分区，Call Number栏自动生成影响因子，右键条目点击Manage Citation Counts即可在Extra栏更新引用次数


## 自动识别完成后

- 图标带回形针标志 代表 已经经过Zotfile完成命名，`~/Download/Literature` 文件夹下的文献就可以删除了
![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041224866.png)

- 若不带回形针标志，则需要右键条目Manage Attachments - Rename and Move ，此时会自动调用Zotfile等插件重命名`~/Download/Literature`文件夹下的pdf文件并复制到`~/Zotero文献库`  文件夹，如果设置了坚果云则会自动上传至同步文件夹，带回形针后即可删除`~/Download/Literature` 文件夹下的pdf 
![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041224582.png)


## 整理归档
给条目打标签，便于快速筛选定位

## 阅读
直接在软件内双击条目或者文档，内置PDF阅读器可以实现高亮、批注等功能，划词利用Translate插件自动翻译

添加的批注默认是**存储在 Zotero 数据库、而非 PDF 文件内部**的。可以随时通过「文件」菜单中的选项在两种批注形态之间相互转换。

## 输出
点击存储注释至PDF，高亮批注等则会保存到PDF内且无法在Zotero中修改，文件管理器中用其他软件直接打开PDF也会显示批注

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041225652.png)

# 常用快捷键
- 点击`+`可展开所有条目，`-`可收起所有条目
- 按住`Ctrl` 可显示当前条目存在于哪个分类下面


# 高级操作

## 配合坚果云同步
只需要将`~/Zotero文献库`  设置为坚果云同步即可，每台电脑上保持主程序和插件配置一致

## Ipad 阅读
在Ipad内通过坚果云直接打开pdf，完成批注后保存pdf，在桌面端使用Zotero内置PDF阅读器打开即可看到Ipad上的批注

## 团队协作

- 按下图设置

![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041227536.png)

- 只占用创建者一人的存储空间
- 将条目和文件从`群组文库`拖到`我的文库`内，等待右上角绿色圈圈同步完成后，右键条目Manage Attachments - Rename and Move 即可保存到`~/Zotero文献库`，从而实现从群组保存到本地个人文库中。


# 常见问题
- 删除条目
软件内右键删除条目和文件后，`~/Zotero文献库`中的pdf文件不会自动删除，需手动操作

- pdf导入进来匹配不到条目
为pdf手动新建条目，主要补全标题、作者、年份卷刊号，完成后重复以下步骤
> 若不带回形针标志，则需要右键条目Manage Attachments - Rename and Move ，此时会自动调用Zotfile等插件重命名`~/Download/Literature`文件夹下的pdf文件并复制到`~/Zotero文献库`  文件夹，带回形针后即可删除`~/Download/Literature` 文件夹下的pdf


# 注意事项
- 软件逻辑：条目和pdf分开存放，有利于PDF的备份和同步
- 从`00Inbox`分类移动到新分类之后，是否需要从`00Inbox`中删除？要分情况，看其他分类是怎么建立的

## 操作流程
![](https://asgeologeekfan-images.oss-cn-hangzhou.aliyuncs.com/img/202205041227102.png)


