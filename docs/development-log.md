# 开发日志 | Development Log

## 项目目标 | Project Goal

目标很简单：

打开终端 → 输入命令 → 粘贴 YouTube 链接 → 完成下载

## 开发过程 | Development Process

### Step 1 — 选择下载工具 | Finding a Download Tool

选择 yt-dlp 作为核心下载工具。

### Step 2 — 第一个问题：yt-dlp 无法识别 | yt-dlp Not Recognized

原因：Windows PATH 未正确配置。

收获：理解了 PATH 的作用。

### Step 3 — 理解 PATH | Understanding PATH

PATH 决定终端能够找到哪些命令。

### Step 4 — PowerShell 与 CMD | PowerShell vs CMD

不同终端环境下命令行为并不完全一致。

### Step 5 — 路径问题 | Path Issues

脚本运行目录影响相对路径。

### Step 6 — 中文路径问题 | Chinese Path Issues

中文路径可能影响命令行工具运行。

### Step 7 — bat 文件集成 | Batch File Integration

实现 yt-basic 与 yt-hd 命令。

### Step 8 — 下载目录管理 | Download Output Management

规范视频和封面的保存位置。

## 最终结果 | Final Result

最终实现：

- yt-basic
- yt-hd

输入 YouTube 链接即可完成下载。

## 个人总结 | Reflection

这是我第一次从真实需求出发，完成一个能够长期使用的小工具。
