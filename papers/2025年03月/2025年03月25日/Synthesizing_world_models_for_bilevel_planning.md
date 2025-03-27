# # 构建用于双层规划的世界模型

发布时间：2025年03月25日

`Agent`

> Synthesizing world models for bilevel planning

# 摘要

> 现代强化学习 (RL) 系统在视频游戏等复杂环境中表现出色，但与人类的学习效率和适应性相比仍有差距。为此，我们提出了基于理论的强化学习 (TBRL)，这一框架通过结构化的因果世界模型（即“理论”）作为模拟器，用于规划、泛化和探索。尽管 TBRL 在解释人类如何学习游戏方面表现出色，但其理论语言和规划算法仍存在局限性。为解决这些问题，我们开发了 TheoryCoder，它通过层次化理论表示和高效程序合成实现更强大的学习与规划。TheoryCoder 为代理提供通用抽象概念（如“移动到”），并结合大型语言模型从观察中生成的低级别转换模型，使其适应具体环境。双层规划算法利用这种层次化结构解决复杂任务。实验表明，该方法在网格世界游戏中表现出色，而传统直接策略合成方法则表现不佳。消融实验进一步验证了层次化抽象的优势。

> Modern reinforcement learning (RL) systems have demonstrated remarkable capabilities in complex environments, such as video games. However, they still fall short of achieving human-like sample efficiency and adaptability when learning new domains. Theory-based reinforcement learning (TBRL) is an algorithmic framework specifically designed to address this gap. Modeled on cognitive theories, TBRL leverages structured, causal world models - "theories" - as forward simulators for use in planning, generalization and exploration. Although current TBRL systems provide compelling explanations of how humans learn to play video games, they face several technical limitations: their theory languages are restrictive, and their planning algorithms are not scalable. To address these challenges, we introduce TheoryCoder, an instantiation of TBRL that exploits hierarchical representations of theories and efficient program synthesis methods for more powerful learning and planning. TheoryCoder equips agents with general-purpose abstractions (e.g., "move to"), which are then grounded in a particular environment by learning a low-level transition model (a Python program synthesized from observations by a large language model). A bilevel planning algorithm can exploit this hierarchical structure to solve large domains. We demonstrate that this approach can be successfully applied to diverse and challenging grid-world games, where approaches based on directly synthesizing a policy perform poorly. Ablation studies demonstrate the benefits of using hierarchical abstractions.

[Arxiv](https://arxiv.org/abs/2503.20124)