# TapeAgents：智能体开发与优化的一体化框架
发布时间：2024年12月11日

`Agent应用`
> TapeAgents: a Holistic Framework for Agent Development and Optimization
>
> 我们推出了TapeAgents——一个以粒度、结构化的日志带为核心的代理框架，该日志带同时承担着代理会话可恢复状态的角色。在TapeAgents中，我们通过日志带贯穿LLM代理开发全生命周期的每个环节。代理通过解析日志带和LLM输出生成新的思考与行动，并将这些步骤追加到日志带上。环境则通过将观察结果写入日志带对代理行为做出响应。得益于这种以日志带为中心的设计理念，TapeAgents能够为AI开发者提供全方位的端到端支持。在开发阶段，日志带助力会话持久化、代理审计和逐步调试。部署后，日志带可被复用于评估、微调和提示优化；更重要的是，它支持跨代理的日志复用或历史日志的修订利用。本报告中，我们将深入解析TapeAgents的设计理念。通过构建单体代理与多代理团队、优化代理提示及微调代理LLM等多个实例，我们展示了TapeAgents的实际应用场景。我们还推出了相关工具原型，并通过案例研究展示了TapeAgents的强大效能：我们成功将一个Llama-3.1-8B表单填写助手微调至与GPT-4相当的性能水平，而成本仅为后者的零头。最终，我们的对比分析揭示，TapeAgents相较于传统框架的优势源于其独特的设计理念——将LLM代理构建成一个具有结构化配置的可恢复模块化状态机，能够生成粒度、结构化的日志，并将其转化为训练文本，这是一系列在先前工作中未曾结合的独特功能。
>
> https://arxiv.org/abs/2412.08445

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.08445](https://arxiv.org/abs/2412.08445)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)