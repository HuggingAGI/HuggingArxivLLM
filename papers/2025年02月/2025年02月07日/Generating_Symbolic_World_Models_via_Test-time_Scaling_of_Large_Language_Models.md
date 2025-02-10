# # 通过大型语言模型的测试时调整生成符号化世界模型

发布时间：2025年02月07日

`Agent` `人工智能` `机器人学`

> Generating Symbolic World Models via Test-time Scaling of Large Language Models

# 摘要

> 解决复杂规划问题需要大型语言模型（LLMs）明确建模状态转换，以避免规则违规、遵守约束并确保最优性。然而，这一任务因自然语言的固有模糊性而受到限制。为克服这种模糊性，我们利用规划领域定义语言（PDDL）作为规划抽象，实现精确且正式的状态描述。通过PDDL，我们可以生成一个符号世界模型，在此模型中，可以无缝应用经典搜索算法（如A*）来寻找最优规划。然而，当前LLMs直接生成PDDL域仍然面临挑战，主要由于缺乏PDDL训练数据。为应对这一挑战，我们提出通过扩展LLMs在测试时的计算能力，增强其PDDL推理能力，从而生成高质量的PDDL域。具体而言，我们引入了一种简单而有效的算法，该算法首先采用Best-of-N采样方法提升初始解的质量，然后利用可解释的机器学习进行精细调整。我们的方法在生成PDDL域方面显著优于o1-mini，在两个任务（即从自然语言描述或PDDL问题生成PDDL域）上实现了超过50%的成功率。这一切无需额外训练。通过利用PDDL作为状态抽象，我们的方法在几乎所有竞赛级别的规划任务中优于当前最先进的方法。

> Solving complex planning problems requires Large Language Models (LLMs) to explicitly model the state transition to avoid rule violations, comply with constraints, and ensure optimality-a task hindered by the inherent ambiguity of natural language. To overcome such ambiguity, Planning Domain Definition Language (PDDL) is leveraged as a planning abstraction that enables precise and formal state descriptions. With PDDL, we can generate a symbolic world model where classic searching algorithms, such as A*, can be seamlessly applied to find optimal plans. However, directly generating PDDL domains with current LLMs remains an open challenge due to the lack of PDDL training data. To address this challenge, we propose to scale up the test-time computation of LLMs to enhance their PDDL reasoning capabilities, thereby enabling the generation of high-quality PDDL domains. Specifically, we introduce a simple yet effective algorithm, which first employs a Best-of-N sampling approach to improve the quality of the initial solution and then refines the solution in a fine-grained manner with verbalized machine learning. Our method outperforms o1-mini by a considerable margin in the generation of PDDL domain, achieving over 50% success rate on two tasks (i.e., generating PDDL domains from natural language description or PDDL problems). This is done without requiring additional training. By taking advantage of PDDL as state abstraction, our method is able to outperform current state-of-the-art methods on almost all competition-level planning tasks.

[Arxiv](https://arxiv.org/abs/2502.04728)