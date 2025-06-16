# 学习持续思考标记以提升测试时间扩展能力

发布时间：2025年06月12日

`LLM应用` `人工智能` `模型优化`

> Learning a Continue-Thinking Token for Enhanced Test-Time Scaling

# 摘要

> 测试时间缩放作为一种有效的手段，通过在推理过程中利用额外的计算资源来提升语言模型的性能。近期研究表明，替换结束思考标记（例如将“答案”替换为“等等”）可以延长推理步骤并提高准确性。在本研究中，我们探讨了是否可以学习一个专门的“继续思考”标记来触发更长的推理过程。我们通过强化学习在蒸馏版的DeepSeek-R1模型中添加了一个单独学习的“<|continue-thinking|>”标记，仅对其嵌入进行训练，同时保持模型权重不变。实验结果表明，与基线模型以及使用固定标记（如“等等”）进行预算强制的测试时间缩放方法相比，我们的学习标记方法在标准数学基准测试中实现了更高的准确率。特别地，在固定标记方法能够提升基线模型准确性的场景下，我们的方法带来了显著更大的提升。例如，在GSM8K基准测试中，固定标记方法使准确率绝对值提升了1.3%，而我们的学习标记方法相较于未使用预算强制的基线模型，准确率提升了4.2%。

> Test-time scaling has emerged as an effective approach for improving language model performance by utilizing additional compute at inference time. Recent studies have shown that overriding end-of-thinking tokens (e.g., replacing "</think>" with "Wait") can extend reasoning steps and improve accuracy. In this work, we explore whether a dedicated continue-thinking token can be learned to trigger extended reasoning. We augment a distilled version of DeepSeek-R1 with a single learned "<|continue-thinking|>" token, training only its embedding via reinforcement learning while keeping the model weights frozen. Our experiments show that this learned token achieves improved accuracy on standard math benchmarks compared to both the baseline model and a test-time scaling approach that uses a fixed token (e.g., "Wait") for budget forcing. In particular, we observe that in cases where the fixed-token approach enhances the base model's accuracy, our method achieves a markedly greater improvement. For example, on the GSM8K benchmark, the fixed-token approach yields a 1.3% absolute improvement in accuracy, whereas our learned-token method achieves a 4.2% improvement over the base model that does not use budget forcing.

[Arxiv](https://arxiv.org/abs/2506.11274)