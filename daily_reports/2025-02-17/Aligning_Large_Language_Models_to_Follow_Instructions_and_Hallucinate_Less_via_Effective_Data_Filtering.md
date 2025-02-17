# 通过有效数据过滤对齐大型语言模型，使其更少生成幻觉并遵循指令
发布时间：2025年02月11日


> Aligning Large Language Models to Follow Instructions and Hallucinate Less via Effective Data Filtering
>
> 在 LLM 的指令微调过程中，使用包含陌生知识的数据进行训练会导致模型过于自信并鼓励产生幻觉。为了解决这一问题，我们提出了一个全新的框架 NOVA，该框架通过识别与 LLM 已有知识高度契合的高质量数据来减少幻觉现象。NOVA 包含两个关键组件：内部一致性探测（ICP）和语义等价识别（SEI），用于评估 LLM 对指令数据的熟悉程度。具体而言，ICP 通过计算多个自生成响应之间的定制一致性来衡量 LLM 对给定指令的理解深度。SEI 则进一步通过比较目标响应与生成响应，结合语义聚类和投票策略，评估 LLM 对目标响应的熟悉程度。此外，我们引入了一个与专家对齐的奖励模型，综合考虑了超越熟悉度的其他特征，以进一步提升数据质量。通过注重数据质量并避免使用陌生数据，我们可以利用筛选后的数据有效对齐 LLM，使其更好地遵循指令并显著减少幻觉现象。大量实验和分析结果表明，NOVA 在减少幻觉方面表现出色，同时保持了 LLM 强大的遵循指令能力。
>
> https://arxiv.org/abs/2502.07340

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.07340](https://arxiv.org/abs/2502.07340)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)