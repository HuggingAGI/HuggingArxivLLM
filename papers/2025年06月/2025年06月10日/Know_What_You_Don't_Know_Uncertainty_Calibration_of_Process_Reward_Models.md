# 知其所不知：过程奖励模型的不确定性校准

发布时间：2025年06月10日

`LLM理论` `大型语言模型` `数学推理`

> Know What You Don't Know: Uncertainty Calibration of Process Reward Models

# 摘要

> 过程奖励模型（PRMs）在指导大型语言模型（LLMs）的推理扩展算法中起到关键作用。然而，即使是先进的PRMs，也可能存在校准不佳的问题，常常高估成功概率。针对这一挑战，我们提出了一种基于分位数回归的校准方法，能够将PRM输出与真实成功概率更好地对齐。结合这些校准后的成功概率及其置信区间，我们开发了一个\emph{实例自适应扩展}（IAS）框架，该框架能够根据部分推理轨迹生成正确最终答案的可能性动态调整推理预算。与传统方法为每个查询固定分配推理轨迹数量不同，这种方法在使用我们的校准PRMs时，能够灵活适应每个实例和推理步骤。在数学推理基准测试中的实验结果表明，(i) 我们的PRM校准方法成功实现了低校准误差，优于基线方法；(ii) 校准是实现有效自适应扩展的关键；(iii) 提出的IAS策略在保持最终答案准确性的同时降低了推理成本，如预期的那样，在更自信的问题上使用更少的计算资源。

> Process reward models (PRMs) play a central role in guiding inference-time scaling algorithms for large language models (LLMs). However, we observe that even state-of-the-art PRMs can be poorly calibrated and often overestimate success probabilities. To address this, we present a calibration approach, performed via quantile regression, that adjusts PRM outputs to better align with true success probabilities. Leveraging these calibrated success estimates and their associated confidence bounds, we introduce an \emph{instance-adaptive scaling} (IAS) framework that dynamically adjusts the inference budget based on the estimated likelihood that a partial reasoning trajectory will yield a correct final answer. Unlike conventional methods that allocate a fixed number of reasoning trajectories per query, this approach successfully adapts to each instance and reasoning step when using our calibrated PRMs. Experiments on mathematical reasoning benchmarks show that (i) our PRM calibration method successfully achieves small calibration error, outperforming the baseline methods, (ii) calibration is crucial for enabling effective adaptive scaling, and (iii) the proposed IAS strategy reduces inference costs while maintaining final answer accuracy, utilizing less compute on more confident problems as desired.

[Arxiv](https://arxiv.org/abs/2506.09338)