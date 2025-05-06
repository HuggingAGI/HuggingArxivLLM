# # Qwen3 量化实证研究

发布时间：2025年05月04日

`LLM应用` `模型压缩`

> An Empirical Study of Qwen3 Quantization

# 摘要

> Qwen系列作为开源大型语言模型（LLMs）的佼佼者，在自然语言理解任务中表现卓越。随着Qwen3的最新发布，其在各类基准测试中的出色表现引发了人们对在资源受限环境中高效部署该模型的浓厚兴趣。低比特量化虽提供了一种有前景的解决方案，但其对Qwen3性能的影响仍待深入研究。本研究系统评估了Qwen3在不同量化设置下的表现，旨在揭示压缩这一先进模型所面临的机会与挑战。我们严格评估了5种现有经典训练后量化技术在Qwen3上的应用效果，涵盖从1到8比特的比特宽度，并在多个数据集上评估其有效性。研究发现表明，尽管Qwen3在中等比特宽度下仍能保持竞争力，但在超低精度下其在语言任务上的表现显著下降，凸显了大型语言模型压缩领域仍需克服的持续挑战。这些结果强调了进一步研究以缓解极端量化场景下性能损失的必要性。我们希望这项实证分析能为开发针对Qwen3及未来LLMs的量化方法提供切实可行的见解，最终提升其实际应用性而不妥协准确性。我们的项目已发布在https://github.com/Efficient-ML/Qwen3-Quantization和https://huggingface.co/collections/Efficient-ML/qwen3-quantization-68164450decb1c868788cb2b。

> The Qwen series has emerged as a leading family of open-source Large Language Models (LLMs), demonstrating remarkable capabilities in natural language understanding tasks. With the recent release of Qwen3, which exhibits superior performance across diverse benchmarks, there is growing interest in deploying these models efficiently in resource-constrained environments. Low-bit quantization presents a promising solution, yet its impact on Qwen3's performance remains underexplored. This study conducts a systematic evaluation of Qwen3's robustness under various quantization settings, aiming to uncover both opportunities and challenges in compressing this state-of-the-art model. We rigorously assess 5 existing classic post-training quantization techniques applied to Qwen3, spanning bit-widths from 1 to 8 bits, and evaluate their effectiveness across multiple datasets. Our findings reveal that while Qwen3 maintains competitive performance at moderate bit-widths, it experiences notable degradation in linguistic tasks under ultra-low precision, underscoring the persistent hurdles in LLM compression. These results emphasize the need for further research to mitigate performance loss in extreme quantization scenarios. We anticipate that this empirical analysis will provide actionable insights for advancing quantization methods tailored to Qwen3 and future LLMs, ultimately enhancing their practicality without compromising accuracy. Our project is released on https://github.com/Efficient-ML/Qwen3-Quantization and https://huggingface.co/collections/Efficient-ML/qwen3-quantization-68164450decb1c868788cb2b.

[Arxiv](https://arxiv.org/abs/2505.02214)