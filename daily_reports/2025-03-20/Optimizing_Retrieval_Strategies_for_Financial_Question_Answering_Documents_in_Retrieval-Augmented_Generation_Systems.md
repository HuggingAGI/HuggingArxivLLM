# 优化检索策略：在检索增强生成系统中提升财务问答文档的效果
发布时间：2025年03月19日

`RAG`
> Optimizing Retrieval Strategies for Financial Question Answering Documents in Retrieval-Augmented Generation Systems
>
> 检索增强生成（RAG）作为一种有前景的框架，用于缓解大型语言模型（LLMs）中的幻觉问题，但其性能依赖于底层检索系统。在金融领域，10-K报告等文档因领域特定的词汇和多层级表格数据带来了独特挑战。本研究提出了一种高效、端到端的RAG流水线，通过三阶段方法（预检索、检索、后检索）提升金融文档的检索效果。预检索阶段采用多种查询和语料库预处理技术，丰富输入数据。检索阶段使用领域知识微调的SOTA嵌入模型，并结合稠密和稀疏表示的混合检索策略。后检索阶段则利用直接偏好优化（DPO）训练和文档选择方法，进一步优化结果。在七个金融问答数据集上的评估显示，检索性能显著提升，生成结果更准确且语境适宜。这些发现突显了定制化检索技术在提升RAG系统金融应用有效性方面的重要性。完整的可复制流水线已在GitHub上提供：https://github.com/seohyunwoo-0407/GAR。
>
> https://arxiv.org/abs/2503.15191

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.15191](https://arxiv.org/abs/2503.15191)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)