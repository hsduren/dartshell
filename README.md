# DartShell

**专为 macOS 打造的专业 SSH 客户端**

**Professional SSH Client Built for macOS**

*更适合管理大量服务器*

---

## 📖 目录 / Table of Contents

- [中文介绍](#中文介绍)
- [English Introduction](#english-introduction)
- [功能特性](#功能特性)
- [安装指南](#安装指南)
- [使用指南](#使用指南)
- [版本对比](#版本对比)
- [常见问题](#常见问题)
- [技术支持](#技术支持)

---

## 中文介绍

DartShell 是一款专为 macOS 系统开发的 SSH 客户端应用，专为大容量服务器管理而设计。应用支持 Free 和 Pro 两个版本，提供完整的 SSH 连接、SFTP 文件管理和批量操作功能。

### 🎯 为什么选择 DartShell？

- **离线优先** - 无需登录注册，本地数据存储，支持局域网连接
- **隐私安全** - 绝不收集敏感数据，所有配置信息本地加密存储
- **专业高效** - 针对系统管理员和开发者的实际需求优化
- **持续迭代** - 根据用户反馈持续改进功能

### 🌟 核心优势

1. **macOS 原生体验** - 完美融入 macOS 系统
2. **批量管理能力** - 支持服务器分组、批量导入导出、批量命令执行
3. **多语言界面** - 内置中英文支持，轻松切换界面语言
4. **专业版功能** - 高级 SFTP 操作、端口转发、终端主题定制

---

## English Introduction

DartShell is an SSH client application specifically developed for macOS systems, designed for managing large numbers of servers. The application supports both Free and Pro versions, providing complete SSH connection, SFTP file management, and batch operation capabilities.

### 🎯 Why Choose DartShell?

- **Offline First** - No login required, local data storage, supports LAN connections
- **Privacy & Security** - Never collects sensitive data, all configurations stored locally with encryption
- **Professional & Efficient** - Optimized for real-world needs of system administrators and developers
- **Continuous Iteration** - Continuous improvement based on user feedback

### 🌟 Key Advantages

1. **Native macOS Experience** - Perfect integration with macOS, supports Touch Bar and system gestures
2. **Batch Management** - Server grouping, batch import/export, batch command execution
3. **Multi-language Interface** - Built-in Chinese and English support, easy language switching
4. **Pro Features** - Advanced SFTP operations, port forwarding, terminal theme customization

---

## 功能特性 / Features

### 🔧 核心功能 / Core Features

#### SSH 连接管理 / SSH Connection Management
- **安全存储** - 密码和私钥安全保存，支持多种认证方式
- **连接历史** - 自动保存连接记录，快速重连
- **自动重连** - 网络中断后自动重新连接
- **登录脚本** - 支持连接后自动执行预设命令
- **跳板机支持** - 支持多级跳板机连接，访问内网服务器

#### SFTP 文件管理 / SFTP File Management
- **直观浏览** - 图形化文件浏览器，支持文件夹导航
- **拖拽操作** - 直接拖拽文件进行上传下载
- **批量传输** - 支持多文件和文件夹批量操作
- **权限管理** - 查看和修改文件权限
- **远程编辑** - 直接编辑远程文件（专业版）

#### 终端功能 / Terminal Features
- **丰富主题** - 15+ 内置主题，支持明暗切换
- **字体定制** - 可调节字体大小和样式
- **分屏显示** - 支持水平和垂直分屏
- **命令搜索** - 快速搜索终端历史命令
- **快捷片段** - 保存常用命令，一键执行

#### 批量操作 / Batch Operations
- **服务器分组** - 按项目或环境对服务器进行分组管理
- **批量命令** - 对分组内所有服务器执行相同命令
- **配置管理** - 导出导入服务器配置，便于备份和分享
- **端口转发** - 管理本地和远程端口转发规则

### 🖥️ 用户界面 / User Interface

- **现代化设计** - 遵循 macOS 设计规范，界面简洁美观
- **深色模式** - 专注深色主题，保护眼睛
- **响应式布局** - 适配不同屏幕尺寸，支持窗口缩放
- **键盘快捷键** - 完整的键盘操作支持，提高效率

---

## 安装指南 / Installation Guide

### 📋 系统要求 / System Requirements

- **操作系统**: macOS 10.14 或更高版本
- **内存**: 至少 4GB RAM
- **存储**: 至少 500MB 可用空间
- **网络**: 支持局域网和互联网连接

### 📦 安装方式 / Installation Methods

#### 从 App Store 下载 / Download from App Store
1. 打开 Mac App Store 或直接访问：[DartShell Pro on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12)
2. 点击"获取"按钮进行下载和安装

### 🚀 首次启动 / First Launch

1. 从 Applications 文件夹启动 DartShell
2. 授予必要的系统权限（网络访问、文件访问等）
3. 选择界面语言（中文/English）
4. 开始添加您的第一台服务器

---

## 使用指南 / User Guide

### 🏠 主界面介绍 / Main Interface Overview

应用主界面分为以下几个区域：

- **侧边栏** - 显示服务器列表和分组
- **工具栏** - 提供常用操作按钮
- **标签页** - 管理多个 SSH 连接
- **状态栏** - 显示连接状态和系统信息

### 🔧 添加服务器 / Adding Servers

1. **点击"新建主机"按钮**
2. **填写基本信息**：
   - 名称：为服务器起一个容易识别的名字
   - IP 或域名：服务器地址
   - 端口：SSH 端口（默认 22）
   - 用户名：登录用户名
3. **选择认证方式**：
   - 密码认证：输入登录密码
   - 密钥认证：选择私钥文件
4. **配置高级选项**（可选）：
   - 选择或创建分组
   - 设置登录脚本
   - 配置代理设置
5. **点击"连接"测试配置**

### 📁 使用 SFTP 文件管理 / Using SFTP File Management

1. **建立 SSH 连接**
2. **点击工具栏的"SFTP"按钮**
3. **文件操作**：
   - 双击文件夹进入目录
   - 右键文件查看操作菜单
   - 拖拽文件到本地进行下载
   - 拖拽本地文件到远程进行上传

### ⚙️ 终端定制 / Terminal Customization

1. **打开设置界面**
2. **选择"终端主题"选项卡**
3. **浏览和选择主题**：
   - 预览主题效果
   - 调整字体大小
   - 自定义颜色方案
4. **保存设置**

### 🔀 分屏操作 / Split Screen Operations

1. **打开多个 SSH 连接**
2. **右键点击标签页**
3. **选择分屏方向**：
   - 水平分割：上下排列终端
   - 垂直分割：左右排列终端（专业版功能）

---

## 版本对比 / Version Comparison

### 🆓 免费版功能 / Free Version Features

| 功能类别 | 具体功能 | 限制说明 |
|---------|---------|---------|
| **服务器管理** | 添加、编辑、删除服务器 | 最多 3 台服务器 |
| **SSH 连接** | 基本连接、命令执行、跳板机 | 无限制，支持多级跳板机 |
| **终端功能** | 基础终端操作、终端主题 | 仅限前 3 个内置主题 |
| **SFTP 基础** | 文件浏览、下载上传 | 单线程，100MB 文件大小限制 |
| **SFTP 限制** | 文件夹上传、拖拽上传 | 不支持文件夹上传和拖拽上传 |
| **端口转发** | 本地和远程转发 | 1 个转发规则 |
| **分屏功能** | 水平分屏 | 不支持垂直分屏 |

### 💎 专业版功能 / Pro Version Features

| 功能类别 | 具体功能 | 专业版优势 |
|---------|---------|-----------|
| **服务器管理** | 无限制服务器数量 | 管理大量服务器，适合企业使用 |
| **SSH 连接** | 基本连接、命令执行、多级跳板机 | 复杂网络环境下的连接能力 |
| **终端功能** | 所有内置主题、字体大小调节 | 15+ 主题可供选择，完全个性化 |
| **SFTP 高级** | 多线程传输、文件夹上传 | 高效处理大文件和复杂目录结构 |
| **SFTP 便捷** | 拖拽上传、远程文件编辑 | 提升文件操作效率 |
| **端口转发** | 无限制转发规则 | 复杂网络环境配置 |
| **分屏功能** | 水平和垂直分屏 | 更灵活的布局选择 |

### 💰 升级到专业版 / Upgrade to Pro Version

**升级方式**：
- 应用内直接升级
- App Store 购买专业版：[DartShell Pro on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12)
- 一次性付费，永久使用

**升级后立即获得**：
- 无限制服务器管理
- 所有高级功能解锁
- 优先技术支持
- 免费功能更新

---

## 常见问题 / Frequently Asked Questions

### 🔧 连接问题 / Connection Issues

**Q: 无法连接到服务器怎么办？**
A: 请检查以下项目：
- 网络连接是否正常
- 服务器地址和端口是否正确
- 用户名和密码是否准确
- 服务器 SSH 服务是否开启

**Q: 连接经常中断怎么办？**
A: 尝试以下解决方案：
- 检查网络稳定性
- 启用自动重连功能
- 调整连接超时设置

### 📁 文件传输问题 / File Transfer Issues

**Q: 文件上传失败怎么办？**
A: 可能的原因和解决方案：
- 检查目标路径是否有写入权限
- 确认磁盘空间是否充足
- 验证文件名是否包含特殊字符

**Q: 大文件传输很慢怎么办？**
A: 建议使用专业版的多线程传输功能，可以显著提升传输速度。

### 🎨 界面问题 / Interface Issues

**Q: 如何切换界面语言？**
A: 在设置界面找到"语言"选项，选择中文或 English 即可。

**Q: 字体太小看不清楚怎么办？**
A: 在设置中可以调整终端字体大小，选择适合您的显示效果。

---

## 技术支持 / Technical Support

### 📞 联系我们 / Contact Us

- **Discord 社区**: [https://discord.gg/7nEQspHK](https://discord.gg/7nEQspHK)
- **微信群**: 在设置中查看微信二维码加入用户群
- **应用内反馈**: 设置 → 技术支持

### 🆘 获取帮助 / Getting Help

**优先推荐的支持方式**：

1. **应用内帮助** - 查看内置的使用指南和教程
2. **常见问题** - 浏览 FAQ 部分，快速找到解决方案
3. **社区论坛** - 与其他用户交流经验和技巧
4. **技术支持** - 遇到复杂问题时直接联系技术团队

### 📝 反馈建议 / Feedback & Suggestions

我们非常重视用户的反馈和建议：

- **功能建议** - 告诉我们您希望添加的新功能
- **问题报告** - 详细描述遇到的问题，帮助我们改进
- **使用体验** - 分享您的使用心得和改进建议

**反馈渠道**：
- Discord 社区讨论
- 微信用户群交流
- 应用内反馈功能

### 🔄 更新与维护 / Updates & Maintenance

**自动更新**：
- 应用会自动检查更新
- 推荐开启自动更新功能
- 重要安全更新会强制安装

**更新内容**：
- 新功能添加
- 性能优化
- 安全漏洞修复
- 用户体验改进

---

<div align="center">

**感谢选择 DartShell！**
**Thank you for choosing DartShell!**

🚀 **提升您的服务器管理效率** / **Boost Your Server Management Efficiency**

[📱 App Store 下载 / Download on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12) | [💬 Discord 社区 / Discord Community](https://discord.gg/7nEQspHK) | [📱 微信群 / WeChat Group](设置中查看二维码)

</div>
