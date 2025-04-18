# SHA256 在 SemEval-2025 任务4中的表现：选择性遗忘——通过知识隔离实现大型语言模型的约束性无学习

发布时间：2025年04月17日

`LLM理论` `数据隐私` `人工智能`

> SHA256 at SemEval-2025 Task 4: Selective Amnesia -- Constrained Unlearning for Large Language Models via Knowledge Isolation

# 摘要

> 大型语言模型 (LLMs) 在训练过程中往往会记住训练数据中的敏感信息，这在部署公开可用模型时带来了潜在风险。当前的机器遗忘 (machine unlearning) 方法在不降低模型整体能力的前提下，难以选择性地移除特定数据关联。本文提出了我们在 SemEval-2025 任务 4 中针对目标遗忘问题的解决方案，该方案采用了一种结合因果中介分析 (causal mediation analysis) 与分层优化 (layer-specific optimization) 的两阶段方法。通过在 OLMo 架构（10亿和70亿参数）上的系统性因果追踪实验，我们发现前几层 Transformer 层（第0-5层）在存储主体-属性关联方面起到了关键作用。基于这一发现，我们开发了一种约束优化方法，该方法通过冻结上层网络，同时对下层网络应用一种新型联合损失函数，实现了对遗忘集损失的最大化（通过输出 token 的交叉熵惩罚）和对保留集偏差的最小化（通过自适应正则化）。我们的方法在10亿参数模型赛道中获得了第二名，不仅展现了强大的任务性能，还保持了88%的基线 MMLU 准确率。这些结果表明，基于因果关系的分层优化是一种在大型语言模型中实现高效、精准遗忘的有前景的方法范式，为解决人工智能系统中的数据隐私问题迈出了重要一步。

> Large language models (LLMs) frequently memorize sensitive information during training, posing risks when deploying publicly accessible models. Current machine unlearning methods struggle to selectively remove specific data associations without degrading overall model capabilities. This paper presents our solution to SemEval-2025 Task 4 on targeted unlearning, which introduces a two-stage methodology that combines causal mediation analysis with layer-specific optimization. Through systematic causal tracing experiments on OLMo architectures (1B and 7B parameters), we identify the critical role of the first few transformer layers (layers 0-5) in storing subject-attribute associations within MLP modules. Building on this insight, we develop a constrained optimization approach that freezes upper layers while applying a novel joint loss function to lower layers-simultaneously maximizing forget set loss via output token cross-entropy penalties and minimizing retain set deviation through adaptive regularization. Our method achieves 2nd place in the 1B model track, demonstrating strong task performance while maintaining 88% of baseline MMLU accuracy. These results establish causal-informed layer optimization as a promising paradigm for efficient, precise unlearning in LLMs, offering a significant step forward in addressing data privacy concerns in AI systems.

[Arxiv](https://arxiv.org/abs/2504.12996)