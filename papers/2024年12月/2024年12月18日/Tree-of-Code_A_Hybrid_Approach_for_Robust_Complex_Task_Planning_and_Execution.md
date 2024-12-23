# Tree-of-Code：一种用于稳健复杂任务规划与执行的混合式方法

发布时间：2024年12月18日

`Agent` `智能体` `代码生成`

> Tree-of-Code: A Hybrid Approach for Robust Complex Task Planning and Execution

# 摘要

> 大型语言模型（LLMs）的非凡能力大幅加快了智能体的迅速兴起和广泛运用。近期研究显示，生成 Python 代码将基于 LLM 的智能体的动作整合至统一的动作空间（CodeAct），是开发现实世界 LLM 智能体的可行之法。但这种逐步的代码生成方式常常缺乏一致性和稳健性，致使智能体应用不稳定，在复杂推理和域外任务中尤为如此。本文中，我们提出一种名为代码树（ToC）的新方法，借助端到端机制应对复杂问题规划与执行的挑战。通过融合来自思维树和 CodeAct 的关键理念，ToC 结合二者优势来强化解决方案的探索。在我们的框架里，每个最终的代码执行结果都被视作决策树中的一个节点，并运用广度优先搜索策略来探寻潜在的解决方案。最终结果通过基于节点输出的投票机制来确定。

> The exceptional capabilities of large language models (LLMs) have substantially accelerated the rapid rise and widespread adoption of agents. Recent studies have demonstrated that generating Python code to consolidate LLM-based agents' actions into a unified action space (CodeAct) is a promising approach for developing real-world LLM agents. However, this step-by-step code generation approach often lacks consistency and robustness, leading to instability in agent applications, particularly for complex reasoning and out-of-domain tasks. In this paper, we propose a novel approach called Tree-of-Code (ToC) to tackle the challenges of complex problem planning and execution with an end-to-end mechanism. By integrating key ideas from both Tree-of-Thought and CodeAct, ToC combines their strengths to enhance solution exploration. In our framework, each final code execution result is treated as a node in the decision tree, with a breadth-first search strategy employed to explore potential solutions. The final outcome is determined through a voting mechanism based on the outputs of the nodes.

[Arxiv](https://arxiv.org/abs/2412.14212)