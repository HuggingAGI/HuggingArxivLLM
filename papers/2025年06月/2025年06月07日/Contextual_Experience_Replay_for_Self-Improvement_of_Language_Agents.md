# 通过上下文经验重放实现语言代理的自我改进

发布时间：2025年06月07日

`LLM应用` `人工智能`

> Contextual Experience Replay for Self-Improvement of Language Agents

# 摘要

> 大型语言模型（LLM）代理在诸如网络导航等顺序决策任务中已有应用，但缺乏特定环境经验的它们往往难以应对复杂任务。此外，当前LLM代理未能实现在推理过程中持续学习，而这对于获取环境特异性经验至关重要。为解决这一问题，我们提出了一种无训练框架——情境经验回放（CER），旨在帮助语言代理在上下文窗口中实现高效自我改进。具体来说，CER通过积累并合成过去经验，构建动态记忆缓冲区。这些经验涵盖环境动态和常见决策模式，使代理能够在新任务中检索并增强自身知识，从而提升复杂环境中的适应能力。我们在具有挑战性的WebArena和VisualWebArena基准测试中评估了CER。在VisualWebArena上，CER达到了31.9%的竞争力表现；在WebArena上，其平均成功率达36.7%，相较于GPT-4o代理基线，相对提升了51.0%。我们还进行了全面分析，以证明其高效性和有效性，并更好地理解其工作原理。

> Large language model (LLM) agents have been applied to sequential decision-making tasks such as web navigation, but without any environment-specific experiences, they often fail in these complex tasks. Moreover, current LLM agents are not designed to continually learn from past experiences during inference time, which could be crucial for them to gain these environment-specific experiences. To address this, we propose Contextual Experience Replay (CER), a training-free framework to enable efficient self-improvement for language agents in their context window. Specifically, CER accumulates and synthesizes past experiences into a dynamic memory buffer. These experiences encompass environment dynamics and common decision-making patterns, allowing the agents to retrieve and augment themselves with relevant knowledge in new tasks, enhancing their adaptability in complex environments. We evaluate CER on the challenging WebArena and VisualWebArena benchmarks. On VisualWebArena, CER achieves a competitive performance of 31.9%. On WebArena, CER also gets a competitive average success rate of 36.7%, relatively improving the success rate of the GPT-4o agent baseline by 51.0%. We also conduct a comprehensive analysis on it to prove its efficiency, validity and understand it better.

[Arxiv](https://arxiv.org/abs/2506.06698)