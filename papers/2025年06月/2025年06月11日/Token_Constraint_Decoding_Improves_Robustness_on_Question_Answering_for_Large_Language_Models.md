# Token约束解码提升大型语言模型在问答任务中的鲁棒性

发布时间：2025年06月11日

`LLM应用

理由：论文讨论了大型语言模型在特定任务中的表现，并提出了一种改进推理阶段的方法，以提升模型的鲁棒性和实际应用中的性能，属于模型的应用层面。`

> Token Constraint Decoding Improves Robustness on Question Answering for Large Language Models

# 摘要

> 大型语言模型（LLMs）在多项选择题回答（MCQA）任务中表现优异，但对输入的小幅度扰动仍高度敏感。本文提出并评估了一种名为Token约束解码（TCD）的创新方法。这一简单而有效的推理阶段算法通过强制对齐词级别预测，显著提升了模型在噪声环境下的鲁棒性。通过在CommonsenseQA、MMLU和MMLU-Pro数据集上的广泛实验，我们发现TCD，尤其是与提示工程（PE）修复结合时，能有效恢复因输入噪声导致的性能下降，为如Gemma3 1B等较弱模型带来最高达+39%的绝对性能提升。进一步的惩罚幅度扫描分析表明，TCD能够隐式地对过度自信的输出进行正则化处理，不同模型需要不同的惩罚计划以最大化其韧性。我们的研究结果证实了TCD作为一种实用且模型不可知论的方法，能够显著提升推理稳定性，为在现实世界不完美条件下更可靠地部署LLMs奠定了基础，并为在安全关键或面向用户的场景中实现更可靠的LLM应用铺平了道路。

> Large Language Models (LLMs) have demonstrated impressive performance on multiple-choice question answering (MCQA) benchmarks, yet they remain highly vulnerable to minor input perturbations. In this paper, we introduce and evaluate Token Constraint Decoding (TCD). This simple yet effective inference-time algorithm enforces alignment between token-level predictions to enhance robustness in noisy settings. Through extensive experiments on CommonsenseQA, MMLU, and MMLU-Pro, we show that TCD, especially when paired with prompt engineering (PE) fixes, significantly restores performance degraded by input noise, yielding up to +39\% absolute gains for weaker models like Gemma3 1B. Penalty sweep analyses further reveal that TCD implicitly regularizes overconfident outputs, with different models requiring distinct penalty schedules to maximize resilience. Our findings establish TCD as a practical, model-agnostic approach for improving reasoning stability under real-world imperfections and pave the way for more reliable deployment of LLMs in safety-critical or user-facing applications.

[Arxiv](https://arxiv.org/abs/2506.09408)