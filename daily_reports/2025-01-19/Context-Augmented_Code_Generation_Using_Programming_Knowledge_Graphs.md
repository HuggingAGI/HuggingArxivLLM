# 基于编程知识图谱的上下文增强代码生成
发布时间：2024年10月09日

`代码编写`
> Context-Augmented Code Generation Using Programming Knowledge Graphs
>
> 大型语言模型（LLMs）和代码-LLMs（CLLMs）在代码生成方面取得了显著进展，但在处理复杂问题时仍面临挑战。检索增强生成（RAG）通过在推理时整合外部知识来解决这一问题。然而，检索模型常难以找到最相关的上下文，而生成模型在接收到不相关数据时容易产生幻觉。我们提出了一种基于编程知识图谱（PKG）的新框架，用于语义化表示和检索代码。该框架通过树剪枝技术减少不相关上下文，实现细粒度代码检索。PKG结合重新排序机制，进一步减少幻觉。我们提出了基于PKG的块级和函数级两种检索方法，优化上下文粒度。在HumanEval和MBPP基准测试中，我们的方法将pass@1准确率提升了20%，并在MBPP上比现有最佳模型高出34%。我们的贡献包括基于PKG的检索、树剪枝、重新排序方法以及用于自动代码增强的Fill-in-the-Middle（FIM）模块，该模块可生成相关注释和文档字符串。
>
> https://arxiv.org/abs/2410.18251

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.18251](https://arxiv.org/abs/2410.18251)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)