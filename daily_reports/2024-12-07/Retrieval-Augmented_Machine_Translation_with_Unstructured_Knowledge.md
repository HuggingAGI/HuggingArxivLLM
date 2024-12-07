# 基于非结构化知识的检索增强型机器翻译
发布时间：2024年12月05日


> Retrieval-Augmented Machine Translation with Unstructured Knowledge
>
> 检索增强生成（RAG）引入额外信息以强化大型语言模型（LLMs）。在机器翻译（MT）领域，以往工作通常从配对的 MT 语料库中检索上下文示例，或从知识图谱中获取特定领域知识，来增强模型的 MT 能力。然而，大量世界知识是以非结构化文档形式组织的，且在不同语言间可能未完全配对。在本文中，我们研究利用非结构化文档的检索增强型 MT。具体而言，我们构建了 RAGtrans，这是首个用于训练和评估 LLMs 检索增强型 MT 能力的基准。RAGtrans 包含通过 GPT-4o 和人类翻译员收集的 79K 个 MT 样本。此外，还提供了不同语言的文档，为这些样本提供知识。基于 RAGtrans，我们进一步提出一种多任务训练方法，教导 LLMs 在翻译时如何使用多语言文档中的信息。该方法利用现有的多语言语料库创建辅助训练目标，无需额外标注要求。大量实验表明，该方法使 LLMs 的 BLEU 分数提升了 1.58 - 3.09，COMET 分数提升了 1.00 - 2.03。
>
> https://arxiv.org/abs/2412.04342

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.04342](https://arxiv.org/abs/2412.04342)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)