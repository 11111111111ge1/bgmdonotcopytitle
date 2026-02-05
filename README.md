# BGM用户名和条目标题去超链接

一个简单的用户脚本，用于移除 bgm.tv（Bangumi）网站中用户名、条目标题、人物名称的超链接，方便复制文本。

## 功能特性

- ✅ 移除个人用户页面中的用户名超链接
- ✅ 移除条目页面中的标题超链接
- ✅ 移除人物页面（现实人物/虚拟角色）中的名称超链接
- ✅ 支持 bgm.tv、bangumi.tv、chii.in 三个主站域名
- ✅ 自动监听页面变化，适用于动态加载内容

## 安装方法

### 方法一：通过超合金组件安装（推荐）

本脚本已上传到 Bangumi 超合金组件平台，登录后即可一键启用：

**[在超合金组件平台查看](https://bgm.tv/dev/app/5543)**

超合金组件是 Bangumi 官方的前端组件库，提供强大的功能增强：
- ✨ 轻量级，高性能
- 🔧 模块化设计，按需使用
- 🎯 丰富的用户交互功能

### 方法二：通过用户脚本管理器安装

#### 1. 安装用户脚本管理器

首先需要在浏览器中安装用户脚本管理器扩展：

- **Chrome/Edge**: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
- **Firefox**: [Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/) 或 [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/)
- **Safari**: [Tampermonkey](https://apps.apple.com/app/tampermonkey/id1482490089)

#### 2. 安装脚本

点击下面的链接安装脚本：

**[点击安装](https://github.com/YOUR_USERNAME/bgmdonotcopytitle/raw/main/remove_link.js)**

或者手动安装：
1. 打开 Tampermonkey 管理面板
2. 点击"添加新脚本"
3. 复制 [remove_link.js](remove_link.js) 的内容
4. 粘贴到编辑器中并保存

## 使用说明

安装完成后，脚本会自动在以下页面生效：

- 用户页面：`https://bgm.tv/user/*`
- 条目页面：`https://bgm.tv/subject/*`
- 列表页面：`https://bgm.tv/*/list/*`
- 人物页面：`https://bgm.tv/person/*`
- 角色页面：`https://bgm.tv/character/*`

访问这些页面时，相关的超链接会自动被移除，你可以直接选中文本进行复制。

## 支持的网站

- bgm.tv
- bangumi.tv
- chii.in

## 更新日志

### v1.3
- 新增支持人物页面（现实人物和虚拟角色）
- 优化代码结构

### v1.2
- 新增支持条目页面标题去超链接
- 支持三个主站域名

### v1.0
- 初始版本
- 支持用户页面用户名去超链接

## 问题反馈

如果遇到问题或有功能建议，欢迎提交 [Issue](https://github.com/YOUR_USERNAME/bgmdonotcopytitle/issues)。

## 许可证

MIT License
