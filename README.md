# 横道图 Gantt

> 一款基于 Electron 的 macOS 甘特图工具 — 轻量、高效、直观的项目进度管理

[![macOS](https://img.shields.io/badge/macOS-10.15+-blue)](https://developer.apple.com/macos)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-ARM64-brightgreen)](https://support.apple.com/zh-cn/HT211814)
[![Version](https://img.shields.io/badge/version-1.0.10-orange)]()

## 简介

**横道图 Gantt** 是一款适用于 macOS 的项目进度管理工具，采用经典的甘特图（横道图）形式，帮助用户直观地规划、跟踪和管理项目任务。无论是个人工作计划还是团队项目协作，都能快速上手。

## 功能特性

- **甘特图展示** — 以横道图形式清晰展示任务时间线，一目了然
- **任务管理** — 创建、编辑、删除任务，设置起止时间和工期
- **进度跟踪** — 可视化展示任务完成进度，实时掌握项目状态
- **依赖关系** — 设置任务前后置依赖，自动调整排期
- **里程碑标记** — 标记关键节点，聚焦重要时间点
- **多项目支持** — 同时管理多个项目数据
- **数据导出** — 支持导出为 Excel (.xlsx) 和 PDF 格式，方便汇报分享
- **日历视图** — 结合日历展示，灵活查看日程安排
- **本地存储** — 数据保存在本地，隐私安全

## 系统要求

- **操作系统**: macOS 10.15 (Catalina) 或更高版本
- **处理器**: Apple Silicon (M1/M2/M3/M4 系列) 或 Intel
- **架构**: ARM64（通用二进制）

## 下载安装

### 方式一：直接下载

从 [GitHub Releases](https://github.com/kail896/gantt-chart/releases) 页面下载最新版本的 `.dmg` 安装包。

### 方式二：克隆仓库

```bash
# 克隆仓库（需要安装 Git LFS）
git lfs clone git@github.com:kail896/gantt-chart.git

# 或者
git clone git@github.com:kail896/gantt-chart.git
cd gantt-chart
git lfs pull
```

安装：

1. 打开下载的 `横道图 Gantt-1.0.10-arm64.dmg`
2. 将 `横道图 Gantt.app` 拖入 **应用程序** 文件夹
3. 首次打开时，如果提示"无法验证开发者"，请前往 **系统设置 → 隐私与安全性 → 仍要打开**

## 使用说明

1. 打开应用，创建新项目
2. 添加任务，填写任务名称、起止时间
3. 拖拽甘特条调整任务时间
4. 设置任务间依赖关系
5. 导出项目进度报告

## 技术栈

- **框架**: [Electron](https://www.electronjs.org/)
- **平台**: macOS (ARM64)
- **架构**: 前端渲染 + 主进程架构

## 截图

<!-- TODO: 添加应用截图 -->
<!-- ![主界面](screenshots/main.png) -->
<!-- ![甘特图编辑](screenshots/gantt.png) -->

## 许可证

Copyright © 2026 横道图 Gantt

## 联系方式

如有问题或建议，欢迎提交 [Issue](https://github.com/kail896/gantt-chart/issues)。
