# 基于大型语言模型的文本游戏代理蒙特卡洛规划方法

发布时间：2025年04月23日

`Agent` `人工智能`

> Monte Carlo Planning with Large Language Model for Text-Based Game Agents

# 摘要

> 文本类游戏为语言型自主智能体提供了宝贵的实验环境。然而，传统的规划-学习范式（如蒙特卡洛树搜索（MCTS）与强化学习（RL）的结合）由于需要大量迭代，耗时较长。此外，这些算法虽然能够进行基于不确定性的探索，但却缺乏语言理解和推理能力。本文中，我们引入了基于动态记忆引导的大型语言模型的蒙特卡洛规划算法（MC-DML）。MC-DML结合了大型语言模型（LLMs）的语言理解和推理能力，以及树搜索算法的探索优势。具体而言，我们通过增强LLMs的在试和跨试记忆机制，使其能够从过往经验中学习，并在规划过程中动态调整行动评估。我们在Jericho基准测试中的一系列文本类游戏中进行了实验。结果表明，MC-DML算法在初始规划阶段显著提升了各类游戏的表现，超越了需要多次迭代的当代优秀方法。这证明了我们算法的有效性，为在复杂环境中实现更高效的基于语言的规划奠定了基础。

> Text-based games provide valuable environments for language-based autonomous agents. However, planning-then-learning paradigms, such as those combining Monte Carlo Tree Search (MCTS) and reinforcement learning (RL), are notably time-consuming due to extensive iterations. Additionally, these algorithms perform uncertainty-driven exploration but lack language understanding and reasoning abilities. In this paper, we introduce the Monte Carlo planning with Dynamic Memory-guided Large language model (MC-DML) algorithm. MC-DML leverages the language understanding and reasoning capabilities of Large Language Models (LLMs) alongside the exploratory advantages of tree search algorithms. Specifically, we enhance LLMs with in-trial and cross-trial memory mechanisms, enabling them to learn from past experiences and dynamically adjust action evaluations during planning. We conduct experiments on a series of text-based games from the Jericho benchmark. Our results demonstrate that the MC-DML algorithm significantly enhances performance across various games at the initial planning phase, outperforming strong contemporary methods that require multiple iterations. This demonstrates the effectiveness of our algorithm, paving the way for more efficient language-grounded planning in complex environments.

[Arxiv](https://arxiv.org/abs/2504.16855)