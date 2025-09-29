# 🎮 Mobile Games Lifecycle Analysis (基于生命周期理论的移动游戏分析)

[English Version Below ⬇️](#english-version)

---

## 📖 项目简介

本项目基于我的硕士毕业论文，结合 **产品生命周期理论 (PLC)** 与 **数据驱动方法**，提出了一个用于分析和监测移动游戏生命周期的框架。  
我设计了新的复合指标 **Active Value Index (AVI)**，并利用 **隐马尔可夫模型 (HMM)** 对多个移动游戏的运营数据进行无监督建模，识别其生命周期阶段。  

此外，本研究还通过 **质性访谈 (Thematic Analysis)** 验证模型结果，从 **行业实践** 和 **玩家心理** 两个角度，补充了数据分析的洞察。  

---

## 📂 仓库结构

```bash
├── figures/          # 可视化图表 (AVI 曲线、HMM 状态划分等)
├── notebooks/        # Jupyter Notebook 文件 (数据处理与建模代码)
├── report_chinese/   # 中文报告 (PDF 与 DOCX 格式)
└── README.md         # 项目说明文档
```


---

## 🔑 研究亮点

- 理论结合：将经典产品生命周期理论与数据驱动方法融合。
- 方法创新：提出 AVI 指标，克服单一指标 (DAU/Revenue) 的局限性。
- 模型应用：基于 HMM 识别生命周期阶段，分析不同公司与类型游戏的差异。
- 实践验证：通过行业从业者和玩家访谈，增强模型解释力与应用价值。

---

## 📊 技术栈

- 编程语言：Python
- 主要库：pandas, numpy, matplotlib, seaborn, hmmlearn
- 方法：时间序列建模、隐马尔可夫模型、主题分析
- 应用场景：游戏数据分析、市场研究、产品运营优化

---

## 📑 学术伦理说明

- 完整论文未公开，以遵守学术规范。
- 此仓库仅展示研究方法、核心发现与技术实现，用于职业展示。

---

## 👩‍💻 作者

**杨璐 (Lu Yang)**  
University of Bristol, MSc Business Analytics, Class of 2026  
📧 Email: yangluchloe@163.com

---

<a id="english-version"></a>
## 🎮 Mobile Games Lifecycle Analysis

---

## 📖 Project Overview

This project is based on my MSc dissertation, which integrates **Product Lifecycle Theory (PLC)** with **data-driven methods** to analyze and monitor the lifecycle of mobile games.  
I designed a composite indicator called **Active Value Index (AVI)** and applied a **Hidden Markov Model (HMM)** to time-series data from multiple games, identifying their lifecycle stages.  

To complement the quantitative analysis, I also conducted **thematic interviews** with both an industry practitioner and players, bringing in perspectives on business strategies and user psychology.  

---

## 📂 Repository Structure
```bash
├── figures/          # Visualization figures (AVI curves, HMM states, etc.)
├── notebooks/        # Jupyter Notebooks (data processing & modeling code)
├── report_chinese/   # Chinese report (PDF & DOCX format)
└── README.md         # Project documentation
```
---

## 🔑 Key Highlights

- Theory & Practice: Extends classic PLC with data-driven approaches.
- Methodological Innovation: Proposed AVI, overcoming limitations of single indicators (DAU/Revenue).
- Modeling: Applied HMM to detect lifecycle stages across different companies and game genres.
- Validation: Supplemented findings with thematic interviews, bridging quantitative models and real-world insights.

---

## 📊 Tech Stack

- Programming: Python
- Libraries: pandas, numpy, matplotlib, seaborn, hmmlearn
- Methods: Time-series modeling, Hidden Markov Models, Thematic Analysis
- Applications: Game data analytics, market research, product lifecycle management

---

## 📑 Academic Integrity Statement

- The full dissertation is not publicly available, in compliance with academic norms.
- This repository only includes methods, key findings, and technical implementations for professional presentation.

---

## 👩‍💻 Author

**Lu Yang**  
University of Bristol, MSc Business Analytics, Class of 2026  
📧 Email: yangluchloe@163.com
