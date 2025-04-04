# 通用奖励建模的推理时间扩展

发布时间：2025年04月03日

`LLM理论`

> Inference-Time Scaling for Generalist Reward Modeling

# 摘要

> 强化学习（RL）在大规模语言模型（LLMs）的后训练中得到了广泛应用。最近，通过RL激励LLMs的推理能力表明，“恰当的学习方法能够实现有效的推理时扩展性”。RL的一个关键挑战是为LLMs在可验证问题或人工规则之外的各个领域获取准确的奖励信号。在这项工作中，我们研究如何通过增加推理计算来提升通用查询的奖励建模（RM），即“通用型RM的推理时扩展性”，以及如何通过恰当的学习方法进一步提升性能-计算扩展的有效性。

在RM方法上，我们采用点式生成奖励建模（GRM）以支持不同输入类型，并为推理时扩展提供潜力。在学习方法上，我们提出了基于在线RL的自我原则化批评调优（SPCT），以促进GRM中可扩展的奖励生成行为，自适应生成原则并准确生成批评，从而得到“DeepSeek-GRM”模型。此外，为了实现有效的推理时扩展，我们采用并行采样以扩展计算使用，并引入元奖励建模以指导投票过程，从而提升扩展性能。

实证研究表明，SPCT显著提升了GRM的质量和扩展性，在多种RM基准测试中超越现有方法和模型，且无明显偏见，相较于训练时扩展可实现更优性能。尽管DeepSeek-GRM在某些任务中仍面临挑战，但我们相信未来在通用型奖励系统中的努力可以解决这些问题。相关模型将开源发布。


> Reinforcement learning (RL) has been widely adopted in post-training for large language models (LLMs) at scale. Recently, the incentivization of reasoning capabilities in LLMs from RL indicates that $\textit{proper learning methods could enable effective inference-time scalability}$. A key challenge of RL is to obtain accurate reward signals for LLMs in various domains beyond verifiable questions or artificial rules. In this work, we investigate how to improve reward modeling (RM) with more inference compute for general queries, i.e. the $\textbf{inference-time scalability of generalist RM}$, and further, how to improve the effectiveness of performance-compute scaling with proper learning methods. For the RM approach, we adopt pointwise generative reward modeling (GRM) to enable flexibility for different input types and potential for inference-time scaling. For the learning method, we propose Self-Principled Critique Tuning (SPCT) to foster scalable reward generation behaviors in GRMs through online RL, to generate principles adaptively and critiques accurately, resulting in $\textbf{DeepSeek-GRM}$ models. Furthermore, for effective inference-time scaling, we use parallel sampling to expand compute usage, and introduce a meta RM to guide voting process for better scaling performance. Empirically, we show that SPCT significantly improves the quality and scalability of GRMs, outperforming existing methods and models in various RM benchmarks without severe biases, and could achieve better performance compared to training-time scaling. DeepSeek-GRM still meets challenges in some tasks, which we believe can be addressed by future efforts in generalist reward systems. The models will be released and open-sourced.

[Arxiv](https://arxiv.org/abs/2504.02495)