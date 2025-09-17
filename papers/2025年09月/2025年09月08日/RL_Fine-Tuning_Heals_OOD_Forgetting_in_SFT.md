# 强化学习微调修复监督微调中的分布外遗忘

发布时间：2025年09月08日

`LLM理论` `基础理论`

> RL Fine-Tuning Heals OOD Forgetting in SFT

# 摘要

> 监督微调（SFT）后接强化学习（RL）的两阶段微调范式，在大型语言模型（LLMs）的后训练中，实证表明其推理性能优于单阶段SFT。但SFT与RL协同作用背后的演变过程及机制仍有待深入探索，结论尚不明确。本研究发现，“先SFT记忆，后RL泛化”这一常见观点过于简化，并得出以下结论：(1) 分布外（OOD）性能在SFT初期达到峰值后便开始下降（即OOD遗忘），且最佳SFT检查点无法通过训练/测试损失来判断；(2) 后续的RL阶段并未从根本上提升OOD能力，而是发挥了	extbf{OOD恢复}作用，弥补了SFT过程中丢失的推理能力；(3) 这种恢复能力存在局限：	extbf{若SFT训练时间过短或过长，RL将无法恢复丢失的OOD能力；} (4) 为揭示遗忘与恢复过程的内在机制，我们对参数矩阵进行奇异值分解（SVD）分析，手动编辑矩阵并观察其对模型性能的影响。研究发现，与普遍观点认为模型能力变化主要源于奇异值改变不同，奇异值在整个微调过程中其实相当稳定；相反，OOD表现与	extbf{奇异向量的旋转}密切相关。我们的研究重新明确了SFT与RL在两阶段微调中的作用，并揭示奇异向量的旋转是关键机制。代码可访问https://github.com/xiaodanguoguo/RL_Heals_SFT获取。

> The two-stage fine-tuning paradigm of Supervised Fine-Tuning (SFT) followed by Reinforcement Learning (RL) has empirically shown better reasoning performance than one-stage SFT for the post-training of Large Language Models (LLMs). However, the evolution and mechanism behind the synergy of SFT and RL are still under-explored and inconclusive. In our study, we find the well-known claim "SFT memorizes, RL generalizes" is over-simplified, and discover that: (1) OOD performance peaks at the early stage of SFT and then declines (OOD forgetting), the best SFT checkpoint cannot be captured by training/test loss; (2) the subsequent RL stage does not generate fundamentally better OOD capability, instead it plays an \textbf{OOD restoration} role, recovering the lost reasoning ability during SFT; (3) The recovery ability has boundaries, \ie{} \textbf{if SFT trains for too short or too long, RL cannot recover the lost OOD ability;} (4) To uncover the underlying mechanisms behind the forgetting and restoration process, we employ SVD analysis on parameter matrices, manually edit them, and observe their impacts on model performance. Unlike the common belief that the shift of model capacity mainly results from the changes of singular values, we find that they are actually quite stable throughout fine-tuning. Instead, the OOD behavior strongly correlates with the \textbf{rotation of singular vectors}. Our findings re-identify the roles of SFT and RL in the two-stage fine-tuning and discover the rotation of singular vectors as the key mechanism. %reversing the rotations induced by SFT, which shows recovery from forgetting, whereas imposing the SFT parameter directions onto a RL-tuned model results in performance degradation. Code is available at https://github.com/xiaodanguoguo/RL_Heals_SFT

[Arxiv](https://arxiv.org/abs/2509.12235)