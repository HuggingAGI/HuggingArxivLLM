# 为检索增强的大型语言模型学习擦除多文档中的私人知识
发布时间：2025年04月14日

`RAG`
> Learning to Erase Private Knowledge from Multi-Documents for Retrieval-Augmented Large Language Models
>
> # 摘要
检索增强生成（RAG）是将大型语言模型应用于专有领域的一种有前景的技术。然而，检索到的文档可能包含敏感知识，这在生成结果中存在隐私泄露的风险。因此，如何有效擦除检索文档中的隐私信息，是RAG面临的关键挑战。

与传统的文本匿名化不同，RAG需要考虑以下几点：(1) 内在的多文档推理可能面临去匿名化攻击；(2) 隐私知识因场景而异，因此应允许用户自定义需要擦除的信息；(3) 保留足够的公开可用知识以支持生成任务。

本文介绍了RAG的隐私擦除任务，并提出了Eraser4RAG，这是一种隐私知识擦除器，能够有效去除用户定义的隐私知识，同时保留足够的公开知识用于生成。具体来说，我们首先构建一个全局知识图谱，以识别文档中的潜在知识，旨在防御去匿名化攻击。然后将其随机拆分为隐私子图和公开子图，并微调Flan-T5以重写检索到的文档，排除隐私三元组。最后，使用PPO算法优化重写模型，以最小化隐私三元组并最大化公开三元组的保留。

在四个问答数据集上的实验表明，Eraser4RAG的擦除性能优于GPT-4o。
>
> https://arxiv.org/abs/2504.09910

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.09910](https://arxiv.org/abs/2504.09910)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)