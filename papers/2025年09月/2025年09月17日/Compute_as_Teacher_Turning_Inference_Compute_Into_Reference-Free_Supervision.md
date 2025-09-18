# 以计算为师：将推理计算转化为无参考监督

发布时间：2025年09月17日

`强化学习` `基础理论`

> Compute as Teacher: Turning Inference Compute Into Reference-Free Supervision

# 摘要

> 训练后若缺乏真实标签，学习信号从何而来？为此，我们提出计算即教师（CaT）方法，将探索转化为监督信号——通过从一组并行推理轨迹中合成单一参考，并以此为优化目标，将模型推理时的自主探索转化为无参考监督。具体实现中，当前策略生成多组推理轨迹；冻结锚点（即初始策略）通过调和轨迹中的遗漏与矛盾来估计参考值，从而将额外的推理计算转化为教师信号。我们将该机制转化为两种奖励模式：（i）可验证任务采用最终答案的程序等价性；（ii）不可验证任务则使用自拟评分标准——由独立LLM评判器对二元可审计标准打分，奖励由满足标准的比例决定。与选择方法（如N选优、多数投票、困惑度或评判分数）不同，合成方法即使与多数轨迹不一致，甚至在所有轨迹均错误时仍可能给出正确结果；其性能随轨迹数量的增加而提升。作为测试时优化方法，CaT显著提升了Gemma 3 4B、Qwen 3 4B和Llama 3.1 8B的表现（在MATH-500上提升高达27%，在HealthBench上提升12%）。结合强化学习（CaT-RL）后，性能进一步提升（最高达33%和30%），且训练后的策略表现超越了初始教师信号。

> Where do learning signals come from when there is no ground truth in post-training? We propose turning exploration into supervision through Compute as Teacher (CaT), which converts the model's own exploration at inference-time into reference-free supervision by synthesizing a single reference from a group of parallel rollouts and then optimizing toward it. Concretely, the current policy produces a group of rollouts; a frozen anchor (the initial policy) reconciles omissions and contradictions to estimate a reference, turning extra inference-time compute into a teacher signal. We turn this into rewards in two regimes: (i) verifiable tasks use programmatic equivalence on final answers; (ii) non-verifiable tasks use self-proposed rubrics-binary, auditable criteria scored by an independent LLM judge, with reward given by the fraction satisfied. Unlike selection methods (best-of-N, majority, perplexity, or judge scores), synthesis may disagree with the majority and be correct even when all rollouts are wrong; performance scales with the number of rollouts. As a test-time procedure, CaT improves Gemma 3 4B, Qwen 3 4B, and Llama 3.1 8B (up to +27% on MATH-500; +12% on HealthBench). With reinforcement learning (CaT-RL), we obtain further gains (up to +33% and +30%), with the trained policy surpassing the initial teacher signal.

[Arxiv](https://arxiv.org/abs/2509.14234)