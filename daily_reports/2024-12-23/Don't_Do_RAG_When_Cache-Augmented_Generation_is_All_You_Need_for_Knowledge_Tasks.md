# 别搞 RAG 啦：对于知识任务，缓存增强生成就足够了
发布时间：2024年12月20日

`RAG`
> Don't Do RAG: When Cache-Augmented Generation is All You Need for Knowledge Tasks
>
> 检索增强生成（RAG）作为整合外部知识源以强化语言模型的有力手段，已备受瞩目。但 RAG 也带来了一些难题，比如检索延迟、文档选取可能出错以及系统复杂度提升等。随着具有大幅扩展上下文窗口的大型语言模型（LLM）的问世，本文提出了一种新的范式——缓存增强生成（CAG），它避开了实时检索。我们的方法是把所有相关资源，特别是在用于检索的文档或知识有限且便于管理的情况下，预加载到 LLM 的扩展上下文中，并缓存其运行时参数。在推理时，模型利用这些预加载的参数来回答问题，无需额外的检索步骤。对比分析显示，CAG 消除了检索延迟，将检索错误降到最低，同时保持了上下文的相关性。在多个基准上的性能评估凸显了长上下文 LLM 要么胜过要么补充传统 RAG 流程的情形。这些发现表明，对于某些应用，尤其是知识库有限的那些，CAG 为 RAG 提供了一种精简高效的替代方案，在降低复杂度的同时取得了相当甚至更优的成果。
>
> https://arxiv.org/abs/2412.15605

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.15605](https://arxiv.org/abs/2412.15605)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)