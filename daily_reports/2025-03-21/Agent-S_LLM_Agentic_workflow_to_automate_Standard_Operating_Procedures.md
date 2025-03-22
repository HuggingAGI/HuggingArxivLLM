# Agent-S：基于LLM的智能体工作流，实现标准操作程序的自动化
发布时间：2025年02月03日


> Agent-S: LLM Agentic workflow to automate Standard Operating Procedures
>
> 基于大型语言模型（LLMs）的AI代理在解决复杂现实任务方面展现出巨大潜力。本文提出了一种基于LLMs的智能体工作流，用于自动化标准操作程序（SOP）。在客服领域，SOP为人工客服解决客户问题提供了逻辑性的分步指南。我们发现，SOP中的每一步骤均可归类为用户交互或API调用，而其逻辑流程则决定了导航路径。通过增强LLMs的记忆和环境（包括API工具、用户界面和外部知识来源），我们实现了SOP的自动化。我们的智能体架构包含三个特定任务的LLMs、全局动作仓库（GAR）、执行记忆和多个环境。SOP工作流以简洁的逻辑文本块形式编写。基于当前执行记忆和SOP，智能体选择要执行的动作；通过与适当环境（用户/API）交互收集观察结果和反馈，这些信息随后输入到记忆中以决定下一步动作。该智能体设计为容错型，能够动态决定重复某个动作或从外部知识源获取输入。我们在电子商务卖家领域的三个SOP上验证了所提智能体的效能，实验结果表明其在复杂现实场景中表现出色。
>
> https://arxiv.org/abs/2503.15520

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.15520](https://arxiv.org/abs/2503.15520)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)