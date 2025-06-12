# 要么FP32，要么死亡！可重复推理的挑战与解决方案

发布时间：2025年06月11日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在推理过程中的可重复性问题，深入分析了数值精度对模型输出的影响，并提出了改进方法。这属于对LLM内在机制和性能的理论研究。` `计算机科学`

> Give Me FP32 or Give Me Death? Challenges and Solutions for Reproducible Reasoning

# 摘要

> 大型语言模型（LLMs）如今在各个领域中发挥着重要作用，并展现出了卓越的性能。然而，这些进展建立在基准分数既准确又可重复的基础之上。我们发现，LLM性能的可重复性十分脆弱：调整系统配置，如评估批次大小、GPU数量及版本，都会对生成的回复产生显著差异。这一问题在推理模型中尤为突出，早期token的微小舍入差异可能引发截然不同的思维链，最终影响准确性。例如，采用bfloat16精度配合贪婪解码策略时，DeepSeek-R1-Distill-Qwen-7B这类推理模型因GPU数量、类型及评估批次大小的不同，准确率可相差高达9%，回复长度差异甚至可达9,000个token。我们追溯这一变异性根源至有限数值精度下浮点运算的非结合性。本研究首次系统性探究了数值精度对LLM推理可重复性的影响。通过在不同硬件、软件及精度设置下精心设计的实验，我们量化了模型输出偏离的时间点及方式。分析表明，尽管浮点精度对可重复性至关重要，但在评估实践中常被忽视。受此启发，我们开发了一条轻量级推理管线——LayerCast，该方案将权重存储为16位精度，但在所有计算中使用FP32，从而在内存效率与数值稳定性之间取得平衡。代码已开源，地址为：https://github.com/nanomaoli/llm_reproducibility。


> Large Language Models (LLMs) are now integral across various domains and have demonstrated impressive performance. Progress, however, rests on the premise that benchmark scores are both accurate and reproducible. We demonstrate that the reproducibility of LLM performance is fragile: changing system configuration such as evaluation batch size, GPU count, and GPU version can introduce significant difference in the generated responses. This issue is especially pronounced in reasoning models, where minor rounding differences in early tokens can cascade into divergent chains of thought, ultimately affecting accuracy. For instance, under bfloat16 precision with greedy decoding, a reasoning model like DeepSeek-R1-Distill-Qwen-7B can exhibit up to 9% variation in accuracy and 9,000 tokens difference in response length due to differences in GPU count, type, and evaluation batch size. We trace the root cause of this variability to the non-associative nature of floating-point arithmetic under limited numerical precision. This work presents the first systematic investigation into how numerical precision affects reproducibility in LLM inference. Through carefully controlled experiments across various hardware, software, and precision settings, we quantify when and how model outputs diverge. Our analysis reveals that floating-point precision -- while critical for reproducibility -- is often neglected in evaluation practices. Inspired by this, we develop a lightweight inference pipeline, dubbed LayerCast, that stores weights in 16-bit precision but performs all computations in FP32, balancing memory efficiency with numerical stability. Code is available at https://github.com/nanomaoli/llm_reproducibility.

[Arxiv](https://arxiv.org/abs/2506.09501)