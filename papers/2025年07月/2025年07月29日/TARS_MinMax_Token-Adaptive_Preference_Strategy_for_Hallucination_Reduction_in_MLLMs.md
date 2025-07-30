# TARS：针对多语言大模型幻觉问题的MinMax自适应令牌偏好策略

发布时间：2025年07月29日

`LLM应用` `人工智能`

> TARS: MinMax Token-Adaptive Preference Strategy for Hallucination Reduction in MLLMs

# 摘要

> 多模态大型语言模型 (MLLMs) 虽然实现了视觉语言推理，但常常生成看似合理却事实错误或视觉无依据的输出，从而影响其可靠性。直接偏好优化 (DPO) 是一种常见的通过将模型输出与人类偏好对齐来纠正幻觉的方法。现有的 DPO 策略通常将与幻觉相关的偏好视为固定目标，在训练过程中依赖静态监督信号。这种方法倾向于过度拟合偏好数据中的表面语言线索，导致分布僵化和虚假相关性，从而削弱了对因果相关视觉信息的依据。为了解决这一限制，我们提出了一种基于令牌的自适应偏好策略 TARS，将 DPO 重新表述为一个极小极大优化问题。TARS 在语义约束下最大化令牌级分布变化，模拟对齐不确定性，同时在这些受控扰动下最小化预期偏好损失。这一联合目标在减少对偏好模式的过度拟合的同时，保留了因果依据，从而减少了多模态推理中的幻觉。我们在多个幻觉基准上评估了 TARS，并发现其表现一致强劲。仅使用 4.8k 个偏好样本且无需专家反馈，TARS 将幻觉率从 26.4% 降至 13.2%，并将认知价值从 2.5 降至 0.4。它在多个关键指标上优于标准 DPO，并与 GPT-4o 相匹配。

> Multimodal large language models (MLLMs) enable vision-language reasoning, yet often generate plausible outputs that are factually incorrect or visually ungrounded, thereby compromising their reliability. Direct preference optimization (DPO) is a common strategy for correcting hallucinations by aligning model outputs with human preferences. Existing DPO strategies typically treat hallucination-related preferences as fixed targets, relying on static supervision signals during training. This approach tends to overfit to superficial linguistic cues in preference data, leading to distributional rigidity and spurious correlations that impair grounding in causally relevant visual information. To overcome this limitation, we propose TARS, a token-adaptive preference strategy that reformulates DPO as a min-max optimization problem. TARS maximizes token-level distributional shifts under semantic constraints to simulate alignment uncertainty, and simultaneously minimizes the expected preference loss under these controlled perturbations. This joint objective preserves causal grounding while mitigating overfitting to preference patterns, thereby reducing hallucinations in multimodal reasoning. We evaluate TARS on multiple hallucination benchmarks and find consistently strong performance. Using only 4.8k preference samples and no expert feedback, TARS reduces hallucination rates from 26.4% to 13.2% and decreases cognition value from 2.5 to 0.4. It outperforms standard DPO and matches GPT-4o on several key metrics.

[Arxiv](https://arxiv.org/abs/2507.21584)