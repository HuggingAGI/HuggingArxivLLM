# RL-LLM-DT：一种基于 RL 评估与 LLM 增强的自动决策树生成之法

发布时间：2024年12月16日

`LLM应用` `人工智能`

> RL-LLM-DT: An Automatic Decision Tree Generation Method Based on RL Evaluation and LLM Enhancement

# 摘要

> 传统上，双人零和游戏的人工智能开发主要依靠决策树和强化学习（RL）这两项技术。常见做法是把固定的决策树当作一方玩家的策略，同时训练一个 RL 代理作为对手，来找出决策树的漏洞，进而逐步增强其战略实力。然而，这一过程往往需要大量人工干预，在发现决策树的弱点后对其进行改进，致使效率不高，阻碍了策略增强过程的完全自动化。所幸，大型语言模型（LLMs）的出现为实现这一过程的自动化带来了变革性机遇。我们提出了 RL-LLM-DT，这是一种基于 RL 评估和 LLM 增强的自动决策树生成方法。给定一个初始决策树，该方法包含两个重要的迭代步骤。响应策略搜索：利用 RL 来找出针对决策树的反策略。策略改进：LLMs 分析失败场景并生成改进的决策树代码。在我们的方法中，RL 专注于找出决策树的缺陷，同时促使 LLM 生成决策树的改进版本。当 RL 找不到决策树的任何缺陷或者 LLM 无法改进决策树时，迭代优化过程结束。为评估这种集成方法的有效性，我们在冰壶游戏中开展了实验。经过迭代改进，我们基于决策树的冰壶 AI 在吉迪平台的 34 个冰壶 AI 中位列第一，这表明 LLMs 能显著提升决策树的稳健性和适应性，是游戏 AI 领域的重大进步。我们的代码可在 https://github.com/Linjunjie99/RL-LLM-DT 获取。

> Traditionally, AI development for two-player zero-sum games has relied on two primary techniques: decision trees and reinforcement learning (RL). A common approach involves using a fixed decision tree as one player's strategy while training an RL agent as the opponent to identify vulnerabilities in the decision tree, thereby improving its strategic strength iteratively. However, this process often requires significant human intervention to refine the decision tree after identifying its weaknesses, resulting in inefficiencies and hindering full automation of the strategy enhancement process. Fortunately, the advent of Large Language Models (LLMs) offers a transformative opportunity to automate the process. We propose RL-LLM-DT, an automatic decision tree generation method based on RL Evaluation and LLM Enhancement. Given an initial decision tree, the method involves two important iterative steps. Response Policy Search: RL is used to discover counter-strategies targeting the decision tree. Policy Improvement: LLMs analyze failure scenarios and generate improved decision tree code. In our method, RL focuses on finding the decision tree's flaws while LLM is prompted to generate an improved version of the decision tree. The iterative refinement process terminates when RL can't find any flaw of the tree or LLM fails to improve the tree. To evaluate the effectiveness of this integrated approach, we conducted experiments in a curling game. After iterative refinements, our curling AI based on the decision tree ranks first on the Jidi platform among 34 curling AIs in total, which demonstrates that LLMs can significantly enhance the robustness and adaptability of decision trees, representing a substantial advancement in the field of Game AI. Our code is available at https://github.com/Linjunjie99/RL-LLM-DT.

[Arxiv](https://arxiv.org/abs/2412.11417)