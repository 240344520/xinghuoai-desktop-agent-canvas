<p align="center">
  <img src="assets/logo.png" width="92" alt="薪火 AI 小火苗标识" />
</p>

<p align="center"><a href="README.md">简体中文</a> · <a href="README.en.md">English</a></p>

<h1 align="center">薪火 AI｜macOS AI 创作画布</h1>

<p align="center">在一张可自由缩放、平移的无限画布里，创作、管理与预览图片、视频、音频和文本。</p>

<p align="center">
  <a href="https://github.com/240344520/xinghuoai-desktop-agent-canvas/releases/latest"><img src="https://img.shields.io/badge/下载-最新版-orange.svg" alt="下载最新版" /></a>
  <img src="https://img.shields.io/badge/platform-macOS-black.svg" alt="macOS" />
  <img src="https://img.shields.io/badge/核心体验-免费本地使用-orange.svg" alt="免费本地使用" />
</p>

<p align="center">
  <img src="images/canvas-detail.png" alt="薪火 AI 的多媒体创作画布" />
</p>

## 为什么值得下载

- **免费、本地优先**：薪火 AI 可免费下载和本地使用。画布、资产管理、媒体预览与本地编辑围绕你的 Mac 工作，不把你的创作素材锁进单一网页产品。
- **清爽、严格打磨的交互体验**：从画布平移缩放、节点选择与拖拽，到媒体预览、参数编辑和创作协作，都追求克制、顺手、少打扰的反馈，让用户把注意力留给创作本身。
- **模型不绑定**：可接入主流云端模型 API 与 OpenAI 兼容接口，也支持本地模型（如 Ollama）。你可按任务自由选择模型与服务商，而不是被单一模型生态限制。
- **一张无限画布，处理多种创作素材**：把图片、视频、音频、文本、提示词、参数与结果放在同一张可自由缩放、平移的画布上，让创作过程可见、可整理、可继续。
- **AI Agent 协作与可扩展工作流**：Agent 可理解当前画布上下文；通过 MCP 连接工具，通过 Skills 扩展可复用的创作方法，组合成适合自己的工作流。

> 云端模型、外部 MCP 服务和部分扩展能力使用你自己的服务商账户与访问凭据，实际费用、可用模型和额度以对应服务商为准。

## 为谁而做

- 想在一处整理图片、视频、音频、文本与创作结果的创作者。
- 需要用可视化节点串联素材、参数和 AI 创作流程的设计师、内容团队与独立开发者。
- 希望保留本地资产管理体验，同时按需接入 AI 生图、生成视频、生成音频或音乐服务的 macOS 用户。

## 下载安装

请前往 [Releases 下载最新版 DMG](https://github.com/240344520/xinghuoai-desktop-agent-canvas/releases/latest)：

- `arm64`：适用于 Apple Silicon（M 系列芯片）。
- `x64`：适用于 Intel Mac。

下载后打开 DMG，将“薪火 AI”拖入“应用程序”即可。若 macOS 在首次打开时显示安全提示，请按系统指引确认来源后再继续。

安装后，新建一个画布即可开始添加本地素材；图片、视频、音频等云端生成能力按你在应用中接入的服务、账户与额度提供。

## 功能概览

- **画布管理**：新建、查看和进入本地画布项目，并以节点组织创作素材与结果。
- **多媒体节点**：在画布中承载图片、文本、视频、音频等不同类型的内容。
- **无限画布**：自由缩放与平移画布，用节点组织素材、参数、任务和创作结果。
- **AI 多媒体创作**：按需接入服务后，可在画布中发起 AI 生图、生成视频、生成音频或音乐的创作任务。
- **节点操作**：提供上传、编辑、增强、全屏查看、创建模板和下载等常用入口。
- **创作参数面板**：在画布内选择模型、比例、尺寸等参数并提交创作需求。
- **资产管理**：按图片、视频、音频浏览本地作品，并将资产用于画布创作。
- **媒体预览**：放大查看素材、切换相邻内容，并可定位回对应画布。
- **AI Agent 创作协作**：在画布上下文中输入创作需求、查看结果并继续操作。

## 界面预览

| 画布列表 | 画布详情 |
| --- | --- |
| ![画布列表](images/canvas-list.png) | ![画布详情](images/canvas-detail.png) |

| 画布资产面板 | 创作协作面板 |
| --- | --- |
| ![画布资产面板](images/canvas-assets-panel.png) | ![创作协作面板](images/canvas-agent-drawer.png) |

| 节点工具栏 | 画布内创作参数面板 |
| --- | --- |
| ![节点工具栏](images/canvas-node-toolbar.png) | ![画布内创作参数面板](images/canvas-generation-panel.png) |

| 媒体资产库 | 媒体预览 |
| --- | --- |
| ![媒体资产库](images/canvas-media-library.png) | ![媒体预览](images/media-preview.png) |

## 使用说明与反馈

画布浏览、资产管理和本地编辑不要求安装开发环境。云端生成及部分外部能力取决于你在应用中接入的服务、账户、额度和个人访问凭据。

本仓库仅提供正式发布的应用安装包、产品介绍和界面预览，不包含产品源码、开发分支、构建脚本或内部文档。

如需反馈问题，请在 [Issues](https://github.com/240344520/xinghuoai-desktop-agent-canvas/issues) 中附上复现步骤、应用版本、macOS 版本、芯片架构和必要的脱敏日志；不要提交个人资料或访问凭据。
