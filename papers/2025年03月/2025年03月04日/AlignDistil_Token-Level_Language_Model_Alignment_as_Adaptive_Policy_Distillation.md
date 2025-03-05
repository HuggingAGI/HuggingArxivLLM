# AlignDistil：Token级语言模型对齐，一种自适应策略蒸馏方法

发布时间：2025年03月04日

`LLM理论` `机器学习`

> AlignDistil: Token-Level Language Model Alignment as Adaptive Policy Distillation

# 摘要

> 在现代大型语言模型（LLMs）中，模型对齐至关重要，通常通过强化学习从人类反馈（RLHF）和直接偏好优化（DPO）实现。然而，现有方法多采用稀疏的响应级奖励优化所有标记，忽略了标记级奖励的重要性。这可能导致高质量标记被误罚或低质量标记被误奖，影响模型性能和收敛速度。为解决这一问题，我们提出了AlignDistil，一种用于标记级奖励优化的RLHF等效蒸馏方法。具体来说，我们将DPO学习到的奖励融入RLHF目标，并证明该目标与标记级蒸馏过程等价，其中教师分布由DPO模型和参考模型的逻辑回归结果线性组合而成。在此基础上，我们通过构建对比DPO奖励，结合正向和反向DPO模型，进一步缩小了DPO模型奖励与纯奖励模型之间的差距。此外，为了避免对不同标记的欠优化和过优化，我们设计了标记自适应逻辑回归外推机制，为每个标记构建适当的教师分布。实验结果表明，AlignDistil在现有方法中表现优异，且因标记级分布奖励优化而快速收敛。

> In modern large language models (LLMs), LLM alignment is of crucial importance and is typically achieved through methods such as reinforcement learning from human feedback (RLHF) and direct preference optimization (DPO). However, in most existing methods for LLM alignment, all tokens in the response are optimized using a sparse, response-level reward or preference annotation. The ignorance of token-level rewards may erroneously punish high-quality tokens or encourage low-quality tokens, resulting in suboptimal performance and slow convergence speed. To address this issue, we propose AlignDistil, an RLHF-equivalent distillation method for token-level reward optimization. Specifically, we introduce the reward learned by DPO into the RLHF objective and theoretically prove the equivalence between this objective and a token-level distillation process, where the teacher distribution linearly combines the logits from the DPO model and a reference model. On this basis, we further bridge the accuracy gap between the reward from the DPO model and the pure reward model, by building a contrastive DPO reward with a normal and a reverse DPO model. Moreover, to avoid under- and over-optimization on different tokens, we design a token adaptive logit extrapolation mechanism to construct an appropriate teacher distribution for each token. Experimental results demonstrate the superiority of our AlignDistil over existing methods and showcase fast convergence due to its token-level distributional reward optimization.

[Arxiv](https://arxiv.org/abs/2503.02832)