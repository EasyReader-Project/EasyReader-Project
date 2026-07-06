# 📚 EasyReader Project · 为你定制的跨平台阅读器

> **自由定制 · 数据自主 · 原生流畅**

EasyReader Project 是一款面向深度阅读者的开源阅读软件。我们不替你决定“该怎么读书”，而是提供一套灵活、干净、可自由组合的工具，让你在 Windows 和 Android 设备上搭建完全属于自己的阅读环境。

---

## ✨ 为什么选择 EasyReader Project？

### 🎨 真正的“高自由度”定制
- **翻页手势随心定义**：单击、双击、长按、滑动 —— 左右上下，每个区域的动作都可由你独立映射。
- **渲染引擎自由切换**：同一本 EPUB，你可以选用不同的渲染内核（WebView / MiniBlink），获得不同的排版效果和兼容性。
- **主题与样式深度覆盖**：支持导入自定义 CSS，彻底覆盖书籍原有样式，也可以一键切换深色、护眼或墨水屏模式。
- **全局字体替换**：无视书籍内嵌限制，强制使用你喜欢的字体。

### 📱 跨平台一致体验
- Windows 桌面端与 Android 手机端共享同一套进度和笔记数据，无缝接力阅读。
- 两端交互逻辑保持一致，切换设备无需重新适应。

### 🔒 数据完全由你掌控
- **书籍文件** 通过 Syncthing 进行 P2P 同步，不经过任何第三方服务器。
- **阅读进度与笔记** 支持备份到任意 WebDAV 服务（如自建 NAS、Nextcloud 等），数据永远在你手中。
- 智能进度保存机制，确保合上书本后，无论何时打开都能精准回到上次位置。

### 🚀 纯净、快速、无干扰
- 专注于阅读本身，没有社交、广告或推荐算法。
- 原生性能优化，大体积 PDF 和 EPUB 也能流畅翻页。

---

## 🧭 项目仓库

本项目由三个独立仓库协同管理：

| 仓库 | 作用 |
| :--- | :--- |
| [EasyReader-Specs](https://github.com/EasyReader-Project/EasyReader-Specs) | 公共规范与测试用例（供开发者参考） |
| [EasyReader-Win](https://github.com/EasyReader-Project/EasyReader-Win) | Windows 桌面端源码 |
| [EasyReader-Android](https://github.com/EasyReader-Project/EasyReader-Android) | Android 移动端源码 |

---

## 🖥️ 快速开始（开发者）

如果你想本地构建或参与开发：