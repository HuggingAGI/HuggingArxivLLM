# # PIP-KAG：缓解知识增强生成中的知识冲突
通过参数剪枝方法，PIP-KAG成功解决了知识增强生成中的知识冲突问题。
发布时间：2025年02月21日

`RAG`
> PIP-KAG: Mitigating Knowledge Conflicts in Knowledge-Augmented Generation via Parametric Pruning
>
> 知识增强生成（KAG）通过整合外部知识在更新大型语言模型（LLMs）的内部记忆方面展现出巨大潜力。然而，当模型的内部记忆与外部信息产生矛盾时，KAG不可避免地会遇到知识冲突问题。目前缓解这些冲突的方法主要集中在提升外部知识的利用效率上，但这些方法的效果有限，因为内部知识仍然会对LLMs的生成过程产生影响。本文中，我们提出了一种基于参数化剪枝的知识增强生成方法（PIP-KAG），通过剪枝LLMs的内部知识并引入一个即插即用的适配模块，帮助模型更好地利用外部信息。此外，我们基于LLMs的幻觉现象构建了CoConflictQA基准测试，以便更好地评估回答问题时的上下文忠实度。实验结果表明，PIP-KAG显著减少了知识冲突并提升了上下文忠实度。值得注意的是，PIP-KAG将LLMs的参数减少了13%，在KAG框架下提升了模型的参数效率。所有代码均可在https://github.com/OpenBMB/PIP-KAG获取。
>
> https://arxiv.org/abs/2502.15543

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.15543](https://arxiv.org/abs/2502.15543)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)