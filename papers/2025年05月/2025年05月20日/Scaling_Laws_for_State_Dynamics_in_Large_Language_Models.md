# 大型语言模型中状态动力学的缩放规律

发布时间：2025年05月20日

`LLM理论` `人工智能`

> Scaling Laws for State Dynamics in Large Language Models

# 摘要

> 大型语言模型（LLMs）在需要内部状态跟踪的任务中被越来越多地应用，但它们建模状态转换动态的能力仍不为人所理解。我们评估了LLMs在三个领域中对确定性状态动态的捕捉能力：盒子跟踪、抽象DFA序列和复杂文本游戏，每个领域都可以形式化为有限状态系统。在所有任务中，我们发现，随着状态空间大小和稀疏转换的增加，下一步状态预测的准确性会下降。GPT-2 XL在低复杂度设置下能达到约70%的准确率，但当盒子或状态数量分别超过5或10时，准确率会降至30%以下。在DFA任务中，当状态数量超过10且转换少于30时，Pythia-1B的准确率无法超过50%。通过激活补丁技术，我们识别出负责传播状态信息的注意力头：GPT-2 XL第22层第20个头，以及Pythia-1B第10、11、12和14层的头。尽管这些头能够成功移动相关状态特征，但动作信息未能可靠地传递到最终标记，表明状态-动作联合推理能力较弱。我们的研究结果表明，LLMs中的状态跟踪源自下一个标记头的分布式交互，而非显式的符号计算。

> Large Language Models (LLMs) are increasingly used in tasks requiring internal state tracking, yet their ability to model state transition dynamics remains poorly understood. We evaluate how well LLMs capture deterministic state dynamics across 3 domains: Box Tracking, Abstract DFA Sequences, and Complex Text Games, each formalizable as a finite-state system. Across tasks, we find that next-state prediction accuracy degrades with increasing state-space size and sparse transitions. GPT-2 XL reaches about 70% accuracy in low-complexity settings but drops below 30% when the number of boxes or states exceeds 5 or 10, respectively. In DFA tasks, Pythia-1B fails to exceed 50% accuracy when the number of states is > 10 and transitions are < 30. Through activation patching, we identify attention heads responsible for propagating state information: GPT-2 XL Layer 22 Head 20, and Pythia-1B Heads at Layers 10, 11, 12, and 14. While these heads successfully move relevant state features, action information is not reliably routed to the final token, indicating weak joint state-action reasoning. Our results suggest that state tracking in LLMs emerges from distributed interactions of next-token heads rather than explicit symbolic computation.

[Arxiv](https://arxiv.org/abs/2505.14892)