# 自适应压力测试：黑箱LLM规划器

发布时间：2025年05月08日

`LLM应用` `自动驾驶` `人工智能`

> Adaptive Stress Testing Black-Box LLM Planners

# 摘要

> 大型语言模型 (LLMs) 在规划、控制和预测等决策任务中展现了显著的泛化能力，但其生成不安全和不理想输出的倾向却带来了潜在风险。尤其是在关键安全场景中，检测这些失败情况至关重要。现有的黑盒方法通常通过识别多个样本中的不一致来检测幻觉，常用手段包括随机化细节顺序或生成对抗性输入，其核心直觉是：自信的模型应产生稳定的输出。我们通过手动案例研究发现，除了上述方法外，其他形式的扰动（如添加噪声、移除传感器细节）也会导致 LLMs 在驾驶环境中产生幻觉。为此，我们提出了一种基于自适应压力测试 (AST) 和蒙特卡洛树搜索 (MCTS) 的全新方法，用于高效搜索提示扰动空间。我们的 AST 方法能够发现导致语言模型表现出高度不确定性的场景和提示。通过在各种场景下生成 MCTS 提示扰动树，我们证明：离线分析可应用于运行时，不仅能够自动生成影响模型不确定性的提示，还能为 LLM 的实时信任评估提供关键信息。

> Large language models (LLMs) have recently demonstrated success in generalizing across decision-making tasks including planning, control and prediction, but their tendency to hallucinate unsafe and undesired outputs poses risks. We argue that detecting such failures is necessary, especially in safety-critical scenarios. Existing black-box methods often detect hallucinations by identifying inconsistencies across multiple samples. Many of these approaches typically introduce prompt perturbations like randomizing detail order or generating adversarial inputs, with the intuition that a confident model should produce stable outputs. We first perform a manual case study showing that other forms of perturbations (e.g., adding noise, removing sensor details) cause LLMs to hallucinate in a driving environment. We then propose a novel method for efficiently searching the space of prompt perturbations using Adaptive Stress Testing (AST) with Monte-Carlo Tree Search (MCTS). Our AST formulation enables discovery of scenarios and prompts that cause language models to act with high uncertainty. By generating MCTS prompt perturbation trees across diverse scenarios, we show that offline analyses can be used at runtime to automatically generate prompts that influence model uncertainty, and to inform real-time trust assessments of an LLM.

[Arxiv](https://arxiv.org/abs/2505.05665)