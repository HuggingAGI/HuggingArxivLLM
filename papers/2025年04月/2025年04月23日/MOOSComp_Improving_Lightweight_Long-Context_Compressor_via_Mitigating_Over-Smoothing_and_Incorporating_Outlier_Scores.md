# MOOSComp：抑制过度平滑并结合异常评分的轻量化长上下文压缩器改进方案

发布时间：2025年04月23日

`LLM应用` `移动应用` `资源优化`

> MOOSComp: Improving Lightweight Long-Context Compressor via Mitigating Over-Smoothing and Incorporating Outlier Scores

# 摘要

> 大型语言模型在处理长上下文输入方面的能力有了显著提升，但在实际应用中，推理时间和资源消耗的增加，尤其是在资源受限的环境中，仍是亟待解决的挑战。为此，我们提出了MOOSComp——一种基于令牌分类的长上下文压缩方法。该方法通过缓解过平滑问题并引入异常分数，显著提升了基于BERT的压缩器的性能。

在训练阶段，我们引入了类间余弦相似度损失项，以惩罚过于相似的令牌表示，从而提高了令牌分类的准确性。在压缩阶段，我们通过异常分数保留了那些在任务无关压缩中容易被丢弃的罕见但关键的令牌。这些分数与分类器的输出相结合，使压缩器更具通用性，能够适应各种任务需求。

在长上下文理解与推理基准测试中，MOOSComp在多种压缩比率下均表现优异。特别值得一提的是，在资源受限的移动设备上，以4倍的压缩比率实现了3.3倍的加速效果，充分展现了其在实际应用中的潜力。

> Recent advances in large language models have significantly improved their ability to process long-context input, but practical applications are challenged by increased inference time and resource consumption, particularly in resource-constrained environments. To address these challenges, we propose MOOSComp, a token-classification-based long-context compression method that enhances the performance of a BERT-based compressor by mitigating the over-smoothing problem and incorporating outlier scores. In the training phase, we add an inter-class cosine similarity loss term to penalize excessively similar token representations, thereby improving the token classification accuracy. During the compression phase, we introduce outlier scores to preserve rare but critical tokens that are prone to be discarded in task-agnostic compression. These scores are integrated with the classifier's output, making the compressor more generalizable to various tasks. Superior performance is achieved at various compression ratios on long-context understanding and reasoning benchmarks. Moreover, our method obtains a speedup of 3.3x at a 4x compression ratio on a resource-constrained mobile device.

[Arxiv](https://arxiv.org/abs/2504.16786)