# 利用推测性思维链提升大型语言模型的推理效率

发布时间：2025年04月26日

`LLM应用` `推理模型` `模型协同`

> Efficient Reasoning for LLMs through Speculative Chain-of-Thought

# 摘要

> 大型推理语言模型（如 OpenAI-o1 和 Deepseek-R1）因其卓越的任务解决能力而备受关注。然而，模型规模庞大和冗长的推理链导致推理成本高昂且响应延迟显著。现有高效推理方法主要通过减少模型参数或缩短推理链长度来优化性能。本文提出了一种全新的推理方法——Speculative Chain-of-Thought (SCoT)，通过大规模和小规模模型的协同工作，从全新角度加速推理过程，显著降低推理延迟。SCoT 利用轻量级草稿模型进行思维层面的草稿生成，随后借助目标模型对最优推理链进行筛选和修正。我们的思维行为对齐技术不仅提升了草稿生成效率，还确保了复杂问题的预测准确性。实验结果表明，在 GSM8K、MATH、GaoKao、CollegeMath 和 Olympiad 数据集上，SCoT 将 Deepseek-R1-Distill-Qwen-32B 的推理延迟降低了 48\% 到 66\%，同时保持了接近目标模型的性能水平。我们的代码已开源，地址为 https://github.com/Jikai0Wang/Speculative_CoT。


> Large reasoning language models such as OpenAI-o1 and Deepseek-R1 have recently attracted widespread attention due to their impressive task-solving abilities. However, the enormous model size and the generation of lengthy thought chains introduce significant reasoning costs and response latency. Existing methods for efficient reasoning mainly focus on reducing the number of model parameters or shortening the chain-of-thought length. In this paper, we introduce Speculative Chain-of-Thought (SCoT), which reduces reasoning latency from another perspective by accelerated average reasoning speed through large and small model collaboration. SCoT conducts thought-level drafting using a lightweight draft model. Then it selects the best CoT draft and corrects the error cases with the target model. The proposed thinking behavior alignment improves the efficiency of drafting and the draft selection strategy maintains the prediction accuracy for complex problems. Experimental results on GSM8K, MATH, GaoKao, CollegeMath and Olympiad datasets show that SCoT reduces reasoning latency by 48\%$\sim$66\% for Deepseek-R1-Distill-Qwen-32B while achieving near-target-model-level performance. Our code is available at https://github.com/Jikai0Wang/Speculative_CoT.

[Arxiv](https://arxiv.org/abs/2504.19095)