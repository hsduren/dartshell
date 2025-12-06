# DartShell

**深度定制的专业 SSH 客户端**

*满足专业管理需求，且极具性价比*
官网: https://dartshell.com
---

## 🇨🇳 中文介绍

### 📖 目录
- [应用介绍](#应用介绍)
- [功能特性](#功能特性)
- [安装指南](#安装指南)
- [使用指南](#使用指南)
- [版本对比](#版本对比)
- [常见问题](#常见问题)
- [技术支持](#技术支持)

### 🎯 应用介绍

DartShell 是一款专为 macOS 深度定制的 SSH 客户端应用，专为大容量服务器管理而设计。应用支持 Free 和 Pro 两个版本，提供完整的 SSH 连接、SFTP 文件管理和批量操作功能。

#### 🌟 为什么选择 DartShell？

- **离线优先设计** - 无需登录注册，所有数据本地存储，即使断网也能正常使用，支持纯局域网环境
- **隐私安全保护** - 绝不收集任何用户数据，配置信息端到端加密存储，确保服务器信息安全
- **专业高效体验** - 专为系统管理员和开发者量身打造，批量操作、跳板机、端口转发等专业功能一应俱全
- **持续快速迭代** - 基于真实用户反馈持续优化更新，快速响应用户需求，不断改进用户体验
- **macOS 深度集成** - 完美融入系统界面，支持深色模式和原生交互
- **多语言无障碍** - 内置中英文界面，轻松切换，消除语言障碍，服务全球用户

#### 核心优势

1. **macOS 原生体验** - 完美融入 macOS 系统，遵循 Apple 设计规范，提供原生的用户体验
2. **批量管理能力** - 支持服务器分组、批量导入导出、批量命令执行，高效管理大量服务器
3. **多语言界面** - 内置中英文支持，轻松切换界面语言，适应不同用户需求
4. **专业版功能** - 高级 SFTP 操作、端口转发、终端主题定制，满足专业用户需求
5. **安全隐私保护** - 本地数据存储，端到端加密，绝不收集用户敏感信息
6. **离线优先设计** - 无需联网即可使用，支持局域网连接，随时随地管理服务器

### 🔧 功能特性

#### SSH 连接管理
- **安全存储** - 密码和私钥安全保存，支持多种认证方式
- **连接历史** - 自动保存连接记录，快速重连
- **自动重连** - 网络中断后自动重新连接
- **登录脚本** - 支持连接后自动执行预设命令
- **跳板机支持** - 支持多级跳板机连接，访问内网服务器

#### SFTP 文件管理
- **直观浏览** - 图形化文件浏览器，支持文件夹导航
- **拖拽操作** - 直接拖拽文件进行上传下载（专业版）
- **批量传输** - 支持多文件和文件夹批量操作
- **权限管理** - 查看和修改文件权限
- **远程编辑** - 直接编辑远程文件（专业版）

#### 终端功能
- **丰富主题** - 15+ 内置主题，免费版限制前 3 个主题
- **字体定制** - 可调节字体大小和样式
- **分屏显示** - 支持水平分屏，垂直分屏（专业版）
- **命令搜索** - 快速搜索终端历史命令
- **快捷片段** - 保存常用命令，一键执行

#### 批量操作
- **服务器分组** - 按项目或环境对服务器进行分组管理
- **批量命令** - 对分组内所有服务器执行相同命令
- **配置管理** - 导出导入服务器配置，便于备份和分享
- **端口转发** - 管理本地和远程端口转发规则

#### 用户界面
- **现代化设计** - 遵循 macOS 设计规范，界面简洁美观
- **深色模式** - 专注深色主题，保护眼睛
- **响应式布局** - 适配不同屏幕尺寸，支持窗口缩放
- **键盘快捷键** - 完整的键盘操作支持，提高效率

### 📦 安装指南

#### 系统要求
- **操作系统**: macOS 10.14 或更高版本
- **内存**: 至少 4GB RAM
- **存储**: 至少 500MB 可用空间
- **网络**: 支持局域网和互联网连接

#### 安装方式
**从 App Store 下载**：
1. 打开 Mac App Store 或直接访问：[DartShell Pro on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12)
2. 点击"获取"按钮进行下载和安装

#### 首次启动
1. 从 Applications 文件夹启动 DartShell
2. 授予必要的系统权限（网络访问、文件访问等）
3. 选择界面语言（中文/English）
4. 开始添加您的第一台服务器

### 📚 使用指南

#### 主界面介绍
应用主界面分为以下几个区域：
- **侧边栏** - 显示服务器列表和分组
- **工具栏** - 提供常用操作按钮
- **标签页** - 管理多个 SSH 连接
- **状态栏** - 显示连接状态和系统信息

#### 添加服务器
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
   - 配置跳板服务器
5. **点击"连接"测试配置**

#### 使用 SFTP 文件管理
1. **建立 SSH 连接**
2. **点击工具栏的"SFTP"按钮**
3. **文件操作**：
   - 双击文件夹进入目录
   - 右键文件查看操作菜单
   - 拖拽文件到本地进行下载
   - 拖拽本地文件到远程进行上传（专业版）

#### 终端定制
1. **打开设置界面**
2. **选择"终端主题"选项卡**
3. **浏览和选择主题**：
   - 预览主题效果
   - 调整字体大小
   - 自定义颜色方案（专业版提供更多主题）
4. **保存设置**

#### 分屏操作
1. **打开多个 SSH 连接**
2. **右键点击标签页**
3. **选择分屏方向**：
   - 水平分割：上下排列终端
   - 垂直分割：左右排列终端（专业版功能）

### ⚖️ 版本对比

#### 免费版功能
| 功能类别 | 具体功能 | 限制说明 |
|---------|---------|---------|
| **服务器管理** | 添加、编辑、删除服务器 | 最多 3 台服务器 |
| **SSH 连接** | 基本连接、命令执行、跳板机 | 无限制，支持多级跳板机 |
| **终端功能** | 基础终端操作、终端主题 | 仅限前 3 个内置主题 |
| **SFTP 基础** | 文件浏览、下载上传 | 单线程，100MB 文件大小限制 |
| **SFTP 限制** | 文件夹上传、拖拽上传 | 不支持文件夹上传和拖拽上传 |
| **端口转发** | 本地和远程转发 | 1 个转发规则 |
| **分屏功能** | 水平分屏 | 不支持垂直分屏 |

#### 专业版功能
| 功能类别 | 具体功能 | 专业版优势 |
|---------|---------|-----------|
| **服务器管理** | 无限制服务器数量 | 管理大量服务器，适合企业使用 |
| **SSH 连接** | 基本连接、命令执行、多级跳板机 | 复杂网络环境下的连接能力 |
| **终端功能** | 所有内置主题、字体大小调节 | 15+ 主题可供选择，完全个性化 |
| **SFTP 高级** | 多线程传输、文件夹上传 | 高效处理大文件和复杂目录结构 |
| **SFTP 便捷** | 拖拽上传、远程文件编辑 | 提升文件操作效率 |
| **端口转发** | 无限制转发规则 | 复杂网络环境配置 |
| **分屏功能** | 水平和垂直分屏 | 更灵活的布局选择 |

#### 升级到专业版
**升级方式**：
- 应用内直接升级
- App Store 购买专业版：[DartShell Pro on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12)
- 一次性付费，永久使用

**升级后立即获得**：
- 无限制服务器管理
- 所有高级功能解锁
- 优先技术支持
- 免费功能更新

### ❓ 常见问题

**Q: 免费版升级到专业版后，数据如何迁移？**
A: 通过导出导入功能实现数据迁移。在免费版的服务器列表中点击"导出"按钮，保存配置文件。安装专业版后，在服务器列表中点击"导入"按钮即可恢复所有服务器设置、分组信息和连接历史。

**Q: 如何与团队其他成员共享服务器配置？**
A: 可以通过修改配置路径到 iCloud 目录实现团队共享。将应用的数据目录移动到 iCloud Drive 目录下（如：~/Library/Mobile Documents/com~apple~CloudDocs/DartShell），团队成员即可通过 iCloud 同步配置文件。

### 🆘 技术支持

#### 联系我们
- **Discord 社区**: [https://discord.gg/7nEQspHK](https://discord.gg/7nEQspHK)
- **微信群**: 在设置中查看微信二维码加入用户群

#### 更新与维护
**更新机制**：
- 通过 App Store 进行更新分发
- 推荐开启自动更新功能
- 重要安全更新会及时推送

---

## 🇺🇸 English Introduction

### 📖 Table of Contents
- [App Introduction](#app-introduction)
- [Features](#features)
- [Installation Guide](#installation-guide)
- [User Guide](#user-guide)
- [Version Comparison](#version-comparison)
- [FAQ](#faq)
- [Technical Support](#technical-support)

### 🎯 App Introduction

DartShell is an SSH client application specifically customized for macOS systems, designed for managing large numbers of servers. The application supports both Free and Pro versions, providing complete SSH connection, SFTP file management, and batch operation capabilities.

#### 🌟 Why Choose DartShell?

- **Offline First Design** - No login or registration required, all data stored locally, works perfectly even without internet connection, supports pure LAN environments
- **Privacy & Security Protection** - Never collects any user data, end-to-end encrypted storage of all configurations, ensuring complete server information security
- **Professional & Efficient Experience** - Tailor-made for system administrators and developers, complete professional features including batch operations, jump hosts, port forwarding
- **Continuous Rapid Iteration** - Continuous optimization and updates based on real user feedback, quick response to user needs, constantly improving user experience
- **Deep macOS Integration** - Perfectly integrates with system interface, supports dark mode and native interactions
- **Multi-language Accessibility** - Built-in Chinese and English interfaces, easy switching, eliminates language barriers, serves global users

#### Key Advantages

1. **Native macOS Experience** - Perfect integration with macOS, follows Apple design guidelines, provides native user experience
2. **Batch Management** - Server grouping, batch import/export, batch command execution for efficient large-scale server management
3. **Multi-language Interface** - Built-in Chinese and English support, easy language switching to meet different user needs
4. **Pro Features** - Advanced SFTP operations, port forwarding, terminal theme customization for professional users
5. **Security & Privacy Protection** - Local data storage, end-to-end encryption, never collects user sensitive information
6. **Offline First Design** - Works without internet connection, supports LAN connections, manage servers anytime anywhere

### 🔧 Features

#### SSH Connection Management
- **Secure Storage** - Secure password and private key storage, supports multiple authentication methods
- **Connection History** - Auto-save connection records for quick reconnection
- **Auto-reconnection** - Automatically reconnect when network is interrupted
- **Login Scripts** - Support for automatically executing preset commands after connection
- **Jump Host Support** - Support for multi-level jump host connections to access internal servers

#### SFTP File Management
- **Intuitive Browsing** - Graphical file browser with folder navigation support
- **Drag & Drop Operations** - Direct drag and drop file upload/download (Pro version)
- **Batch Transfer** - Support for multi-file and folder batch operations
- **Permission Management** - View and modify file permissions
- **Remote Editing** - Direct remote file editing (Pro version)

#### Terminal Features
- **Rich Themes** - 15+ built-in themes, free version limited to first 3 themes
- **Font Customization** - Adjustable font size and style
- **Split Screen** - Support for horizontal split, vertical split (Pro version)
- **Command Search** - Quick search of terminal command history
- **Quick Snippets** - Save frequently used commands for one-click execution

#### Batch Operations
- **Server Grouping** - Group servers by project or environment
- **Batch Commands** - Execute same commands on all servers in a group
- **Configuration Management** - Export/import server configurations for backup and sharing
- **Port Forwarding** - Manage local and remote port forwarding rules

#### User Interface
- **Modern Design** - Follows macOS design guidelines, clean and beautiful interface
- **Dark Mode** - Focus on dark theme, eye protection
- **Responsive Layout** - Adapts to different screen sizes, supports window resizing
- **Keyboard Shortcuts** - Complete keyboard operation support for improved efficiency

### 📦 Installation Guide

#### System Requirements
- **Operating System**: macOS 10.14 or higher
- **Memory**: At least 4GB RAM
- **Storage**: At least 500MB available space
- **Network**: Support for LAN and internet connections

#### Installation Method
**Download from App Store**:
1. Open Mac App Store or visit directly: [DartShell Pro on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12)
2. Click "Get" button to download and install

#### First Launch
1. Launch DartShell from Applications folder
2. Grant necessary system permissions (network access, file access, etc.)
3. Select interface language (Chinese/English)
4. Start adding your first server

### 📚 User Guide

#### Main Interface Overview
The main interface is divided into the following areas:
- **Sidebar** - Displays server list and groups
- **Toolbar** - Provides common operation buttons
- **Tabs** - Manages multiple SSH connections
- **Status Bar** - Shows connection status and system information

#### Adding Servers
1. **Click "New Host" button**
2. **Fill in basic information**:
   - Name: Give your server an easily recognizable name
   - IP or Hostname: Server address
   - Port: SSH port (default 22)
   - Username: Login username
3. **Select authentication method**:
   - Password authentication: Enter login password
   - Key authentication: Select private key file
4. **Configure advanced options** (optional):
   - Select or create group
   - Set login script
   - Configure jump servers
5. **Click "Connect" to test configuration**

#### Using SFTP File Management
1. **Establish SSH connection**
2. **Click "SFTP" button in toolbar**
3. **File operations**:
   - Double-click folders to enter directories
   - Right-click files to see operation menu
   - Drag files to local for download
   - Drag local files to remote for upload (Pro version)

#### Terminal Customization
1. **Open settings interface**
2. **Select "Terminal Themes" tab**
3. **Browse and select themes**:
   - Preview theme effects
   - Adjust font size
   - Customize color schemes (Pro version offers more themes)
4. **Save settings**

#### Split Screen Operations
1. **Open multiple SSH connections**
2. **Right-click on tab**
3. **Select split direction**:
   - Horizontal split: Arrange terminals vertically
   - Vertical split: Arrange terminals horizontally (Pro version feature)

### ⚖️ Version Comparison

#### Free Version Features
| Feature Category | Specific Features | Limitations |
|---------|---------|---------|
| **Server Management** | Add, edit, delete servers | Maximum 3 servers |
| **SSH Connection** | Basic connection, command execution, jump host | Unlimited, supports multi-level jump hosts |
| **Terminal Features** | Basic terminal operations, terminal themes | Limited to first 3 built-in themes |
| **SFTP Basic** | File browsing, download/upload | Single thread, 100MB file size limit |
| **SFTP Limitations** | Folder upload, drag & drop upload | No folder upload or drag & drop support |
| **Port Forwarding** | Local and remote forwarding | 1 forwarding rule |
| **Split Screen** | Horizontal split | No vertical split support |

#### Pro Version Features
| Feature Category | Specific Features | Pro Advantages |
|---------|---------|-----------|
| **Server Management** | Unlimited server quantity | Manage large numbers of servers, suitable for enterprise use |
| **SSH Connection** | Basic connection, command execution, multi-level jump host | Connection capability for complex network environments |
| **Terminal Features** | All built-in themes, font size adjustment | 15+ themes to choose from, complete personalization |
| **SFTP Advanced** | Multi-threaded transfer, folder upload | Efficient handling of large files and complex directory structures |
| **SFTP Convenience** | Drag & drop upload, remote file editing | Improve file operation efficiency |
| **Port Forwarding** | Unlimited forwarding rules | Complex network environment configuration |
| **Split Screen** | Horizontal and vertical split | More flexible layout options |

#### Upgrade to Pro Version
**Upgrade Methods**:
- In-app direct upgrade
- Purchase Pro version on App Store: [DartShell Pro on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12)
- One-time payment, lifetime use

**Immediate Benefits After Upgrade**:
- Unlimited server management
- All advanced features unlocked
- Priority technical support
- Free feature updates

### ❓ FAQ

**Q: How to migrate data after upgrading from free to pro version?**
A: Data migration is achieved through export and import functionality. In the free version, click the "Export" button in the server list to save the configuration file. After installing the Pro version, click the "Import" button in the server list to restore all server settings, group information, and connection history.

**Q: How to share server configuration with team members?**
A: You can achieve team sharing by modifying the configuration path to iCloud directory. Move the application's data directory to iCloud Drive directory (e.g., ~/Library/Mobile Documents/com~apple~CloudDocs/DartShell), so team members can sync configuration files through iCloud.

### 🆘 Technical Support

#### Contact Us
- **Discord Community**: [https://discord.gg/7nEQspHK](https://discord.gg/7nEQspHK)
- **WeChat Group**: View WeChat QR code in settings to join user group

#### Updates & Maintenance
**Update Mechanism**:
- Updates are distributed through App Store
- Recommend enabling auto-update feature
- Important security updates are pushed promptly

---

<div align="center">

**感谢选择 DartShell！**
**Thank you for choosing DartShell!**

🚀 **提升您的服务器管理效率** / **Boost Your Server Management Efficiency**

[📱 App Store 下载 / Download on App Store](https://apps.apple.com/cn/app/dartshell-pro-ssh-sftp/id6504210872?mt=12) | [💬 Discord 社区 / Discord Community](https://discord.gg/7nEQspHK) | [📱 微信群 / WeChat Group](设置中查看二维码)

</div>
