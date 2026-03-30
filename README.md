# 🧜‍♀️ Mermaid Studio 

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)
![HTML5](https://img.shields.io/badge/HTML5-Strict-orange.svg)

**Mermaid Studio** 是一款开箱即用、由 AI 驱动的现代化 Mermaid 图表可视化编辑器。无需繁琐的语法记忆，只需通过自然语言描述，即可借助大模型（DeepSeek、Gemini、OpenAI 等）快速生成、优化并渲染专业的架构图、流程图、时序图及网络拓扑。

🔗 **在线免费体验**: [https://mermaid.cyber-sec.run](https://mermaid.cyber-sec.run)

---

### 📸 界面预览
*(上传截图到 Github 后，请将这里的链接替换为实际的图片地址)*

<div align="center">
  <img src="https://via.placeholder.com/800x450.png?text=Mermaid+Studio+Dashboard" alt="主界面预览" width="80%">
  <br>
  <em>图 1：沉浸式编辑器主界面与实时自适应预览</em>
</div>

<br>

<div align="center">
  <img src="https://via.placeholder.com/800x450.png?text=AI+Assistant+in+Action" alt="AI 助手生成图表" width="80%">
  <br>
  <em>图 2：内置 AI 助手，通过自然语言一键生成与优化代码</em>
</div>

---

## ✨ 核心特性

- 🤖 **AI 智能赋能**: 内置 AI 助手，支持 DeepSeek（推荐）、Gemini、OpenAI、Claude 等主流模型。支持一键从自然语言生成图表，或对现有代码进行智能纠错与优化。
- 🔒 **隐私与安全优先**: 纯前端 SPA 架构，零后端依赖。所有 API Key 及配置仅保存在浏览器的本地存储（Local/Session Storage）中，刷新不丢失，确保凭证绝对安全。
- 🔍 **无界漫游视图**: 独创的自适应居中算法，支持画布拖拽平移、鼠标滚轮无极缩放，彻底解决复杂架构图渲染后“忽大忽小”或溢出屏幕的问题。
- 📥 **超清纯净导出**: 深度修复了 Mermaid 原生导出时的背景透明、黑块等 Bug。支持一键导出带有完美安全边距的无损 SVG 和 2 倍超清 PNG 图像。
- 🎨 **双语与个性化主题**: 原生支持中/英双语无缝切换；提供深色/浅色模式，以及 Default、Forest、Neutral、Macaron 四种图表渲染引擎风格。
- 📚 **全场景模板内置**: 包含 10+ 种常用图表（流程图、序列图、甘特图、类图、状态图、ER 图、用户旅程图、思维导图、时间轴等）的丰富双语示例与语法备忘录。

---

## ⚙️ AI 助手配置说明

由于本工具极度注重隐私，我们不存储任何用户数据。首次使用 AI 功能前，请进行简单的本地配置：

1. 点击界面左下角的 **AI 助手** 栏目并展开。
2. 点击 **API Configuration (API 配置)**。
3. 选择您偏好的大模型服务商（推荐使用 DeepSeek，性价比高且代码生成能力极强）。
4. 填入对应的 API Endpoint 和您个人的 API Key。
5. 在输入框内输入你的制图需求，点击 **Generate (生成)** 即可体验魔法。

> **💡 提示**: 在您使用完毕或处于公共设备时，可点击配置面板下方的“清除本地凭证”按钮，一键安全销毁内存中的 Key。

---

## 🛠️ 技术栈

* **核心渲染**: [Mermaid.js](https://mermaid.js.org/) (v10+)
* **前端架构**: 原生 HTML5 / CSS3 / JavaScript (Vanilla JS)
* **图标库**: [FontAwesome 6.4.0](https://fontawesome.com/)

---

## 🤝 贡献指南

欢迎提交 Pull Request 或提出 Issue！如果您有新的图表模板建议、更好的 UI 交互想法或是发现了 Bug，请随时发起讨论。

---

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。您可以自由地使用、修改和分享，但请保留原作者信息。
