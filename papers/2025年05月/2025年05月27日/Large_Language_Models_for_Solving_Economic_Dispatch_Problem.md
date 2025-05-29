# # 大型语言模型助力经济调度问题求解

发布时间：2025年05月27日

`LLM应用` `电力系统`

> Large Language Models for Solving Economic Dispatch Problem

# 摘要

> 本文探讨了现成大型语言模型（LLMs）在经济调度（ED）问题中的应用潜力。ED 是一个硬约束优化问题，电网运营商在日前时间尺度上求解，以最小化发电成本并满足物理及工程约束。尽管已有多种方法提出，但这些方法往往需要复杂的数学建模，存在收敛问题，或依赖大量标注数据和训练时间。本研究通过增强推理能力的 LLMs 来解决经典的无损 ED 问题。所提出的方法无需显式数学建模，不受收敛问题困扰，且无需标注数据或大量训练。在两个不同提示语境中采用了小样本学习技术。以 IEEE 118 节点系统（含 19 个发电单元）作为评估基准。实验结果表明，多种提示策略使 LLMs 能够有效解决 ED 问题，提供了一种方便高效的替代方案。因此，该方法为 ED 任务提供了一个有前景的未来解决方案，尤其是在基础电力系统模型可用的情况下。

> This paper investigates the capability of off-the-shelf large language models (LLMs) to solve the economic dispatch (ED) problem. ED is a hard-constrained optimization problem solved on a day-ahead timescale by grid operators to minimize electricity generation costs while accounting for physical and engineering constraints. Numerous approaches have been proposed, but these typically require either mathematical formulations, face convergence issues, or depend on extensive labeled data and training time. This work implements LLMs enhanced with reasoning capabilities to address the classic lossless ED problem. The proposed approach avoids the need for explicit mathematical formulations, does not suffer from convergence challenges, and requires neither labeled data nor extensive training. A few-shot learning technique is utilized in two different prompting contexts. The IEEE 118-bus system with 19 generation units serves as the evaluation benchmark. Results demonstrate that various prompting strategies enable LLMs to effectively solve the ED problem, offering a convenient and efficient alternative. Consequently, this approach presents a promising future solution for ED tasks, particularly when foundational power system models are available.

[Arxiv](https://arxiv.org/abs/2505.21931)