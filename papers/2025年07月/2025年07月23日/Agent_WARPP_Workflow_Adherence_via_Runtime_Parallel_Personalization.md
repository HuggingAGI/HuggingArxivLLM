# Agent WARPP：通过运行时并行个性化确保工作流遵循

发布时间：2025年07月23日

`LLM应用` `任务导向对话系统`

> Agent WARPP: Workflow Adherence via Runtime Parallel Personalization

# 摘要

> 大型语言模型（LLMs）在任务导向对话（TOD）系统中应用广泛，但面对涉及外部工具调用且依赖用户特定信息的长流程、条件性工作流时常常表现欠佳。我们提出了一种无训练、模块化的框架——基于运行时并行个性化的流程遵循框架（WARPP），该框架通过结合多智能体编排与运行时个性化，显著提升了基于LLMs系统的流程遵循能力。通过根据用户属性动态剪枝条件分支，WARPP在运行时有效降低了推理开销并缩小了工具选择范围。其采用的并行化架构中，专用的Personalizer智能体与模块化、领域特定的智能体协同工作，实时动态调整执行路径。我们在银行、航班和医疗三个领域选取了五个不同复杂度的代表性用户意图进行评估。通过合成数据集和LLM驱动的模拟用户，我们测试了具有条件依赖性的场景。实验结果表明，WARPP在性能上显著优于非个性化方法和ReAct基准模型。随着意图复杂度的增加，其参数保真度和工具准确性均获得显著提升，同时平均令牌使用量也有所减少，且无需额外训练。

> Large language models (LLMs) are increasingly applied in task-oriented dialogue (TOD) systems but often struggle with long, conditional workflows that involve external tool calls and depend on user-specific information. We present Workflow Adherence via Runtime Parallel Personalization, or WARPP, a training-free, modular framework that combines multi-agent orchestration with runtime personalization to improve workflow adherence in LLM-based systems. By dynamically pruning conditional branches based on user attributes, the framework reduces reasoning overhead and narrows tool selection at runtime. WARPP deploys a parallelized architecture where a dedicated Personalizer agent operates alongside modular, domain-specific agents to dynamically tailor execution paths in real time. The framework is evaluated across five representative user intents of varying complexity within three domains: banking, flights, and healthcare. Our evaluation leverages synthetic datasets and LLM-powered simulated users to test scenarios with conditional dependencies. Our results demonstrate that WARPP outperforms both the non-personalized method and the ReAct baseline, achieving increasingly larger gains in parameter fidelity and tool accuracy as intent complexity grows, while also reducing average token usage, without any additional training.

[Arxiv](https://arxiv.org/abs/2507.19543)