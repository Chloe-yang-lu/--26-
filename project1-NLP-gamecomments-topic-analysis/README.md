# 游戏玩家舆论分析：基于 NLP 的《刺客信条：暗影》社交媒体洞察  
[Click here for English README](#nlp-based-social-media-analysis-for-assassins-creed-shadow)

---

## 📌 项目简介
本项目是布里斯托大学 **Social Media & Web Analytics** 课程的研究作品，旨在分析玩家对育碧即将发行的《刺客信条：暗影》的社交媒体讨论。通过 Reddit 数据抓取、NLP 主题建模与情感分析，量化玩家关注的核心议题及整体舆论倾向，并结合可视化呈现业务价值。

---

## 📊 项目目标
- **识别玩家最关注的话题**：利用 BERTopic 进行无监督主题建模，提取核心话题与关键词。  
- **洞察整体情感态度**：基于 RoBERTa 模型进行情感分类，呈现玩家情绪分布与热度特征。  
- **提供业务价值**：结合分析结果，为游戏开发与市场团队提供优化与营销建议。  

---

## ⚙️ 技术栈
- **编程语言**: Python (pandas, numpy, matplotlib, seaborn, sklearn, nltk)  
- **NLP 方法**: BERTopic (CBOW embedding + UMAP 降维 + HDBSCAN 聚类)  
- **情感分析**: RoBERTa 预训练模型  
- **数据可视化**: matplotlib, seaborn  

---

## 📂 文件结构
├── data/ # Reddit 抓取与清洗后的数据集
├── scripts/ # Python 脚本，包括建模与可视化代码
├── images/ # 可视化图表与结果展示
├── report/ # 项目完整报告 (PDF & DOCX)
└── README.md # 当前说明文档


---

## 📈 可视化示例
- 话题分布柱状图（展示高频/低频讨论话题）
- RoBERTa 情感分布饼图（总体情绪倾向）
- 情感散点图（情绪与讨论热度关系）

---

## 🔍 业务洞察
- 玩家对 **开放世界设计** 与 **角色扮演元素** 保持高度期待。  
- **商业化机制（战斗通行证、战利品箱）** 引发明显负面反馈。  
- 围绕 **日本文化与历史设定** 的讨论带有敏感性，需谨慎沟通与应对。  
- 整体情绪分布显示：积极情绪居多，负面评论虽声量大，但并非主流。  

---

## 📉 局限性
- 数据仅限于英文 Reddit 帖子，未覆盖其他语言与社区。  
- BERTopic 与 RoBERTa 分析结果未交叉整合，无法直接判定各话题的情绪倾向。  
- 模型对讽刺、隐喻的识别能力有限，存在一定误判风险。  

---

## 👩‍💻 作者
杨璐 Lu Yang  
- MSc Business Analytics, University of Bristol  
- 方向：数据分析、NLP 应用、游戏行业市场研究  
- 联系方式：yangluchloe@163.com  

---

# NLP-Based Social Media Analysis for Assassin’s Creed: Shadow

---

## 📌 Project Overview
This project was developed as part of the **Social Media & Web Analytics** module at the University of Bristol. It analyzes Reddit discussions around Ubisoft’s upcoming title *Assassin’s Creed: Shadow*, using NLP topic modeling and sentiment analysis to quantify player concerns, expectations, and emotional tendencies.

---

## 📊 Objectives
- **Topic Identification**: Apply BERTopic to uncover key discussion clusters and keywords.  
- **Sentiment Analysis**: Use RoBERTa to classify player emotions and visualize sentiment distribution.  
- **Business Value**: Translate findings into insights for game design improvements and marketing strategy.  

---

## ⚙️ Tech Stack
- **Languages**: Python (pandas, numpy, matplotlib, seaborn, sklearn, nltk)  
- **NLP Methods**: BERTopic (CBOW embedding + UMAP + HDBSCAN)  
- **Sentiment Analysis**: RoBERTa-based classification  
- **Visualization**: matplotlib, seaborn  

---

## 📂 Repository Structure
├── data/ # Collected and cleaned Reddit dataset
├── scripts/ # Python scripts for modeling & visualization
├── images/ # Visualizations and charts
├── report/ # Full project report (PDF & DOCX)
└── README.md # This file


---

## 📈 Visualization Highlights
- Topic distribution bar chart (high vs. low frequency topics)  
- Sentiment distribution pie chart (overall attitude)  
- Sentiment–engagement scatter plot (discussion heat vs. emotion)  

---

## 🔍 Business Insights
- Strong expectations for **open-world design** and **RPG elements**.  
- Concerns over **monetization mechanics** (battle pass, loot box).  
- **Cultural and historical representation of Japan** triggers debates and sensitivities.  
- Overall sentiment is **predominantly positive**, with negative voices being vocal but not dominant.  

---

## 📉 Limitations
- Dataset limited to English Reddit posts, excluding other communities and languages.  
- BERTopic and RoBERTa were applied separately; no direct mapping of topic–sentiment proportions.  
- Sarcasm, irony, and figurative language remain challenging for sentiment models.  

---

## 👩‍💻 Author
Lu Yang  
- MSc Business Analytics, University of Bristol  
- Focus: Data Analytics, NLP applications, Gaming market research  
- Contact: yangluchloe@163.com  
