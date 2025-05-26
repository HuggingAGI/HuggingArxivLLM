# # 告别搜索，重新定义规划：用离线目标导向强化学习优化前沿LLMs  
无需传统搜索，我们提出了一种全新的方法，通过离线目标导向强化学习来优化前沿大型语言模型（LLMs）。

发布时间：2025年05月23日

`LLM应用` `问答系统` `对话系统`

> Planning without Search: Refining Frontier LLMs with Offline Goal-Conditioned RL

# 摘要

> 大型语言模型（LLMs）在问答和对话方面表现出色，但在涉及交互的复杂任务（如谈判和劝说）中，它们需要额外的长周期推理和规划能力。强化学习（RL）微调虽然在理论上可以实现这种规划，但其扩展性受到诸多限制。特别是，多轮RL训练不仅消耗大量内存和计算资源，当将其应用于LLMs作为策略时，这些问题更是雪上加霜。此外，目前最大的LLMs并未开放必要的API以支持此类训练方式。因此，现代提升LLMs推理能力的方法更多依赖于复杂的提示机制，而非传统的RL微调。为解决这一难题，我们提出了一种创新方法，通过目标导向的价值函数来引导LLM代理的推理过程，这种方法甚至可以扩展到大型API模型。这些价值函数能够根据当前动作预测任务的未来进展，使LLM代理能够全面评估多种可能的结果（包括正向和负向），从而做出更有效的规划。此外，这些价值函数是基于推理步骤而非完整的动作进行训练的，因此成为一个简洁轻量的模块，特别适用于多轮交互中的决策制定。我们在需要交互的任务（包括工具使用、社交推理和对话）上验证了这一方法，结果表明其在性能上显著优于传统的RL微调和提示方法，同时保持了效率和扩展性。

> Large language models (LLMs) excel in tasks like question answering and dialogue, but complex tasks requiring interaction, such as negotiation and persuasion, require additional long-horizon reasoning and planning. Reinforcement learning (RL) fine-tuning can enable such planning in principle, but suffers from drawbacks that hinder scalability. In particular, multi-turn RL training incurs high memory and computational costs, which are exacerbated when training LLMs as policies. Furthermore, the largest LLMs do not expose the APIs necessary to be trained in such manner. As a result, modern methods to improve the reasoning of LLMs rely on sophisticated prompting mechanisms rather than RL fine-tuning. To remedy this, we propose a novel approach that uses goal-conditioned value functions to guide the reasoning of LLM agents, that scales even to large API-based models. These value functions predict how a task will unfold given an action, allowing the LLM agent to evaluate multiple possible outcomes, both positive and negative, to plan effectively. In addition, these value functions are trained over reasoning steps rather than full actions, to be a concise and light-weight module that facilitates decision-making in multi-turn interactions. We validate our method on tasks requiring interaction, including tool use, social deduction, and dialogue, demonstrating superior performance over both RL fine-tuning and prompting methods while maintaining efficiency and scalability.

[Arxiv](https://arxiv.org/abs/2505.18098)