# KTAE：无模型数学推理中的关键令牌优势估计算法。

发布时间：2025年05月22日

`LLM理论` `人工智能` `机器学习`

> KTAE: A Model-Free Algorithm to Key-Tokens Advantage Estimation in Mathematical Reasoning

# 摘要

> 强化学习与基于规则的奖励结合，无需监督微调即可显著提升大型语言模型的推理能力。然而，现有算法如GRPO及其变体DAPO在计算优势函数时存在粒度粗糙的问题，具体表现为无法捕捉序列内单个令牌的特定贡献，从而影响学习效果。为解决这一问题，我们提出了一种名为键令牌优势估计（KTAE）的新型算法。KTAE无需额外模型，通过统计分析量化单个令牌对最终结果的重要性，并结合序列级别优势，实现细粒度的令牌级别优势估计。实验结果表明，采用GRPO+KTAE和DAPO+KTAE训练的模型在五个数学推理基准测试中均优于基线方法，不仅以更短的响应实现了更高的准确率，甚至在使用相同基础模型的情况下超越了R1-Distill-Qwen-1.5B。

> Recent advances have demonstrated that integrating reinforcement learning with rule-based rewards can significantly enhance the reasoning capabilities of large language models, even without supervised fine-tuning. However, prevalent reinforcement learning algorithms such as GRPO and its variants like DAPO, suffer from a coarse granularity issue when computing the advantage. Specifically, they compute rollout-level advantages that assign identical values to every token within a sequence, failing to capture token-specific contributions and hindering effective learning. To address this limitation, we propose Key-token Advantage Estimation (KTAE) - a novel algorithm that estimates fine-grained, token-level advantages without introducing additional models. KTAE leverages the correctness of sampled rollouts and applies statistical analysis to quantify the importance of individual tokens within a sequence to the final outcome. This quantified token-level importance is then combined with the rollout-level advantage to obtain a more fine-grained token-level advantage estimation. Empirical results show that models trained with GRPO+KTAE and DAPO+KTAE outperform baseline methods across five mathematical reasoning benchmarks. Notably, they achieve higher accuracy with shorter responses and even surpass R1-Distill-Qwen-1.5B using the same base model.

[Arxiv](https://arxiv.org/abs/2505.16826)