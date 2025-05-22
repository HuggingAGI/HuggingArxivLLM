# 推理的能耗成本：分析 LLM 中的能源使用情况与推理时计算

发布时间：2025年05月19日

`LLM应用` `人工智能` `计算资源管理`

> The Energy Cost of Reasoning: Analyzing Energy Usage in LLMs with Test-time Compute

# 摘要

> 大规模语言模型的扩展推动了显著的技术进步，但也面临着边际收益递减和能源需求激增的挑战。本研究提出了一种创新的解决方案——测试时间计算（TTC），即在推理过程中动态分配额外计算资源，作为传统扩展策略的有力补充。通过实证分析，我们发现TTC在准确性和能源效率方面均优于传统模型扩展，尤其在需要复杂推理的任务中表现更为突出。此外，我们揭示了TTC性能与输出序列长度之间的关键交互作用，证明了根据查询复杂度在推理时动态调整计算资源能够显著提升效率。这一发现为未来语言模型的可持续、准确和适应性部署提供了新的方向，无需额外的预训练成本即可实现更高效的模型应用。

> Scaling large language models (LLMs) has driven significant advancements, yet it faces diminishing returns and escalating energy demands. This work introduces test-time compute (TTC)-allocating additional computational resources during inference-as a compelling complement to conventional scaling strategies. Specifically, we investigate whether employing TTC can achieve superior accuracy-energy trade-offs compared to simply increasing model size. Our empirical analysis reveals that TTC surpasses traditional model scaling in accuracy/energy efficiency, with notable gains in tasks demanding complex reasoning rather than mere factual recall. Further, we identify a critical interaction between TTC performance and output sequence length, demonstrating that strategically adjusting compute resources at inference time according to query complexity can substantially enhance efficiency. Our findings advocate for TTC as a promising direction, enabling more sustainable, accurate, and adaptable deployment of future language models without incurring additional pretraining costs.

[Arxiv](https://arxiv.org/abs/2505.14733)