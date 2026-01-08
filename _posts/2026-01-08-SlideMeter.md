---
title: "PPT 进度条大师"
---

# 📊 [SlideMeter (PPT 进度条大师)](https://www.asgeologeekfan.top/project/SlideMeter.html)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-v8.1-green)](index.html)
[![Tech](https://img.shields.io/badge/Pure-Frontend-orange)](https://github.com/Stuk/jszip)

> **A secure, pure frontend tool to generate progress bars for PowerPoint presentations automatically.**
>
> **无需联网、数据不离本地的 PPT 智能进度条生成工具。**



## 📖 简介 (Introduction)

**SlideMeter** 是一款专为科研汇报、工程答辩和商务演示设计的轻量级工具。它利用 HTML5 和 JavaScript 技术，直接在浏览器端解析并修改 `.pptx` 文件的 XML 结构，自动添加美观、精准的进度条和页码。

与传统的插件不同，**SlideMeter** 不需要安装任何 Office 插件，也不需要将文件上传到服务器。所有处理均在您的本地浏览器完成，完美解决了涉密项目（如地质工程、科研课题）的数据安全顾虑。

## ✨ 核心功能 (Features)

* **🛡️ 数据隐私第一**：纯前端实现，文件流仅在内存中处理，绝不上传服务器。
* **🎨 高度可视化定制**：
    * 支持自定义进度条颜色、粗细、透明度。
    * 支持页码文字的字体、字号、颜色（支持颜色跟随进度条）。
    * 提供 X/Y 轴像素级位置微调。
* **⚙️ 严密的逻辑控制**：
    * **章节分割**：支持手动指定页码生成“章节分割竖线”，直观展示汇报节奏。
    * **排除与跳过**：支持跳过封面/封底，排除特定页码（不计入总数）。
    * **隐藏页处理**：自动识别并忽略 PPT 中的隐藏幻灯片。
* **🧹 智能清理**：内置 DOM 安全清理机制，重复生成时自动移除旧图层，防止叠加。

## 🚀 快速开始 (Quick Start)

### 方法 1：直接使用
1. 下载本项目中的 `SlideMeter.html` 文件。
2. 双击在任意现代浏览器（Chrome, Edge, Firefox）中打开。
3. 拖拽你的 PPT 文件开始使用。

### 方法 2：部署到 GitHub Pages
1. Fork 本仓库。
2. 在仓库 Settings -> Pages 中选择 `main` 分支。
3. 访问生成的 URL 即可在线使用。

## 🛠️ 技术栈 (Tech Stack)

* **Core Logic**: Vanilla JavaScript (ES6+)
* **UI Framework**: Native CSS (Flexbox/Grid), Tech-Business Style
* **Libraries**:
    * [JSZip](https://stuk.github.io/jszip/): 用于解压和打包 `.pptx` (OpenXML) 结构。
    * [FileSaver.js](https://github.com/eligrey/FileSaver.js): 用于在浏览器端触发文件下载。

## 📝 使用指南 (User Guide)

1.  **上传文件**：点击或拖拽 `.pptx` 文件到上传区。
2.  **视觉设置**：
    * 调整进度条颜色和高度。
    * 设置页码文字样式（建议勾选“文字颜色跟随进度条”）。
3.  **逻辑设置**：
    * **章节分割**：输入页码（如 `6, 12`），工具会在该页的**左侧**绘制白色分割线。
    * **排除页面**：输入不需要显示进度的页码。
4.  **生成**：点击“生成并下载”，文件将自动保存到本地。

## 🤝 贡献 (Contributing)

欢迎提交 Issue 或 Pull Request 来改进这个工具！
特别是针对不同 PPT 版本兼容性的测试反馈。

## 📄 开源协议 (License)

本项目基于 [MIT License](LICENSE) 开源。


*最后更新：2025 年 11 月 20 日*
