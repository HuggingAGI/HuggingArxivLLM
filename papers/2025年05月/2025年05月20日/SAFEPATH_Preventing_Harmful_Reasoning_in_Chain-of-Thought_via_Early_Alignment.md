# # SAFEPATH: Preventing Harmful Reasoning in Chain-of-Thought via Early Alignment
SAFEPATH：通过早期对齐机制遏制链式推理中的有害推理

发布时间：2025年05月20日

`LLM理论` `人工智能` `AI安全`

> SAFEPATH: Preventing Harmful Reasoning in Chain-of-Thought via Early Alignment

# 摘要

> 大型推理模型（LRMs）在解决复杂问题方面表现出色，但它们的结构化推理路径在面对有害提示时可能产生不安全输出。现有的安全对齐方法虽然能减少有害输出，但会降低推理深度，在复杂多步骤任务中带来权衡，并且仍易受高级越狱攻击。为解决这一问题，我们提出了一种轻量级对齐方法SAFEPATH。该方法通过在推理开始时微调LRMs，使其输出一个简短的8个令牌安全启动文本，从而在面对有害提示时做出响应，同时保持其余推理过程不受监督。实验结果显示，SAFEPATH能够有效减少有害输出，同时保持推理性能。具体而言，在DeepSeek-R1-Distill-Llama-8B模型中，SAFEPATH将有害响应减少了高达90.0%，并阻止了83.3%的越狱尝试，计算量只需Direct Refusal的295.9分之一，以及SafeChain的314.1分之一。我们还提供了一种无需微调的零样本变体。此外，我们分析了现有LLMs方法在推理中心模型中的表现，揭示了实现更安全AI的关键差距和新方向。

> Large Reasoning Models (LRMs) have become powerful tools for complex problem solving, but their structured reasoning pathways can lead to unsafe outputs when exposed to harmful prompts. Existing safety alignment methods reduce harmful outputs but can degrade reasoning depth, leading to significant trade-offs in complex, multi-step tasks, and remain vulnerable to sophisticated jailbreak attacks. To address this, we introduce SAFEPATH, a lightweight alignment method that fine-tunes LRMs to emit a short, 8-token Safety Primer at the start of their reasoning, in response to harmful prompts, while leaving the rest of the reasoning process unsupervised. Empirical results across multiple benchmarks indicate that SAFEPATH effectively reduces harmful outputs while maintaining reasoning performance. Specifically, SAFEPATH reduces harmful responses by up to 90.0% and blocks 83.3% of jailbreak attempts in the DeepSeek-R1-Distill-Llama-8B model, while requiring 295.9x less compute than Direct Refusal and 314.1x less than SafeChain. We further introduce a zero-shot variant that requires no fine-tuning. In addition, we provide a comprehensive analysis of how existing methods in LLMs generalize, or fail, when applied to reasoning-centric models, revealing critical gaps and new directions for safer AI.

[Arxiv](https://arxiv.org/abs/2505.14667)