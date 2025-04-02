# 智胜于财：用于测试时知识增强的动态参数检索增强生成
发布时间：2025年03月31日

`RAG`
> Better wit than wealth: Dynamic Parametric Retrieval Augmented Generation for Test-time Knowledge Enhancement
>
> 检索增强生成（RAG）通过从外部来源检索相关文档并将其纳入上下文，增强了大型语言模型（LLMs）。虽然它通过提供事实性文本提高了可靠性，但随着上下文长度的增长，推理成本大幅增加，并引入了具有挑战性的RAG幻觉问题，这主要归因于LLMs中缺乏相应的参数化知识。一个高效的解决方案是在测试时增强LLMs的知识。参数化RAG（PRAG）通过将文档嵌入到LLMs的参数中，以执行测试时的知识增强，通过离线训练有效降低了推理成本。然而，其高昂的训练和存储成本，以及有限的泛化能力，严重限制了其实际应用。为了解决这些挑战，我们提出了动态参数化RAG（DyPRAG），一个利用轻量级参数翻译模型高效地将文档转换为参数化知识的新框架。DyPRAG不仅降低了推理、训练和存储成本，还能够动态生成参数化知识，无缝增强LLMs的知识，并以即插即用的方式在测试时解决知识冲突。在多个数据集上的广泛实验验证了DyPRAG的有效性和泛化能力，提供了一种强大且实用的RAG范式，实现了卓越的知识融合，并在实际应用中缓解了RAG幻觉问题。我们的代码可在https://github.com/Trae1ounG/DyPRAG获取。
>
> https://arxiv.org/abs/2503.23895

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.23895](https://arxiv.org/abs/2503.23895)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)