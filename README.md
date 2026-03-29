# 🎮 AI 游戏创新监控

> 一站式追踪全球 AI + 游戏创新动态的可视化工具

**在线访问** → [https://albertfuzheng.github.io/ai-gameplay-monitor/](https://albertfuzheng.github.io/ai-gameplay-monitor/)

![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue)
![Products](https://img.shields.io/badge/Products-30+-orange)
![Auto Daily](https://img.shields.io/badge/Daily%20Report-Auto%20Generate-green)

---

## 📖 项目简介

AI 游戏创新监控是一个面向游戏策划和行业研究者的工具型网站。它通过 **交互式气泡图** 直观展示当前 AI + 游戏领域的产品全景，同时自动生成 **每日创新日报**，帮助从业者快速掌握行业动态。

### 这个项目能做什么？

1. **产品全景图**：用 ECharts 气泡图可视化 30+ 个 AI 游戏产品，一眼看清行业格局
2. **多维度评估**：从 AI 核心程度、讨论度、用户量、产品分类等维度量化评估每个产品
3. **产品详情面板**：点击任意产品查看详情、参考链接、并可写下自己的观察笔记
4. **可排序产品列表**：表格形式浏览全部产品，支持按任意列排序
5. **每日自动日报**：通过 WorkBuddy Automation 每天 9:00 自动搜索全网中英文资讯，生成 Top5 精选日报
6. **完全静态部署**：纯前端单页应用，零后端依赖，GitHub Pages 直接部署

---

## 🖼️ 功能说明

### 气泡图全景

气泡图以四个维度展示产品分布：

| 维度 | 映射方式 | 说明 |
|------|---------|------|
| **X 轴** | AI 核心程度 (0-10) | 去掉 AI 后玩法是否还成立？越右 = AI 越核心 |
| **Y 轴** | 讨论度 (0-10) | 社交媒体、论坛、新闻的讨论热度 |
| **气泡大小** | 用户量 | small / medium / large / huge 四档 |
| **气泡颜色** | 产品分类 | 🟠 橙色 = AI 原生游戏 / 🔵 蓝色 = 现有游戏+AI |

### 产品列表

表格支持点击表头排序，展示产品名、所属游戏、AI 核心、讨论度、用户量、分类、状态、上线时间、简介和最新评论。

### 产品详情面板

点击气泡或表格中的产品名，弹出侧边面板，包含：
- 产品各维度评分
- 1-3 个参考链接（含标题和摘要）
- 个人评论区（localStorage 存储）

### 每日日报

左侧日期列表 + 右侧 Markdown 渲染，自动生成的日报包含：
- 🔥 Top 5 重点发现（含来源链接、概要、策划启发）
- 📌 其他值得留意的动态（3-5 条）
- 💡 产品库更新建议

---

## 📊 收录产品一览（30 个）

### 🔵 现有游戏 + AI 玩法（14 个）

| 产品 | 所属游戏 | AI核心 | 讨论度 | 用户量 | 状态 | 上线 |
|------|---------|--------|--------|--------|------|------|
| 小马神 | 和平精英 | 3 | 3 | 巨大 | 已上线 | 2024-06 |
| 战犬布鲁斯 | 和平精英 | 5 | 6 | 巨大 | 已上线 | 2025-11 |
| 花傲天 | 和平精英 | 6 | 8 | 大 | 已上线 | 2025-07 |
| 和平指挥官 | 和平精英 | 5 | 5 | 大 | 已上线 | 2025-04 |
| AI假人 | 超自然行动组 | 8 | 8 | 小 | 已上线 | 2025-12 |
| F.A.C.U.L. | 暗区突围 | 7 | 6 | 小 | Demo | 2024-08 |
| 王者指挥官 | 王者荣耀 | 4 | 4 | 巨大 | 已上线 | 2025-04 |
| 王者灵宝 | 王者荣耀 | 3 | 9 | 巨大 | 已上线 | 2025-05 |
| 逆水寒NPC | 逆水寒 | 6 | 7 | 大 | 已上线 | 2023-08 |
| 永劫AI队友 | 永劫无间 | 6 | 5 | 中 | 已上线 | 2024-06 |
| 三角洲AI助手 | 三角洲行动 | 3 | 2 | 中 | 已上线 | 2024-10 |
| LOL守护灵 | 英雄联盟 | 2 | 3 | 巨大 | 已上线 | 2024-09 |
| Backseat AI | 英雄联盟(第三方) | 3 | 3 | 小 | 已上线 | 2024-03 |
| 逗逗游戏伙伴 | 全游戏通用 | 4 | 4 | 小 | 已上线 | 2025-08 |

### 🟠 AI 原生游戏（16 个）

| 产品 | 所属/来源 | AI核心 | 讨论度 | 用户量 | 状态 | 上线 |
|------|----------|--------|--------|--------|------|------|
| inZOI | Krafton | 7 | 8 | 大 | 已上线 | 2025-03 |
| Neuro-sama | Twitch | 8 | 9 | 大 | 已上线 | 2022-12 |
| Suck Up! | 独立游戏 | 8 | 7 | 中 | 已上线 | 2024-05 |
| Aivilization | 港科大 | 9 | 7 | 中 | 已上线 | 2025-08 |
| EVE | 独立产品 | 7 | 7 | 中 | 已上线 | 2025-06 |
| AI Dungeon | AI Dungeon | 9 | 6 | 中 | 已上线 | 2019-12 |
| 星之低语 | 独立游戏 | 9 | 7 | 小 | 已上线 | 2025-08 |
| 斯坦福小镇 | Stanford/HF | 9 | 8 | 小 | Demo | 2023-04 |
| AI太空杀 | 独立游戏 | 8 | 5 | 小 | 已上线 | 2024-11 |
| AI Town | Hugging Face | 9 | 5 | 小 | Demo | 2023-08 |
| 1001夜 | 独立游戏 | 8 | 3 | 小 | 已上线 | 2025-03 |
| 麦琪的花园 | 独立游戏 | 7 | 3 | 小 | 已上线 | 2025-06 |
| Altera Bots | Minecraft | 8 | 4 | 小 | Demo | 2024-12 |
| AI Spellcraft | 独立游戏 | 8 | 4 | 小 | 已上线 | 2024-10 |
| 病娇猫娘女友 | 独立游戏 | 7 | 4 | 小 | 已上线 | 2024-08 |
| 遥远行星 | 独立游戏 | 8 | 2 | 小 | 已上线 | 2025-04 |

---

## 🏗️ 技术架构

```
┌──────────────────────────────────────────────────┐
│                   index.html                      │
│  ┌──────────┐  ┌──────────┐  ┌────────────────┐  │
│  │ ECharts  │  │  marked   │  │  localStorage  │  │
│  │ 气泡图   │  │ Markdown  │  │   评论存储     │  │
│  └──────────┘  └──────────┘  └────────────────┘  │
│         ↓              ↓                          │
│  ┌──────────────────────────────────────────┐     │
│  │         PRODUCTS[] (内嵌数据)             │     │
│  │  30 个产品 × 10+ 字段 + 参考链接         │     │
│  └──────────────────────────────────────────┘     │
│                                                    │
│  ┌──────────────────────────────────────────┐     │
│  │         daily-reports.js (外部加载)       │     │
│  │  Date.now() 缓存破除 + 动态 <script>     │     │
│  └──────────────────────────────────────────┘     │
└──────────────────────────────────────────────────┘
                        │
                        ↓
              GitHub Pages 部署
```

### 技术栈

| 技术 | 用途 |
|------|------|
| **ECharts 5.5** | 气泡图 scatter 可视化 + dataZoom 缩放 |
| **marked.js** | Markdown 日报渲染 |
| **localStorage** | 产品评论本地持久化 |
| **CSS Variables** | 深色科技风主题统一管理 |
| **Responsive CSS** | PC / 移动端自适应（768px 断点） |
| **GitHub Pages** | 静态部署，零成本托管 |
| **WorkBuddy Automation** | 每日日报自动生成 + git push |

### 关键算法

- **气泡重叠消解** `resolveOverlaps()`：迭代 8 次的推斥算法，阈值 0.8 数据单位，避免气泡堆叠
- **动态气泡尺寸** `getUsersSize()`：基于容器宽度的 4 档缩放（scale 范围 0.4~1.2），响应式适配
- **缓存破除**：`daily-reports.js` 通过 `Date.now()` 时间戳动态加载，确保日报即时更新

---

## 📁 文件结构

```
ai-gameplay-monitor/
├── index.html          # 主页面（单页应用，含全部 HTML/CSS/JS）
├── daily-reports.js    # 日报数据（JS 数组，Automation 每天追加）
├── README.md           # 本文件
├── .gitignore          # Git 忽略规则
├── 监控配置.md          # [本地] 搜索关键词、平台清单（不上传）
└── AI玩法产品库.md      # [本地] 产品库评分数据源（不上传）
```

---

## 🤖 自动化日报

项目通过 WorkBuddy Automation 实现每日自动日报：

| 配置项 | 值 |
|--------|-----|
| **任务名称** | AI游戏创新日报 |
| **执行频率** | 每天 09:00 |
| **搜索策略** | 6 组中英文关键词交替搜索 |
| **输出格式** | Top5 重点 + 策划启发 + 其他动态 3-5 条 |
| **写入位置** | `daily-reports.js` 追加新条目 |
| **发布方式** | 自动 `git add → commit → push` |

### 日报生成流程

```
09:00 触发
    ↓
读取 监控配置.md（搜索词、平台清单）
    ↓
执行 6 组中英文 Web 搜索
    ↓
筛选 + 去重 → Top 5 精选
    ↓
生成 Markdown 日报（含来源链接、策划启发）
    ↓
追加到 daily-reports.js
    ↓
git push → GitHub Pages 自动更新
```

---

## 🎨 UI/UX 设计

### 设计风格
- **深色科技风**（`#0F1923` 主背景），减少长时间使用的视觉疲劳
- **渐变色标题** + 蓝紫色调，呼应科技 / AI 主题
- **Backdrop blur** 毛玻璃效果的评论面板

### 响应式适配

| 特性 | PC (≥768px) | 移动端 (<768px) |
|------|------------|----------------|
| 评论面板 | 右侧抽屉 380px | 底部上滑 70vh |
| 日报导航 | 左侧 sidebar | 下拉 select |
| 导航栏 | 完整展示 | 精简 + 隐藏更新时间 |
| 图表交互 | 鼠标缩放 + 拖拽 | ECharts 原生 touch dataZoom |

---

## 🔧 本地开发

```bash
# 克隆仓库
git clone https://github.com/AlbertFuZheng/ai-gameplay-monitor.git
cd ai-gameplay-monitor

# 直接用浏览器打开
start index.html

# 或 Python 本地服务器
python -m http.server 8080
```

### 添加新产品

在 `index.html` 的 `PRODUCTS` 数组中添加：

```javascript
{
  id: "unique-id",           // 唯一标识
  name: "产品名",            // 显示名称
  game: "所属游戏",          // 所属游戏/平台
  ai_core: 7,               // AI核心程度 0-10
  buzz: 5,                  // 讨论度 0-10
  users: "medium",          // 用户量: small/medium/large/huge
  category: "native",       // 分类: native(AI原生) / addon(现有游戏+AI)
  status: "released",       // 状态: released / demo
  launch: "2025-01",        // 上线时间
  desc: "一句话简介",        // 产品描述
  source: "数据来源",        // 信息来源
  links: [                  // 参考链接 1-3 个
    { title: "标题", url: "https://...", summary: "摘要" }
  ]
}
```

### 添加日报

在 `daily-reports.js` 的数组末尾追加（通常由 Automation 自动完成）：

```javascript
{ date: "2026-03-30", content: `# AI 游戏创新日报 - 2026-03-30
...Markdown 内容...
` }
```

---

## 📝 开发历程

这个项目从零开始，经过多轮迭代打磨而成：

| 阶段 | 主要工作 |
|------|---------|
| **v0.1 项目初始化** | 创建配置文件、index.html 单页、Git 初始化、GitHub Pages 部署 |
| **v0.2 基础功能** | ECharts 气泡图 + 评论面板 + 日报浏览器 + 响应式布局 |
| **v0.3 气泡重叠修复** | `resolveOverlaps()` 推斥算法，解决产品扎堆问题 |
| **v0.4 产品列表表格** | 气泡图下方表格，支持点击表头排序 |
| **v0.5 产品扩充** | 从 8 个扩展到 30 个产品，增加上线时间列 |
| **v0.6 缓存修复** | `daily-reports.js` 改为动态 `<script>` 加载 + `Date.now()` 时间戳 |
| **v0.7 移动端优化** | 双指缩放、ECharts dataZoom、气泡大小自适应 |
| **v0.8 维度重构** | Y 轴从「玩法乐趣」改为「讨论度」，气泡大小改为「用户量」，去掉边框样式 |
| **v0.9 分类颜色** | 颜色从三色体系改为二分类：🟠 AI 原生 / 🔵 现有游戏+AI |
| **v1.0 产品详情增强** | 每个产品增加参考链接（1-3个），评论面板展示链接区 |

### 设计决策记录

- **为什么用单页 HTML 而不是 React/Vue？** — 产品够轻量，不需要构建工具，GitHub Pages 零配置部署
- **为什么评论存 localStorage 而不是数据库？** — 个人工具属性，不需要多端同步
- **为什么日报是 JS 数组而不是 JSON？** — 避免 CORS 问题，`<script>` 标签加载最简单可靠
- **为什么气泡颜色只用两种？** — 经过三色→二色的迭代，「AI 原生」vs「现有游戏+AI」是最清晰的分类维度

---

## 📄 代码概览

### index.html 核心结构（约 1060 行）

```
<head>
├── Meta + Viewport + Referrer Policy
├── ECharts CDN + marked.js CDN
├── daily-reports.js 动态加载（带缓存破除）
└── <style> 全部 CSS（~400 行）
    ├── CSS Variables 主题色
    ├── Navigation 导航栏
    ├── Bubble Chart 气泡图容器
    ├── Product Table 产品列表
    ├── Chart Legend 图例
    ├── Comment Panel 评论面板（PC右抽屉 / 移动端底部上滑）
    ├── Daily Report 日报视图（sidebar + content）
    ├── Markdown Styles 日报渲染样式
    └── Responsive 响应式适配

<body>
├── Navigation（产品全景图 / 每日日报 切换）
├── Chart View（气泡图 + 图例 + 产品表格）
├── Report View（日期列表 + Markdown 日报内容）
├── Comment Panel（浮层：评分 + 链接 + 评论）
└── <script> 全部 JS（~550 行）
    ├── PRODUCTS[] — 30 个产品数据（含参考链接）
    ├── getUsersSize() — 动态气泡尺寸
    ├── resolveOverlaps() — 气泡重叠消解算法
    ├── initChart() — ECharts 初始化 + 交互绑定
    ├── renderProductTable() — 表格渲染 + 排序
    ├── openCommentPanel() / closeCommentPanel() — 评论面板
    ├── getComments() / saveComments() — localStorage 读写
    ├── initReports() / selectReport() — 日报导航
    └── initAll() — 全局初始化入口
```

### daily-reports.js 数据格式

```javascript
window.DAILY_REPORTS = [
  {
    date: "2026-03-29",
    content: `# AI 游戏创新日报 - 2026-03-29
> 自动生成 | 数据来源：全网中英文搜索

## 🔥 Top 5 重点发现
### 1. 标题
- **来源**：[链接](url)
- **概要**：内容
- **策划启发**：分析

---
## 📌 其他值得留意的动态
- [标题](url) — 摘要

*本日报由 WorkBuddy Automation 自动生成*`
  }
  // ... 每天自动追加新条目
];
```

---

## 📜 License

本项目为个人研究工具，仅供学习参考。产品数据来源于公开信息。

---

<p align="center">
  <em>Built with ❤️ for game designers who care about AI innovation</em>
</p>
