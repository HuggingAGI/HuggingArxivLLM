# 构建适应性调试软件代理

发布时间：2025年04月25日

`Agent` `软件工程` `人工智能`

> Towards Adaptive Software Agents for Debugging

# 摘要

> 研究发现，使用多个代理可以显著提升大型语言模型的调试能力。然而，增加LLM代理的数量也会带来一些弊端，比如提升运行成本和增加代理失去专注的风险。在本研究中，我们提出了一种自适应代理设计，其中代理的数量和角色会根据任务特性动态调整。在此设计中，代理的角色并非预先定义，而是在分析问题后自动生成。初步评估表明，采用自适应设计后，生成的代理数量取决于代码缺陷的复杂程度。对于仅有简单语法问题的代码，通常只需一个代理即可解决问题；但对于更复杂的问题，则会生成更多代理。在修复效果方面，我们发现与单次提示相比，修复效果平均提升了11%。鉴于这些令人鼓舞的结果，我们提出了未来的研究方向，以进一步改进自适应软件代理的设计，使其能够自主规划和执行软件目标。

> Using multiple agents was found to improve the debugging capabilities of Large Language Models. However, increasing the number of LLM-agents has several drawbacks such as increasing the running costs and rising the risk for the agents to lose focus. In this work, we propose an adaptive agentic design, where the number of agents and their roles are determined dynamically based on the characteristics of the task to be achieved. In this design, the agents roles are not predefined, but are generated after analyzing the problem to be solved. Our initial evaluation shows that, with the adaptive design, the number of agents that are generated depends on the complexity of the buggy code. In fact, for simple code with mere syntax issues, the problem was usually fixed using one agent only. However, for more complex problems, we noticed the creation of a higher number of agents. Regarding the effectiveness of the fix, we noticed an average improvement of 11% compared to the one-shot prompting. Given these promising results, we outline future research directions to improve our design for adaptive software agents that can autonomously plan and conduct their software goals.

[Arxiv](https://arxiv.org/abs/2504.18316)