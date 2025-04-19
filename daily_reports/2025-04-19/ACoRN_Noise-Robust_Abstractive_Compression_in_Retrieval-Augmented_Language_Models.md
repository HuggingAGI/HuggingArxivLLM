# ACoRN：增强型检索语言模型中的噪声鲁棒摘要压缩方法
发布时间：2025年04月17日

`RAG`
> ACoRN: Noise-Robust Abstractive Compression in Retrieval-Augmented Language Models
>
> 抽取式压缩通过使用较小的语言模型浓缩与查询相关的上下文，有效降低了检索增强生成（RAG）中的计算成本。然而，尽管检索到的文档具有高相关性评分，它们常常包含与回答无关或因事实错误而具有误导性的信息。这种现象表明，抽取式压缩器在长上下文中更可能忽略对正确答案至关重要的信息。为了解决这一问题，我们对检索到的文档进行了更细致的分类，并提出了抗噪声的抽取式压缩方法（ACoRN），该方法引入了两项创新性训练步骤。首先，我们在训练数据集上采用离线数据增强，以提升压缩器在面对两类检索噪声时的鲁棒性。其次，鉴于基于语言模型的压缩器存在信息利用率不足和位置偏见问题，我们进行了微调，使其能够生成围绕直接支持正确答案的关键信息的摘要。实验结果表明，使用ACoRN训练的T5-large作为压缩器，在保持答案字符串的同时，显著提升了精确匹配（EM）和F1分数，这些结果可作为直接证据。ACoRN在包含大量降低准确性的文档的数据集上表现出色，使其在实际应用中具有重要价值。
>
> https://arxiv.org/abs/2504.12673

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.12673](https://arxiv.org/abs/2504.12673)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)