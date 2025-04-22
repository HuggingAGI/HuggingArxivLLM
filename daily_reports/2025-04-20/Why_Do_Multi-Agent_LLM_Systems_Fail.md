# 为什么多智能体 LLM 系统会失败？
发布时间：2025年03月17日

`Agent应用`
> Why Do Multi-Agent LLM Systems Fail?
>
> 尽管人们对多智能体系统 (MAS) 的热情日益高涨，但与单智能体框架相比，MAS 在 popular benchmarks 上的性能提升仍然有限。这一差距凸显了分析阻碍 MAS 有效性的挑战的必要性。

在这篇论文中，我们首次全面研究 MAS 的挑战。我们分析了五个流行的 MAS 框架，跨越了 150 多个任务，涉及六位专家人工标注者。我们识别出 14 种独特的失败模式，并提出了一种适用于各种 MAS 框架的全面分类法。这一分类法通过每项研究中三位专家标注者的一致性逐步形成，实现了 0.88 的 Cohen's Kappa 一致性评分。这些细致的失败模式被组织成 3 个类别：(i) 规范和系统设计故障，(ii) 代理间对齐问题，以及 (iii) 任务验证与终止。为了支持可扩展的评估，我们将 MASFT 与 LLM-as-a-Judge 整合。我们还探讨了是否可以通过两种干预措施轻松预防已识别的故障：改进代理角色的规范和增强编排策略。我们的研究发现，这些故障需要更复杂的解决方案，凸显了未来研究的明确路线图。我们开源了我们的数据集和 LLM 标注工具。
>
> https://arxiv.org/abs/2503.13657

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.13657](https://arxiv.org/abs/2503.13657)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)