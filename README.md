# 🌟 WebUI Demo Agents

> 展示不同 AI Agent 平台可实现的 Web 交互效果，覆盖按钮、背景、文字、卡片、加载动画等常用场景，所有效果均为纯 CSS/JS 原生实现，无任何第三方依赖。

[![Pages](https://img.shields.io/badge/GitHub%20Pages-Online-brightgreen?style=flat-square)](https://superbishop.github.io/webui-demo-agents/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Platforms](https://img.shields.io/badge/Platforms-Hermes%20%7C%20Coze%20%7C%20OpenClaw-7c3aed?style=flat-square)](#支持的平台)

---

## 📌 项目简介

本项目用于集中展示和记录各 AI Agent 平台可实现的 Web 前端交互效果。每个效果均包含：

- ✅ **实时演示** — 可直接交互体验
- ✅ **核心关键词** — 直接用于 Agent 对话，快速获取代码
- ✅ **技术栈说明** — CSS / JavaScript 原生实现，无依赖

> **核心理念**：所见即所得，关键词即代码。让 AI Agent 使用者能够快速查询、复制和落地 Web 交互方案。

---

## 🔗 在线预览

| 平台 | 页面 | 地址 |
|------|------|------|
| **Hermes** | 交互效果展示 | [webui_demo_hermes.html](https://superbishop.github.io/webui-demo-agents/webui_demo_hermes.html) |
| **OpenClaw** | 效果展示 | [webui_demo_openclaw.html](https://superbishop.github.io/webui-demo-agents/webui_demo_openclaw.html) |
| **Coze** | 效果词典 | [webui_demo_coze.html](https://superbishop.github.io/webui-demo-agents/webui_demo_coze.html) |

> GitHub Pages 初次部署或更新后约有 1-2 分钟延迟，如页面未更新请稍后刷新。

---

## 🗂️ 效果分类总览

### 🔘 按钮效果
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 霓虹辉光按钮 | `霓虹辉光` `box-shadow` `::before 填充` | 边框辉光 + 填充动画 |
| 玻璃态按钮 | `玻璃态` `backdrop-filter: blur()` `rgba 背景` | 毛玻璃半透明效果 |
| 涟漪效果按钮 | `涟漪效果` `::after` `border-radius:50%` | 点击时圆形波纹扩散 |
| 粒子爆炸按钮 | `粒子爆炸` `--dx --dy CSS变量` `requestAnimationFrame` | 点击喷射彩色粒子 |
| 边框流动按钮 | `边框流动` `渐变边框` `background-size` | 彩虹边框无限流动 |
| 磁吸悬停按钮 | `磁吸悬停` `box-shadow 扩展` | 悬停时发光扩散 |
| 3D 按压按钮 | `3D按压` `transform: scale()` | 按下时有 3D 按压感 |
| 切换开关 | `滑块切换` `::after` `translateX` | iOS 风格开关 |

### 🌌 背景效果
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 极光背景 | `极光背景` `radial-gradient` `@keyframes` | 颜色柔和流动变换 |
| 星空背景 | `星空背景` `radial-gradient 点阵` | 闪烁星点，科幻氛围 |
| 粒子漂浮背景 | `粒子漂浮` `@keyframes translateY` | 上升粒子，氛围装饰 |
| 渐变网格背景 | `渐变网格` `repeating-linear-gradient` | 科技感动态网格 |
| 液态波纹背景 | `液态波纹` `radial-gradient 椭圆` | 有机液态波动效果 |
| 毛玻璃背景 | `毛玻璃` `backdrop-filter: blur()` | 磨砂玻璃通透感 |

### 🃏 卡片效果
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 3D 翻转卡片 | `3D翻转` `perspective` `rotateY` `backface-visibility` | 悬停水平翻转 |
| 悬浮上浮卡片 | `悬浮上浮` `translateY` `box-shadow` | 卡片浮起 + 阴影加深 |
| 边框渐变卡片 | `边框渐变` `-webkit-mask` `linear-gradient` | 彩虹边框环绕 |
| 玻璃态卡片 | `玻璃态卡片` `backdrop-filter` | 毛玻璃质感卡片 |
| 图片遮罩毛玻璃 | `图片遮罩` `::before 渐变` `transform: translateY` | 悬停时文字滑入 |
| 磁吸扭曲卡片 | `磁吸扭曲` `mousemove` `skew` | 卡片随鼠标轻微倾斜 |

### ✒️ 文字效果
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 3D 渐变文字 | `3D渐变文字` `background-clip: text` | 彩虹渐变字体 |
| 故障艺术文字 | `故障艺术` `text-shadow 多色` `@keyframes` | 色彩分离故障感 |
| 流光文字 | `流光文字` `::after` `clip-path` | 光效扫过文字表面 |
| 火焰文字 | `火焰文字` `text-shadow 多层橙红` | 燃烧火焰效果 |
| 霓虹发光文字 | `霓虹灯` `text-shadow 多层叠加` | 霓虹辉光呼吸动画 |
| 打字机效果 | `打字机` `width 0→Nch` `steps()` | 逐字出现 + 光标闪烁 |

### ⏳ 加载动画
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 跳动点加载器 | `跳动点` `animation-delay` `scale` | 三点交替上下跳动 |
| 旋转环加载器 | `旋转环` `border-radius:50%` `border-top-color` | 圆环旋转 |
| 脉冲球加载器 | `脉冲球` `scale` `opacity` | 球体脉冲呼吸 |
| 进度条加载器 | `进度条` `::after` `translateX` | 滑块在进度条内滑动 |

### 🖱️ 鼠标交互
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 鼠标拖尾 | `鼠标拖尾` `mousemove` `setTimeout` | 跟手残影效果 |
| 光点跟随 | `光点跟随` `transform translate` | 平滑圆点跟随光标 |
| 点击爆炸粒子 | `点击爆炸` `--dx --dy CSS变量` | 点击时粒子四散 |
| 磁性吸附 | `磁性吸附` `mousemove` `距离判断` | 元素被鼠标吸引 |

### 📜 滚动动画
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 滚动渐入 | `滚动渐入` `IntersectionObserver` | 元素进入视口淡入 |
| 视差滚动 | `视差滚动` `scroll 监听` `translateY` | 多层速度差 3D 感 |
| 粘性导航 | `粘性导航` `position:sticky` | 滚动时固定在顶部 |

### 🪟 其他组件
| 效果名称 | 核心关键词 | 视觉效果 |
|---------|-----------|---------|
| 发光边框输入框 | `发光边框` `:focus` `box-shadow` | 聚焦时外发光 |
| 浮动标签输入框 | `浮动标签` `label absolute` `:focus ~ label` | 标签随聚焦上浮 |
| 下划线滑动标签页 | `下划线滑动` `border-bottom` `display:none` | 下划线随切换滑动 |
| 居中弹窗 | `居中弹窗` `backdrop-filter:blur` `animation` | 毛玻璃遮罩 + 滑入 |
| Toast 提示 | `Toast提示` `fixed` `setTimeout` | 底部右侧弹出提示 |

---

## 🛠️ 技术栈

| 分类 | 技术 |
|------|------|
| **结构** | HTML5 语义化标签 |
| **样式** | CSS3（CSS Variables、Flexbox、Grid、@keyframes、Transition） |
| **交互** | 原生 JavaScript（ES6+，无框架） |
| **动画** | CSS Animation / Transition，requestAnimationFrame |
| **外部依赖** | ❌ **零依赖**，纯原生实现，可直接嵌入任何项目 |

---

## 🚀 快速使用

### 方式一：关键词直达
直接在 Agent 对话中发送效果关键词，即可获得完整代码：
```
示例：
- "把背景改成星空效果"
- "这个按钮加一个粒子爆炸效果"
- "文字加火焰效果"
- "给我一个玻璃态卡片"
```

### 方式二：复制完整页面
1. 下载对应的 `.html` 文件
2. 直接在浏览器中打开预览
3. 通过开发者工具（F12）查看源码，复制所需效果代码

### 方式三：嵌入现有项目
```html
<!-- 所有效果均为单文件实现，无任何外部依赖 -->
<!-- 直接将 CSS 和 JS 代码片段复制到你的项目中即可使用 -->
```

---

## 📂 项目结构

```
webui-demo-agents/
├── README.md                    # 项目说明文档
├── LICENSE                      # MIT 开源协议
├── webui_demo_hermes.html       # Hermes 平台效果展示（左侧导航+卡片网格布局）
├── webui_demo_openclaw.html     # OpenClaw 平台效果展示
└── webui_demo_coze.html         # Coze 平台效果词典
```

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 提交新效果
1. 在对应页面的分类区块下新增卡片
2. 卡片需包含：图标、标题、描述、效果演示、关键词标签
3. 关键词格式：`<span class="tag">关键词</span>`

### 报告问题
- 通过 [GitHub Issues](https://github.com/Superbishop/webui-demo-agents/issues/new) 描述问题
- 请注明：使用的平台、浏览器版本、问题描述和复现步骤

---

## 📄 开源协议

本项目基于 [MIT License](LICENSE) 开源，你可以免费使用、修改和分发，但请保留原作者署名。

---

## 📬 联系方式

- **GitHub Issues**: [提交新 Issue](https://github.com/Superbishop/webui-demo-agents/issues/new)
- **仓库地址**: https://github.com/Superbishop/webui-demo-agents

---

> 💡 **使用提示**：每个效果页面中的「关键词」区域是对接 AI Agent 的核心入口，直接发送关键词给 Agent，即可获得可投入生产使用的完整代码。
