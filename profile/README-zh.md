<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NarraLeaf/.github/refs/heads/master/doc/banner-md-transparent.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NarraLeaf/.github/refs/heads/master/doc/banner-md-light.png">
  <img alt="Fallback image description" src="https://raw.githubusercontent.com/NarraLeaf/.github/refs/heads/master/doc/banner-md-light.png">
</picture>

# NarraLeaf

[English](./README.md) | 中文

重新定义视觉小说的可能性。

## 我们是谁？

我们是一个致力于构建更轻量、更快速、更面向开发者的视觉小说引擎的团队。

NarraLeaf 是一个基于 React 的轻量级视觉小说引擎，专为速度和开发者可控性而生。用最少的代码和最大的灵活性，构建并打包跨平台的视觉小说。

## 为什么选择我们？

- ⚡ **更轻量** – 零渲染引擎，开销极小，优化运行于大多数低配设备。
- 🔧 **更快速** – 可定制的应用和内置自动化（如 CI 和代码规范检查）让你更高效地开发。
- 💻 **更友好开发者体验** – 标准前端开发流程，严格类型支持，无语言依赖。

### 🔍 视觉小说引擎对比 – 优劣分析

以下对比有助于开发者根据项目需求选择合适的工具。

| 功能 / 工具                              | **NarraLeaf (React/TypeScript)**                  | **Ren’Py (Python)**                                 | **TyranoBuilder (图形界面)**                          |
|------------------------------------------|--------------------------------------------------|----------------------------------------------------|--------------------------------------------------------|
| 🚀 **轻量性能表现**                       | ✅ 零渲染引擎，低配设备也可流畅运行               | ⚠️ 运行开销中等                                   | ⚠️ 渲染较重，可能影响低配设备性能                    |
| ⚛️ **现代 Web 技术支持**                 | ✅ 基于 React + TypeScript                        | ❌ 基于 Python，Web 支持受限                      | ⚠️ 支持部分 JavaScript                               |
| 🧱 **组件化架构**                         | ✅ 模块化结构，组件可复用                         | ❌ 线性脚本结构                                   | ❌ 自定义受限，仅限图形编辑器内                     |
| 📦 **跨平台构建能力**                     | ✅ 支持 Web 与桌面（Electron）打包               | ✅ 多平台支持                                     | ✅ 多平台支持                                       |
| 🧠 **技术门槛**                           | ⚠️ 需掌握 JavaScript / React / TypeScript        | ✅ Python 脚本友好，适合初学者                    | ✅ 无需编程，拖拽操作                               |
| 💬 **脚本语言**                           | 🟡 正在开发（NarraLang 脚本语言）            | ✅ 稳定的 Ren'Py Script（基于 Python）            | ✅ 简单的图形脚本界面                               |
| 🧩 **扩展性**                             | ✅ 可使用完整的 React 生态                       | ⚠️ 可通过 Python 模块扩展                        | ⚠️ 内置功能外扩展性有限                            |
| 🌍 **多语言本地化支持**                   | 🟡 需手动配置或依赖社区插件                      | ✅ 内建多语言与字体支持                          | ✅ 内建语言切换功能                                |
| 🖼️ **图形界面编辑器 / 可视化工具**        | ❌ 尚未推出（目前为纯代码 + CLI 流程）           | ✅ 提供基础 GUI 管理脚本                         | ✅ 完整可视化编辑器                                |
| 🎨 **UI 主题 / 可视化模板**               | 🟡 正在开发（NarraUI界面组件库）                    | ⚠️ 可通过 ATL 脚本与配置文件定制                | ✅ 内建可视化主题与模板                            |

## 解决方案

### [NarraLeaf](https://github.com/NarraLeaf/NarraLeaf) – 桌面端完整解决方案

> **更少代码，更高效率**

创建、构建和打包桌面端视觉小说应用。  
专注于跨平台桌面应用，内置 NarraLeaf-React、本地存档支持以及基于页面的路由系统。通过命令行工具提供开发与打包功能。

- 桌面端开发（Electron）
- 内建开发服务器与打包工具
- 本地存储支持，页面级路由控制
- 内置前端视图引擎（NarraLeaf-React）

### [NarraLeaf-React](https://github.com/NarraLeaf/narraleaf-react) – 内嵌式 VN 播放器解决方案

> **高度可定制性**

一个专为 React 打造的轻量前端视觉小说播放器。  
专注于舞台表现，内置图像、对话与可扩展组件体系。

- 适用于网页或自定义前端项目
- 完整的舞台管理系统（Stage Manager）
- React 组件化结构，支持扩展与自定义
- 可独立嵌入任意 React 应用

## 项目展示

### react.narraleaf.com

NarraLeaf-React 的文档与演示站点。

> [react.narraleaf.com](https://react.narraleaf.com)

### NarraUI（规划中）

使用 NarraLeaf-React 插件快速定制所需的所有视觉小说组件。

> [NarraUI](https://github.com/NarraLeaf/NarraUI)

### NarraLang（规划中）

更简洁的语言，让你摆脱编码负担。

### NarraLeaf-Editor（规划中）

零代码可视化素材管理工具。
