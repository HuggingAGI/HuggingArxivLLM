# ReDit：通过奖励微调优化LLM策略

发布时间：2025年06月24日

`Agent

这篇论文探讨了强化学习中的奖励机制优化，特别是通过添加随机噪声来改善离散奖励信号，从而提升智能体的训练效果。因此，它属于Agent类别。` `人工智能` `机器学习`

> ReDit: Reward Dithering for Improved LLM Policy Optimization

# 摘要

> DeepSeek-R1 通过其基于规则的奖励系统成功增强了大型语言模型（LLM）的推理能力。虽然这是一个“完美”的奖励系统，能够有效缓解奖励 hacking 问题，但此类奖励函数往往是离散的。我们的实验观察表明，离散奖励可能导致梯度异常、优化不稳定以及收敛速度缓慢。为了解决这一问题，我们提出了 ReDit（Reward Dithering），一种通过添加简单随机噪声来对离散奖励信号进行抖动的方法。借助这种扰动后的奖励信号，在整个学习过程中持续提供探索性梯度，从而实现更平滑的梯度更新并加速收敛。注入的噪声还为平坦奖励区域引入了随机性，促使模型探索新策略并摆脱局部最优。在多种任务上的实验结果证明了 ReDit 的有效性和高效性。平均而言，ReDit 仅需约 10% 的训练步骤即可达到与 vanilla GRPO 相当的性能，而且在训练时间相近的情况下，性能还比 vanilla GRPO 高出 4%。可视化结果进一步证实了 ReDit 对梯度问题的显著缓解效果。此外，我们还提供了理论分析以进一步验证这些优势。

> DeepSeek-R1 has successfully enhanced Large Language Model (LLM) reasoning capabilities through its rule-based reward system. While it's a ''perfect'' reward system that effectively mitigates reward hacking, such reward functions are often discrete. Our experimental observations suggest that discrete rewards can lead to gradient anomaly, unstable optimization, and slow convergence. To address this issue, we propose ReDit (Reward Dithering), a method that dithers the discrete reward signal by adding simple random noise. With this perturbed reward, exploratory gradients are continuously provided throughout the learning process, enabling smoother gradient updates and accelerating convergence. The injected noise also introduces stochasticity into flat reward regions, encouraging the model to explore novel policies and escape local optima. Experiments across diverse tasks demonstrate the effectiveness and efficiency of ReDit. On average, ReDit achieves performance comparable to vanilla GRPO with only approximately 10% the training steps, and furthermore, still exhibits a 4% performance improvement over vanilla GRPO when trained for a similar duration. Visualizations confirm significant mitigation of gradient issues with ReDit. Moreover, theoretical analyses are provided to further validate these advantages.

[Arxiv](https://arxiv.org/abs/2506.18631)