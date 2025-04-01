# 基于Text-Debiased Hint-GRPO的MLLM推理增强方法

发布时间：2025年03月31日

`LLM应用` `多模态`

> Boosting MLLM Reasoning with Text-Debiased Hint-GRPO

# 摘要

> MLLM推理因其强大的问题解决能力受到广泛关注。当前推理方法主要分为两类：监督中间推理步骤的PRM，以及监督最终结果的ORM。近期，DeepSeek-R1挑战了传统观点，通过ORM方法（即GRPO）展现了强大的泛化性能。然而，现有MLLM的GRPO算法在处理复杂多模态推理任务时仍存在困难。本研究揭示了阻碍GRPO在MLLM上性能的两大问题：低数据利用率和文本偏见。针对这些问题，我们提出了Hint-GRPO方法，通过自适应地为不同难度样本提供提示来提升数据利用率，并引入了文本偏见校准机制，通过图像条件校准标记预测对数概率来缓解文本偏见。实验结果表明，我们的方法显著提升了MLLM的推理能力，展现出超越现有方法的优越性能。代码可在https://github.com/hqhQAQ/Hint-GRPO获取。

> MLLM reasoning has drawn widespread research for its excellent problem-solving capability. Current reasoning methods fall into two types: PRM, which supervises the intermediate reasoning steps, and ORM, which supervises the final results. Recently, DeepSeek-R1 has challenged the traditional view that PRM outperforms ORM, which demonstrates strong generalization performance using an ORM method (i.e., GRPO). However, current MLLM's GRPO algorithms still struggle to handle challenging and complex multimodal reasoning tasks (e.g., mathematical reasoning). In this work, we reveal two problems that impede the performance of GRPO on the MLLM: Low data utilization and Text-bias. Low data utilization refers to that GRPO cannot acquire positive rewards to update the MLLM on difficult samples, and text-bias is a phenomenon that the MLLM bypasses image condition and solely relies on text condition for generation after GRPO training. To tackle these problems, this work proposes Hint-GRPO that improves data utilization by adaptively providing hints for samples of varying difficulty, and text-bias calibration that mitigates text-bias by calibrating the token prediction logits with image condition in test-time. Experiment results on three base MLLMs across eleven datasets demonstrate that our proposed methods advance the reasoning capability of original MLLM by a large margin, exhibiting superior performance to existing MLLM reasoning methods. Our code is available at https://github.com/hqhQAQ/Hint-GRPO.

[Arxiv](https://arxiv.org/abs/2503.23905)