# AcfunPlus

> 一个轻量 AcFun 信息聚合页。  
> “认真你就输啦 (・ω・)ノ- ( ゜- ゜)つロ”

[![版本](https://img.shields.io/badge/版本-v0.0.1.1-FD4C5B?style=flat-square)](./about.html)
[![状态](https://img.shields.io/badge/状态-积极维护-brightgreen?style=flat-square)]()
[![许可](https://img.shields.io/badge/许可-CC%20BY--NC--SA%204.0-lightgrey?style=flat-square)]()

---

## 简介

**AcfunPlus** 是一个非官方的 AcFun 辅助工具页面，拥有早期视频信息数据库的信息记录。项目采用纯静态 HTML + CSS 构建。

---

## 主要功能

- **网址汇总**：一键直达 AcFun 域名。
- **视频信息数据库**：内置数据结构支持快速更新，便于扩展视频列表或相关索引。
- **全平台适配**：基于 Flexbox 与 Media Query，在手机、平板、电脑上均有出色浏览体验。
- **实时更新日志**：在关于页面内嵌版本记录，方便追踪功能迭代与样式变更。

---

## 快速开始

由于项目为纯静态页面，无需安装任何依赖或构建工具，您只需以下任一方式即可运行：

### 方式一：本地直接打开
将项目克隆或下载到本地，使用 python -m http.server 8080 即可在浏览器中预览。

```bash
git clone https://github.com/wulitian2-png/acfunplus.git
cd acfunplus
python -m http.server 8080
