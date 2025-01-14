# PoAct: 广义应用中的策略与行动双控代理

发布时间：2025年01月12日

`Agent

理由：这篇论文主要讨论了LLM驱动的智能体框架在复杂推理任务中的应用，特别是通过策略和动作双控智能体（PoAct）来优化推理路径和工具调用。论文的核心内容围绕智能体的设计和优化，属于Agent领域的研究。` `智能体`

> PoAct: Policy and Action Dual-Control Agent for Generalized Applications

# 摘要

> 凭借强大的理解和推理能力，LLM驱动的智能体框架在复杂推理任务中表现卓越。类似ReAct的智能体通过逐步规划和工具调用，能够解决各种复杂问题，并根据环境反馈迭代优化。然而，随着LLM规划能力的提升，ReAct框架中的工具调用动作常常与复杂规划和数据组织不匹配。Code Action虽然解决了这些问题，但也带来了更复杂的动作空间和组织挑战。为此，本文提出了策略和动作双控智能体（PoAct），通过动态切换推理策略和调整动作空间，实现更高质量的代码动作和更精准的推理路径。在Agent Benchmark的法律和通用场景实验中，我们的方法展现了卓越的推理能力，并显著减少了token消耗。在LegalAgentBench上，我们的方法比基线提升了20%，同时token消耗更低。基于GPT-4o和GLM-4系列模型的实验与分析，进一步验证了该方法在解决复杂问题上的巨大潜力和可扩展性。

> Based on their superior comprehension and reasoning capabilities, Large Language Model (LLM) driven agent frameworks have achieved significant success in numerous complex reasoning tasks. ReAct-like agents can solve various intricate problems step-by-step through progressive planning and tool calls, iteratively optimizing new steps based on environmental feedback. However, as the planning capabilities of LLMs improve, the actions invoked by tool calls in ReAct-like frameworks often misalign with complex planning and challenging data organization. Code Action addresses these issues while also introducing the challenges of a more complex action space and more difficult action organization. To leverage Code Action and tackle the challenges of its complexity, this paper proposes Policy and Action Dual-Control Agent (PoAct) for generalized applications. The aim is to achieve higher-quality code actions and more accurate reasoning paths by dynamically switching reasoning policies and modifying the action space. Experimental results on the Agent Benchmark for both legal and generic scenarios demonstrate the superior reasoning capabilities and reduced token consumption of our approach in complex tasks. On the LegalAgentBench, our method shows a 20 percent improvement over the baseline while requiring fewer tokens. We conducted experiments and analyses on the GPT-4o and GLM-4 series models, demonstrating the significant potential and scalability of our approach to solve complex problems.

[Arxiv](https://arxiv.org/abs/2501.07054)