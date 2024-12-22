# 用于代码生成的结果细化过程监督

发布时间：2024年12月19日

`LLM应用` `代码生成`

> Outcome-Refining Process Supervision for Code Generation

# 摘要

> 大型语言模型在代码生成领域展现出非凡能力，然而在应对需要深度算法推理的复杂编程任务时，却常常力不从心。尽管通过学习奖励模型进行的过程监督为指导推理步骤带来了希望，但它需要高昂的训练数据，且评估不够可靠。我们提出了结果优化过程监督这一全新范式，将结果优化本身视作需监督的过程。我们的框架借助具体的执行信号为推理步骤的监督奠定基础，同时运用树状结构探索同步维持多个解决方案路径。实验证明，我们的方法能让较小的模型在竞争编程任务中达成高成功率和出色的性能指标，比传统奖励模型创建的验证更可靠，且无需训练 PRM。我们的方法在 5 个模型和 3 个数据集上实现了显著提升：正确性平均提升 26.9%，效率提升 42.2%。结果表明，为解决复杂编程任务提供具备具体验证信号的结构化推理空间极为关键。我们在以下网址开源了所有代码和数据：https://github.com/zhuohaoyu/ORPS

> Large Language Models have demonstrated remarkable capabilities in code generation, yet they often struggle with complex programming tasks that require deep algorithmic reasoning. While process supervision through learned reward models shows promise in guiding reasoning steps, it requires expensive training data and suffers from unreliable evaluation. We propose Outcome-Refining Process Supervision, a novel paradigm that treats outcome refinement itself as the process to be supervised. Our framework leverages concrete execution signals to ground the supervision of reasoning steps, while using tree-structured exploration to maintain multiple solution trajectories simultaneously. Experiments demonstrate that our approach enables even smaller models to achieve high success accuracy and performance metrics on competitive programming tasks, creates more reliable verification than traditional reward models without requiring training PRMs. Our approach achieves significant improvements across 5 models and 3 datasets: an average of 26.9% increase in correctness and 42.2% in efficiency. The results suggest that providing structured reasoning space with concrete verification signals is crucial for solving complex programming tasks. We open-source all our code and data at: https://github.com/zhuohaoyu/ORPS

[Arxiv](https://arxiv.org/abs/2412.15118)