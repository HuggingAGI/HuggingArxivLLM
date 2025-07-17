# 模型思考尚未完成，我们能否预测对齐？探索监控偏离预期的推理模型之路

发布时间：2025年07月16日

`LLM应用` `生成模型`

> Can We Predict Alignment Before Models Finish Thinking? Towards Monitoring Misaligned Reasoning Models

# 摘要

> 开放权重推理语言模型通过生成长的思维链（CoTs）后再输出最终结果，虽然提升了性能，但也带来了额外的对齐风险，有害内容经常出现在思维链和最终输出中。本文研究了是否可以利用思维链来预测最终响应的对齐情况。我们评估了多种监控方法，包括人工审核、功能强大的大型语言模型和文本分类器，使用思维链文本或激活值作为输入。首先，我们发现仅基于思维链激活值训练的简单线性探针在预测最终响应是否安全方面显著优于所有文本基线方法。思维链文本往往不忠实，容易误导人工审核和分类器，而模型潜在表征（即思维链激活值）提供了更可靠的预测信号。其次，该探针可以在推理完成前就做出准确预测，即使应用于早期思维链片段也能表现优异。这些发现适用于不同规模、架构和安全基准的模型，表明轻量化探针可用于生成过程中的实时安全监控和早期干预。

> Open-weights reasoning language models generate long chains-of-thought (CoTs) before producing a final response, which improves performance but introduces additional alignment risks, with harmful content often appearing in both the CoTs and the final outputs. In this work, we investigate if we can use CoTs to predict final response misalignment. We evaluate a range of monitoring approaches, including humans, highly-capable large language models, and text classifiers, using either CoT text or activations. First, we find that a simple linear probe trained on CoT activations can significantly outperform all text-based methods in predicting whether a final response will be safe or unsafe. CoT texts are often unfaithful and can mislead humans and classifiers, while model latents (i.e., CoT activations) offer a more reliable predictive signal. Second, the probe makes accurate predictions before reasoning completes, achieving strong performance even when applied to early CoT segments. These findings generalize across model sizes, families, and safety benchmarks, suggesting that lightweight probes could enable real-time safety monitoring and early intervention during generation.

[Arxiv](https://arxiv.org/abs/2507.12428)