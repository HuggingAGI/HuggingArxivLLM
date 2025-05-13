# 精细专家模型的力量：粒度越高，表达能力越强——专家混合模型的探索

发布时间：2025年05月11日

`LLM理论` `人工智能` `模型架构`

> The power of fine-grained experts: Granularity boosts expressivity in Mixture of Experts

# 摘要

> 专家混合层（MoE）已成为前沿模型架构中的核心组件。通过选择性激活参数，它们在扩展模型容量的同时降低了计算成本。本文重点研究了"粒度"（即每层激活的专家数量）对模型性能的影响，对比了采用较多专家（如DeepSeek模型每层8个）与较少专家（如Llama-4模型每层1个）的架构设计。我们从理论上证明了粒度这一设计参数会导致网络表达能力的指数级差距，表明采用更高粒度的模型更具优势。实验结果不仅验证了我们的理论发现，还直观地展示了这种性能差距。

> Mixture-of-Experts (MoE) layers are increasingly central to frontier model architectures. By selectively activating parameters, they reduce computational cost while scaling total parameter count. This paper investigates the impact of the number of active experts, termed granularity, comparing architectures with many (e.g., 8 per layer in DeepSeek) to those with fewer (e.g., 1 per layer in Llama-4 models). We prove an exponential separation in network expressivity based on this design parameter, suggesting that models benefit from higher granularity. Experimental results corroborate our theoretical findings and illustrate this separation.

[Arxiv](https://arxiv.org/abs/2505.06839)