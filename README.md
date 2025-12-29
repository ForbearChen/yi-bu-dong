# 移不动公司的时刻 📱

<div align="center">

**校园服务助手网页版**

一个模仿学校"移动公司的时候"app的趣味网页版本

[在线演示](https://forbearchen.github.io/yi-bu-dong/) | [功能特性](#功能特性) | [快速开始](#快速开始)

</div>

---

## 📖 项目简介

"移不动公司的时刻"是一个基于纯前端技术开发的校园服务助手网页应用，灵感来源于学校的移动应用平台。项目名称"移不动"是对"移动"的幽默谐音，体现了大学生活中那些既让人依赖又时常"卡顿"的校园服务系统的真实写照。

本项目采用 PWA（Progressive Web App）技术，支持添加到手机主屏幕，提供接近原生应用的使用体验。

## ✨ 功能特性

### 🎨 精美界面
- **蓝色渐变主题**：采用现代化的蓝色渐变设计（#2563eb → #3b82f6）
- **卡片式布局**：清爽的卡片式界面，阴影和圆角细节精致
- **响应式设计**：专为手机屏幕优化，完美适配各种移动设备

### 📊 核心功能模块
- **统计面板**：实时显示消息、预约、发起、待办数量
- **快捷操作**：付款码、充值、账单、交晓助快速入口
- **功能网格**：
  - 本科选课
  - 智慧缴费（热门）
  - 课表查询
  - 移动教务
  - 预约中心（热门）
  - 师生电子凭证综合服务
  - 电子校历
  - 迎新离校
  - 失物招领
  - 更多功能...

### 🎯 特色专区
- **预约中心**：便捷预约各类服务
- **智慧缴费**：快速缴费通道
- **智印通道**：智能打印服务

### 📱 PWA 支持
- **离线访问**：Service Worker 提供离线缓存
- **添加到主屏幕**：可作为独立应用使用
- **全屏体验**：隐藏浏览器地址栏，类原生应用体验

### 🎭 交互效果
- **点击反馈**：所有按钮都有流畅的点击动画
- **Toast 提示**：优雅的消息提示效果
- **底部导航**：5个导航选项，支持切换高亮
- **搜索框聚焦**：搜索时的微动效果

## 🛠️ 技术栈

本项目采用纯前端技术栈，无需后端服务器：

- **HTML5**：语义化标签，优化 SEO
- **CSS3**：
  - Flexbox & Grid 布局
  - 渐变、阴影、动画
  - 响应式设计
- **JavaScript (ES6+)**：
  - Service Worker API
  - DOM 操作
  - 事件处理
- **PWA**：
  - Web App Manifest
  - Service Worker
  - 离线缓存策略
- **Font Awesome**：图标库（CDN）
- **GitHub Pages**：静态网站托管

## 🚀 快速开始

### 在线访问

直接访问在线演示：**[https://forbearchen.github.io/yi-bu-dong/](https://forbearchen.github.io/yi-bu-dong/)**

### 本地运行

由于是纯静态网页，您可以直接打开 HTML 文件，或使用任何 HTTP 服务器：

#### 方法 1：直接打开
```bash
# 克隆仓库
git clone https://github.com/ForbearChen/yi-bu-dong.git
cd yi-bu-dong

# 直接用浏览器打开 index.html
```

#### 方法 2：使用 Python HTTP 服务器
```bash
# Python 3
python -m http.server 8000

# 访问 http://localhost:8000
```

#### 方法 3：使用 Node.js HTTP 服务器
```bash
# 安装 http-server
npm install -g http-server

# 运行服务器
http-server -p 8000

# 访问 http://localhost:8000
```

## 📲 添加到手机主屏幕

让"移不动"像原生 App 一样使用！

### iOS (Safari)

1. 打开 Safari 浏览器，访问 [https://forbearchen.github.io/yi-bu-dong/](https://forbearchen.github.io/yi-bu-dong/)
2. 点击底部工具栏的 **分享按钮**（方框带向上箭头 <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' fill='%23007AFF' viewBox='0 0 16 16'%3E%3Cpath d='M8 0l3 3h-2v5H7V3H5l3-3z'/%3E%3Cpath d='M2 6h3v1H2v7h12V7h-3V6h3a1 1 0 011 1v7a1 1 0 01-1 1H2a1 1 0 01-1-1V7a1 1 0 011-1z'/%3E%3C/svg%3E" style="vertical-align: middle;">）
3. 在弹出菜单中向下滚动，找到 **"添加到主屏幕"**
4. 点击右上角的 **"添加"** 确认
5. 完成！现在可以从主屏幕直接打开应用

### Android (Chrome)

1. 打开 Chrome 浏览器，访问 [https://forbearchen.github.io/yi-bu-dong/](https://forbearchen.github.io/yi-bu-dong/)
2. 点击右上角的 **菜单按钮**（三个点 ⋮）
3. 选择 **"添加到主屏幕"** 或 **"安装应用"**
4. 在弹出的对话框中点击 **"添加"** 或 **"安装"**
5. 完成！应用图标会出现在主屏幕上

### 其他浏览器

- **Microsoft Edge**：菜单 → 应用 → 安装此站点为应用
- **Firefox**：菜单 → 安装
- **Samsung Internet**：菜单 → 添加页面到

## 🎨 设计规范

### 颜色系统
```css
主题蓝色：#2563eb
渐变蓝色：linear-gradient(135deg, #2563eb 0%, #3b82f6 100%)
浅蓝背景：#f0f9ff
浅紫背景：#f5f3ff
文字黑色：#333
文字灰色：#666
边框颜色：#e5e7eb
热标签红色：#ff6b6b
```

### 布局规范
- 圆角：12px
- 卡片阴影：`box-shadow: 0 2px 10px rgba(0,0,0,0.05)`
- 触摸区域最小：44x44px
- 页面留白：16px

### 字体系统
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```

## 📁 项目结构

```
yi-bu-dong/
├── index.html              # 主页面
├── manifest.json           # PWA 配置文件
├── service-worker.js       # Service Worker 脚本
├── README.md              # 项目文档
└── .github/
    └── workflows/
        └── pages.yml       # GitHub Pages 自动部署
```

## 🔧 开发说明

### 代码特点
- **语义化 HTML**：使用 `<header>`, `<main>`, `<nav>` 等语义化标签
- **模块化 CSS**：按组件分类，注释清晰
- **原生 JavaScript**：无框架依赖，轻量快速
- **移动优先**：专为移动设备优化的触摸交互

### 性能优化
- 使用 CDN 加载外部资源（Font Awesome）
- Service Worker 缓存策略提高加载速度
- CSS 在 `<head>` 中，JavaScript 在 `<body>` 底部
- 禁用双击缩放，优化触摸体验

### 浏览器兼容性
- ✅ Chrome/Edge (推荐)
- ✅ Safari (iOS 11.3+)
- ✅ Firefox
- ✅ Samsung Internet

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支：`git checkout -b feature/AmazingFeature`
3. 提交更改：`git commit -m 'Add some AmazingFeature'`
4. 推送到分支：`git push origin feature/AmazingFeature`
5. 提交 Pull Request

## 📄 开源协议

本项目采用 MIT 协议 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🙏 致谢

- 图标来自 [Font Awesome](https://fontawesome.com/)
- 灵感来源于校园移动应用平台
- 感谢所有贡献者

## 📮 联系方式

- GitHub: [@ForbearChen](https://github.com/ForbearChen)
- Project Link: [https://github.com/ForbearChen/yi-bu-dong](https://github.com/ForbearChen/yi-bu-dong)

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给它一个 Star！**

Made with ❤️ by ForbearChen

</div>
