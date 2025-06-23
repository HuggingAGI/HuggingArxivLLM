# 利用潜在转向向量进行分式推理，显著提升推理计算效率

发布时间：2025年06月18日

`LLM应用` `人工智能`

> Fractional Reasoning via Latent Steering Vectors Improves Inference Time Compute

# 摘要

> 测试时推理已成为提升大型语言模型性能的强大范式。通过生成多个输出或优化单个推理链，可以显著提升答案的准确性。然而，现有方法（如Best-of-N、多数投票和自我反思）往往对所有输入采用统一的推理方式，忽视了不同问题可能需要不同推理深度的事实。本研究提出了Fractional Reasoning，这是一种无需训练、与模型无关的框架，能够在推理过程中对推理强度进行连续控制，突破固定指令提示的限制。通过提取与更深层次推理相关的潜在引导向量，并将其重新应用到可调节的缩放因子中，使模型能够根据输入的复杂性调整其推理过程。这支持了两种关键的测试时扩展模式：（1）在基于广度的策略（如Best-of-N、多数投票）中提升输出质量，以及（2）在基于深度的策略（如自我反思）中增强单个推理链的正确性。实验结果表明，Fractional Reasoning在GSM8K、MATH500和GPQA等数据集上，能够显著提升多种推理任务和模型的性能。

> Test-time compute has emerged as a powerful paradigm for improving the performance of large language models (LLMs), where generating multiple outputs or refining individual chains can significantly boost answer accuracy. However, existing methods like Best-of-N, majority voting, and self-reflection typically apply reasoning in a uniform way across inputs, overlooking the fact that different problems may require different levels of reasoning depth. In this work, we propose Fractional Reasoning, a training-free and model-agnostic framework that enables continuous control over reasoning intensity at inference time, going beyond the limitations of fixed instructional prompts. Our method operates by extracting the latent steering vector associated with deeper reasoning and reapplying it with a tunable scaling factor, allowing the model to tailor its reasoning process to the complexity of each input. This supports two key modes of test-time scaling: (1) improving output quality in breadth-based strategies (e.g., Best-of-N, majority voting), and (2) enhancing the correctness of individual reasoning chains in depth-based strategies (e.g., self-reflection). Experiments on GSM8K, MATH500, and GPQA demonstrate that Fractional Reasoning consistently improves performance across diverse reasoning tasks and models.

[Arxiv](https://arxiv.org/abs/2506.15882)