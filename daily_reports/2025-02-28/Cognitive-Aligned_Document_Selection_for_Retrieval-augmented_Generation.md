# 用于检索增强生成的认知对齐文档选择
发布时间：2025年02月17日

`RAG`
> Cognitive-Aligned Document Selection for Retrieval-augmented Generation
>
> 大型语言模型（LLMs）固有的幻觉现象源于其生成文本的精度无法仅凭参数化知识保证。尽管检索增强生成（RAG）系统通过整合外部文档提升了生成模型的准确性和可靠性，但在实际应用中，检索到的文档往往无法充分支持模型的回答。为解决这一问题，我们提出了GGatrieval（细粒度 grounded 对齐检索，用于可验证生成），该方法利用LLM动态更新查询并筛选高质量、可靠的检索文档。

具体来说，我们将用户查询解析为其句法成分，并与检索到的文档进行细粒度的 grounded 对齐。对于无法单独对齐的查询成分，我们提出了一种动态语义补偿机制，通过迭代优化和重写查询，同时持续更新检索结果。这一迭代过程持续进行，直到检索到的文档足以支持查询的回答。

我们的方法引入了一种新颖的检索文档筛选标准，紧密模仿了人类获取目标信息的策略。这确保了检索到的内容能够有效支持和验证生成的输出。在ALCE基准测试中，我们的方法显著超越了各种基线，达到了最先进的性能水平。
>
> https://arxiv.org/abs/2502.11770

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.11770](https://arxiv.org/abs/2502.11770)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)