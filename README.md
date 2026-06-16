<p align="center">
  <img src="https://img.shields.io/badge/status-live-brightgreen?style=flat" alt="Live">
  <img src="https://img.shields.io/badge/stack-HTML%2FCSS%2FJS-f7df1e?logo=javascript" alt="Stack">
  <img src="https://img.shields.io/badge/charts-Chart.js-ff6384?logo=chartdotjs" alt="Chart.js">
  <img src="https://img.shields.io/badge/deploy-GitHub_Pages-222222?logo=github" alt="GH Pages">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
</p>

<h1 align="center">DataArt — 数据可视化生成器</h1>

<p align="center"><strong>纯前端数据可视化工具 — 输入数据 → 选择图表 → 导出高清大图</strong></p>

<p align="center">
  <a href="https://3432926599-cyber.github.io/DataViz/"><strong>🌐 Live Demo</strong></a>
  ·
  <a href="#-快速开始"><strong>🏃 Quick Start</strong></a>
</p>

---

## ✦ 这是什么？

一个轻量级的纯前端数据可视化工具。无需后端、无需注册，直接在浏览器中输入数据，选择图表类型，即可生成并导出高清无水印的可视化图片。

---

## ✨ 功能

| 功能 | 说明 |
|------|------|
| 📊 **4 种图表** | 柱状图 · 折线图 · 饼图 · 甜甜圈图 |
| 📝 **数据输入** | 按页面示例格式填写，实时校验 |
| 🎨 **即时预览** | Canvas 渲染，所见即所得 |
| 📥 **高清导出** | 一键导出 PNG 大图，无水印 |
| 📱 **响应式** | 适配桌面 + 移动端浏览器 |
| 🔌 **零依赖构建** | 单个 HTML 文件 + Chart.js CDN |

---

## 🏃 快速开始

```bash
# 直接用浏览器打开
open index.html

# 或部署到任意静态服务器
npx serve .
```

### 使用流程

1. **选择图表类型** — 柱状图 / 折线图 / 饼图 / 甜甜圈图
2. **输入数据** — 按页面示例格式填写标签和数值
3. **生成图表** — 点击按钮，Canvas 实时渲染
4. **导出图片** — 下载高清 PNG

---

## 📁 项目结构

```
DataViz/
├── index.html              # 单页应用（Chart.js CDN）
├── avatar1.png             # 默认图标
└── README.md
```

---

## 🔧 技术栈

| 层 | 技术 |
|----|------|
| **框架** | 原生 HTML/CSS/JS |
| **图表库** | [Chart.js](https://www.chartjs.org/) (CDN) |
| **字体** | 系统字体栈（Microsoft YaHei / PingFang SC） |
| **导出** | Canvas `toDataURL()` → download link |
| **部署** | GitHub Pages |

---

## 🔗 相关链接

- **个人主页**：[supersuperchik-home.pages.dev](https://supersuperchik-home.pages.dev)
- **GitHub**：[3432926599-cyber](https://github.com/3432926599-cyber)

---

## 👤 作者

**SupersupErChik** — [GitHub](https://github.com/3432926599-cyber)

---

## 📄 License

MIT — 完全开源免费
