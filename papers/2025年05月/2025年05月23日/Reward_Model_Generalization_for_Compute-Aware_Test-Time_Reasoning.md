# # 奖励模型的泛化能力：面向计算感知的推理测试阶段

发布时间：2025年05月23日

`LLM理论` `机器学习` `模型优化`

> Reward Model Generalization for Compute-Aware Test-Time Reasoning

# 摘要

> 外部推理时间增强通过生成与选择的分离来提升大型语言模型（LLMs）的能力。在推理过程中，模型生成多个推理路径，然后通过辅助过程奖励模型（PRM）对这些路径进行评分并选择最优解。推理时间计算最优性（TCO）是这一过程中的核心挑战，即如何在固定推理预算下最大化答案准确性。我们建立了一个理论框架，用于分析PRM的泛化误差对计算效率和推理性能的影响。借助PAC-Bayes理论，我们推导了泛化界限，证明PRM的较低泛化误差可减少找到正确答案所需的样本数量。基于此分析，我们提出了计算感知树搜索（CATS），这是一种动态控制搜索行为的Actor-Critic框架。其中，Actor根据奖励分布和稀疏性统计输出采样超参数，而Critic则评估这些超参数的效用，以指导预算分配。在MATH和AIME基准测试中，使用不同LLMs和PRMs的实验表明，CATS始终优于其他外部TTS方法，验证了我们的理论预测。


> External test-time reasoning enhances large language models (LLMs) by decoupling generation and selection. At inference time, the model generates multiple reasoning paths, and an auxiliary process reward model (PRM) is used to score and select the best one. A central challenge in this setting is test-time compute optimality (TCO), i.e., how to maximize answer accuracy under a fixed inference budget. In this work, we establish a theoretical framework to analyze how the generalization error of the PRM affects compute efficiency and reasoning performance. Leveraging PAC-Bayes theory, we derive generalization bounds and show that a lower generalization error of PRM leads to fewer samples required to find correct answers. Motivated by this analysis, we propose Compute-Aware Tree Search (CATS), an actor-critic framework that dynamically controls search behavior. The actor outputs sampling hyperparameters based on reward distributions and sparsity statistics, while the critic estimates their utility to guide budget allocation. Experiments on the MATH and AIME benchmarks with various LLMs and PRMs demonstrate that CATS consistently outperforms other external TTS methods, validating our theoretical predictions.

[Arxiv](https://arxiv.org/abs/2505.18065)