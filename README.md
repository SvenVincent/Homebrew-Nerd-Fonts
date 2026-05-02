# Nerd Fonts批量安装脚本
![Shell Script](https://img.shields.io/badge/Shell-Script-brightgreen)
![Homebrew](https://img.shields.io/badge/Homebrew-Cask-blue)
![macOS](https://img.shields.io/badge/macOS-Compatible-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

一个功能强大的Shell脚本，用于批量安装和管理Nerd Fonts字体，支持智能检查、选择性安装和进度显示。

## 📋 功能特性

### ✨ 核心功能
- **智能检查**：自动检测字体是否已安装，避免重复安装
- **批量安装**：支持一次性安装所有70个Nerd Fonts字体
- **选择性安装**：支持按序号安装单个或多个字体
- **进度显示**：实时显示安装进度和状态
- **彩色输出**：使用颜色区分不同状态信息

### 🔧 高级特性
- **参数解析**：支持复杂参数格式（单个、多个、范围）
- **输入验证**：自动检查序号有效性（1-70）
- **去重处理**：避免重复安装相同字体
- **错误处理**：详细的错误提示和恢复机制
- **统计报告**：完整的安装统计和分类报告

## 🚀 快速开始

### 1. 下载脚本
```bash
# 下载脚本
curl -O https://raw.githubusercontent.com/yourusername/nerdfonts-installer/main/install_nerdfonts.sh

# 添加执行权限
chmod +x install_nerdfonts.sh
```
### 2. 查看帮助
```bash
./install_nerdfonts.sh -h
```
