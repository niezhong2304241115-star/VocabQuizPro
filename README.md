# 刷题物语 · Vocab Quiz Pro

<p align="center">
  <strong>刷题，也可以很美</strong>
  <br>
  申论规范词 3000 题 · 沉浸式单页应用 · 智能学习系统
</p>

<p align="center">
  <img src="https://img.shields.io/badge/题库-3000%20题-blueviolet?style=flat-square" alt="题库数量">
  <img src="https://img.shields.io/badge/状态-稳定-brightgreen?style=flat-square" alt="状态">
  <img src="https://img.shields.io/badge/技术-原生%20HTML%2FCSS%2FJS-ff6fa5?style=flat-square" alt="技术">
  <img src="https://img.shields.io/badge/离线可用-是-22b573?style=flat-square" alt="离线可用">
</p>

---

## 📖 这是什么？

**刷题物语** 是一个为公务员考试（申论科目）设计的**沉浸式刷题工具**。

区别于枯燥的刷题 App，它用精心设计的视觉氛围（樱花／暗夜双主题）和人性化的交互细节，让刷题这件事本身变得不那么苦——甚至有点享受。

> 打开即用，无需安装，无需网络。一个 HTML 文件，一个完整的学习系统。

## ✨ 功能一览

| 功能 | 说明 |
|------|------|
| 🎯 **智能刷题** | 支持单题库 / 多题库混合练习，随机抽题，不重复 |
| 🧠 **错题重练** | 自动记录错题，支持针对性巩固训练 |
| ⭐ **收藏夹** | 标记重点题目，随时回顾 |
| 📊 **学习统计** | 正确率追踪、7 日活跃度、各题库错题分布 |
| 🌙 **双主题** | 樱花粉与暗夜紫两种视觉风格，适配不同场景 |
| 🏅 **成就系统** | 等级与徽章体系，让每一次练习都看得见成长 |
| 📥 **题库导入** | 支持导入自定义题库，扩展学习范围 |
| 💾 **本地存储** | 全部数据保存在浏览器中，离线可用的真正 PWA 体验 |

## 🎨 视觉设计

- **樱花主题**：柔和的粉紫渐变背景，暖萌的配色，适合白天或轻松场景
- **暗夜主题**：深邃的紫黑调，低眩光，适合夜间或专注模式
- 中文字体优化，融合了 Poppins、ZCOOL KuaiLe、Noto Sans SC 等

## 🚀 快速开始

1. 打开 `VocabQuizPro.html`（或从任意静态服务器访问）
2. 点击 **开始刷题**，选择一个或多个题库
3. 设置题目数量，开始练习！
4. 刷错的题会自动进入错题本，方便复习

> 提示：你也可以将题库文件 `.md` 放入同目录，点击「导入题库」来扩展内容。

## 📁 项目结构

```
VocabQuizPro/
├── VocabQuizPro.html          # 主应用（自包含，零外部依赖）
├── 申论规范词选择题3000道.md   # 内置题库（3000 道选择题）
└── README.md
```

## 🧩 技术栈

- **纯前端**：HTML5 + CSS3 + Vanilla JavaScript
- **零依赖**：一个 HTML 文件，不依赖任何框架或包
- **本地存储**：基于 `localStorage`，数据完全在浏览器端
- **单页应用**：路由、状态管理、UI 渲染全部在前端完成

## 📜 许可

MIT License
