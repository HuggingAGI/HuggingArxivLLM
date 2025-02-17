# 基于SOP增强的LLM多智能体系统在根本原因分析中的行动流程研究
发布时间：2025年02月12日

`Agent应用`
> Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis
>
> 在微服务架构领域，频繁的故障事件需要通过根本原因分析（RCA）来快速解决。通常，一个严重故障可能需要几位专家花费数小时才能找到根本原因。因此，目前的趋势是利用大型语言模型（LLMs）作为自动化工具来执行RCA。尽管近期的ReAct框架因其思考-行动-观察的范式与站点可靠性工程师（SREs）的工作方式高度契合，但其产生的幻觉常常导致无关行动，直接影响后续结果。此外，故障事件复杂多变的线索往往会进一步使模型陷入困境。

为了应对这些挑战，我们提出了一种开创性的基于标准操作程序（SOP）的LLM多智能体系统——Flow-of-Action。通过明确总结SREs的诊断步骤，SOP在关键节点对LLMs施加约束，引导RCA流程朝着正确的方向发展。为了促进SOP的合理有效使用，我们设计了一个以SOP为中心的框架，名为SOP流。SOP流包含一系列工具，包括一个用于为事件查找相关SOP的工具，一个用于为没有相关SOP的事件自动生成SOP的工具，以及一个将SOP转换为代码的工具。这大大缓解了ReAct在RCA任务中出现的幻觉问题。

我们还设计了多个辅助智能体，通过去除无用的噪声、缩小搜索范围，并告知主智能体RCA过程是否可以停止，从而协助主智能体。与ReAct方法的35.50%准确率相比，我们的Flow-of-Action方法达到了64.01%的准确率，满足了真实系统中RCA所需的准确性要求。
>
> https://arxiv.org/abs/2502.08224

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.08224](https://arxiv.org/abs/2502.08224)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)