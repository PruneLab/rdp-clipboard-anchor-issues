# ⚓ RDP Clipboard Anchor (远程桌面剪贴板锚点)

<p align="left">
  <a href="https://apps.microsoft.com/store/detail/9PNGHSMN43W9">
    <img src="https://img.shields.io/badge/微软商店-立即获取-0078D7?style=for-the-badge&logo=windows" alt="Get it from Microsoft Store">
  </a>
  <img src="https://img.shields.io/badge/平台-Windows_11-blue?style=for-the-badge&logo=windows11" alt="Platform">
  <img src="https://img.shields.io/badge/版本-v1.1.0.0-success?style=for-the-badge" alt="Current Version">
  <img src="https://img.shields.io/badge/隐私-100%25_离线安全-lock?style=for-the-badge&color=critical" alt="100% Offline & Secure">
</p>

[English Version](README.md)

---

**强大的 Win+V 高阶平替。完美支持文件、图片与文本等富格式，自动缓存并防止 RDP 远程桌面断连导致的数据丢失。100% 离线，安全可靠。**

### 🛑 你需要的 RDP 守护锚点
你是否经历过这样的崩溃瞬间：在远程服务器上刚复制了一段关键代码或重要文件，RDP 桌面突然卡顿或掉线？等你重新连上，本地剪贴板早已空空如也。

**RDP Clipboard Anchor** 正是为解决这一痛点而生。它安全地运行在你的本地电脑上，静默接管并缓存跨会话的复制事件。当远程桌面 (RDP) 异常断开时，你的数据会被稳稳“锚定”在本地，随时可以粘贴或拖拽。告别网络波动带来的效率灾难。

### 🚀 原生 Win+V 的完美高阶平替
不仅仅是 RDP 伴侣，它更是一款专为开发者和效率控打造的高级剪贴板管理中枢，全面碾压 Windows 自带的 Win+V：
* **富文本与大文件支持：** 完美接管图片、复杂数据结构甚至大文件，远超原生工具的纯文本限制。
* **丝滑拖拽交互 (Drag & Drop)：** 直接从历史记录中将文件或图片拖入其他软件或文件夹，一气呵成。
* **智能缓存管理：** 提供自定义存储配额与自动清理机制，告别 C 盘空间焦虑，时刻保持轻量高效。
* **快捷执行：** 双击记录即可快速打开或触发响应动作。
* **原生级 UI 体验：** 基于最新 Windows App SDK (WinUI 3) 打造，完美融入 Windows 11 现代设计语言，轻量且优雅。

### 🛡️ 100% 纯本地与绝对安全
本软件承诺 100% 纯本地运行，无任何联网权限，零后台遥测。此外，它还能智能识别并自动忽略来自 1Password 等主流密码管理器的复制动作。你的隐私，完全由你掌控。

---

## 🛠️ 问题反馈与建议

本仓库主要用于收集用户的 Bug 反馈与新功能建议。
*(注：核心应用程序为闭源软件。)*

* 🐛 **[提交 Bug 反馈](../../issues/new)**：如果您发现了任何异常，请告诉我们！
* ✨ **[提交功能建议](../../issues/new)**：如果您有任何能让应用变得更好的点子，欢迎提出。

---

## 🗺️ 开发路线图

我们正在积极地打磨并优化应用：
- [x] **v1.1.0.0**: 交互体验打磨、智能缓存管理、可靠性提升 *(已发布)*
- [ ] **v1.2.0.0**: 多语言支持 (i18n) - *首批计划：繁体中文、日语、德语。*
- [ ] **v1.2.0.0+**: 全局搜索、图片/长文本快速预览、条目固定与置顶、全局快捷键支持。