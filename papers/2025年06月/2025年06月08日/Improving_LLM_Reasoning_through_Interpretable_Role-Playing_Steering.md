# 通过可解释的角色扮演引导提升大语言模型的推理能力

发布时间：2025年06月08日

`LLM应用` `人工智能`

> Improving LLM Reasoning through Interpretable Role-Playing Steering

# 摘要

> 角色扮演已成为提升大型语言模型（LLMs）推理能力的有效技术，但现有方法多依赖提示工程，存在稳定性和可解释性不足的问题。本文提出了一种名为稀疏自动编码器角色扮演引导（SRPS）的新颖框架，能够识别并操纵与角色扮演行为相关的内部模型特征。我们的方法通过提取角色扮演提示的潜在表示，基于激活模式选择关键特征，并构建可调节强度的引导向量，将其注入模型残差流中，实现对角色特定行为的精细控制。实验结果表明，SRPS在多种推理基准测试中显著提升了模型性能。例如，在零样本链式思维（CoT）任务中，Llama3.1-8B在CSQA上的准确率从31.86%提升至39.80%，Gemma2-9B在SVAMP上的准确率从37.50%提升至45.10%。SRPS不仅增强了LLMs的推理能力，还提供了更优的可解释性和稳定性，为角色扮演技术的发展开辟了新方向。

> Role-playing has emerged as an effective technique for enhancing the reasoning capabilities of large language models (LLMs). However, existing methods primarily rely on prompt engineering, which often lacks stability and interpretability. In this paper, we introduce Sparse Autoencoder Role-Playing Steering (SRPS), a novel framework that identifies and manipulates internal model features associated with role-playing behavior. Our approach extracts latent representations from role-play prompts, selects the most relevant features based on activation patterns, and constructs a steering vector that can be injected into the model's residual stream with controllable intensity. Our method enables fine-grained control over role-specific behavior and offers insights into how role information influences internal model activations. Extensive experiments across various reasoning benchmarks and model sizes demonstrate consistent performance gains. Notably, in the zero-shot chain-of-thought (CoT) setting, the accuracy of Llama3.1-8B on CSQA improves from 31.86% to 39.80%, while Gemma2-9B on SVAMP increases from 37.50% to 45.10%. These results highlight the potential of SRPS to enhance reasoning ability in LLMs, providing better interpretability and stability compared to traditional prompt-based role-playing.

[Arxiv](https://arxiv.org/abs/2506.07335)