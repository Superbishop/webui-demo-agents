# 🌟 WebUI Demo Agents

> 展示不同 Agent 平台可实现的 Web 交互效果，覆盖按钮、背景、文字、卡片、加载动画等常用场景。

[![Pages](https://img.shields.io/badge/GitHub%20Pages-Online-brightgreen?style=flat-square)](https://superbishop.github.io/webui-demo-agents/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-WebUI%20%7C%20Coze%20%7C%20Hermes-7c3aed?style=flat-square)](#支持的平台)

---

## 📌 项目简介

本项目用于集中展示和记录各 AI Agent 平台（WebUI、Coze、Heremes 等）可实现的 Web 前端交互效果。每个效果均包含：

- ✅ 实时演示（可交互体验）
- ✅ 核心关键词（可直接用于 Agent 对话）
- ✅ 技术栈说明（CSS / JavaScript 原生实现，无依赖）

> **目标**：帮助开发者和 AI Agent 使用者快速查询、复制和落地 Web 交互方案，降低重复造轮子的成本。

---

## 🎯 支持的平台

| 平台 | 页面文件 | 说明 |
|------|---------|------|
| **Hermes** | `webui_demo_hermes.html` | 基于原生 HTML/CSS/JS，展示 45+ 交互效果 |
| **Coze** | `webui_demo_coze.html` | 效果词典/索引页面，支持关键词速查 |

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
| **样式** | CSS3（CSS Variables、Flexbox、Grid、@keyframes） |
| **交互** | 原生 JavaScript（ES6+）|
| **动画** | CSS Animation / Transition，无第三方库 |
| **框架依赖** | ❌ 无（纯原生实现，可直接嵌入任何项目）|

---

## 🚀 快速使用

### 方式一：直接复制效果代码
1. 打开效果展示页面
2. 找到对应的效果卡片，查看「关键词」区域
3. 将关键词发送给 Agent，即可获取完整代码

### 方式二：嵌入到现有项目
```html
<!-- 直接将 HTML/CSS/JS 代码片段复制到你的项目中 -->
<!-- 所有效果均为单文件实现，无外部依赖 -->
```

### 方式三：通过 Agent 平台调用
```
示例 Prompts：
- "把背景改成星空效果"
- "这个按钮加一个粒子爆炸效果"
- "文字加火焰效果，代码给我"
```

---

## 📂 项目结构

```
webui-demo-agents/
├── README.md                 # 项目说明文档
├── LICENSE                   # MIT 开源协议
├── webui_demo_hermes.html    # Hermes 交互效果展示（主页面）
└── webui_demo_coze.html      # Coze 效果词典页面
```

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 提交新效果
1. 在对应页面的分类区块下新增卡片
2. 卡片需包含：图标、标题、描述、效果演示、关键词
3. 关键词格式：`<span class="tag">关键词</span>`

### 修复问题
- 优先通过 Issue 描述问题
- 提交 PR 时请注明修复内容和原因

---

## 📄 开源协议

本项目基于 [MIT License](LICENSE) 开源，你可以免费使用、修改和分发，但请保留原作者署名。

---

## 📬 联系方式

- **GitHub Issues**: [New Issue](https://github.com/Superbishop/webui-demo-agents/issues/new)
- **仓库地址**: https://github.com/Superbishop/webui-demo-agents

---

> 💡 **小提示**：直接在对话中描述你想要的效果（如"给我一个霓虹辉光按钮"），AI Agent 可直接生成对应代码并嵌入你的项目使用。
