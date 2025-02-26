# 提升领域特定检索增强生成：利用推理模型生成与评估合成数据
发布时间：2025年02月21日

`RAG`
> Enhancing Domain-Specific Retrieval-Augmented Generation: Synthetic Data Generation and Evaluation using Reasoning Models
>
> 检索增强生成（RAG）系统在技术领域应用中存在明显性能差距，尤其是在需要从复杂文档中精确提取信息的场景下。现有评估方法依赖于文档级别指标，无法准确捕捉技术文档中基于token的检索精度。我们提出了一种结合细粒度评估指标和合成数据生成的框架，旨在优化特定领域的RAG性能。

首先，我们引入了基于token的精度Ω和交并比（IoU）指标，用于量化技术文本中上下文保留与信息密度之间的权衡关系。其次，我们开发了一个基于指令微调LLM（DeepSeek-R1、其蒸馏变体及Phi-4）的推理模型驱动管道，用于生成与上下文锚定的问答对，覆盖三个专业语料库：SEC 10-K文件（金融）、生物医学摘要（PubMed）和APT威胁报告（网络安全）。

实证分析揭示了以下关键发现：较小的块大小（小于10个token）可使精度提升31-42%（IoU=0.071 vs. 基线0.053），但需付出18%的召回率代价。特定领域嵌入策略在最优块大小（5-20个token）上产生了22%的差异。DeepSeek-R1-Distill-Qwen-32B模型在概念对齐方面表现出色（平均IoU比其他模型高出14%），尽管没有一种配置在所有情况下都占优。金融文本更倾向于较大块大小以覆盖更多风险因素（召回率=0.81，块大小=20），而网络安全内容则受益于原子分割，精度Ω=0.28，块大小=5。

我们的代码可在https://github.com/aryan-jadon/Synthetic-Data-Generation-and-Evaluation-using-Reasoning-Model获取。
>
> https://arxiv.org/abs/2502.15854

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.15854](https://arxiv.org/abs/2502.15854)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)