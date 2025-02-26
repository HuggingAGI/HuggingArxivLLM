# # KiRAG: 知识驱动型迭代检索器，提升检索增强生成效果
KiRAG 是一种基于知识的迭代检索器，专为增强检索增强生成而设计。
发布时间：2025年02月25日

`RAG`
> KiRAG: Knowledge-Driven Iterative Retriever for Enhancing Retrieval-Augmented Generation
>
> 迭代检索增强生成（iRAG）模型为多跳问答（QA）提供了一种有效的解决方案。然而，iRAG模型的检索过程面临两大关键挑战：（1）检索过程可能受到无关文档或事实不准确的推理链的干扰；（2）现有的检索器并未设计成能够动态适应多步推理中不断变化的信息需求，因此难以识别并检索每个迭代步骤中所需的关键信息。为此，我们提出了KiRAG，通过采用知识驱动的迭代检索器模型来优化iRAG的检索过程。具体而言，KiRAG将文档分解为知识三元组，并利用这些三元组进行迭代检索，从而实现可靠的事实检索过程。此外，KiRAG将推理过程融入检索环节，能够动态识别并检索填补信息缺口的知识，从而有效适应不断变化的信息需求。实证结果显示，KiRAG显著超越现有iRAG模型，R@3指标平均提升了9.40%，F1指标平均提升了5.14%在多跳问答任务中。
>
> https://arxiv.org/abs/2502.18397

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.18397](https://arxiv.org/abs/2502.18397)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)