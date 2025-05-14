# FalseReject：通过结构化推理优化LLM上下文安全并降低过度拒绝的实用资源

发布时间：2025年05月12日

`LLM应用` `模型安全` `风险管理`

> FalseReject: A Resource for Improving Contextual Safety and Mitigating Over-Refusals in LLMs via Structured Reasoning

# 摘要

> 大型语言模型（LLMs）中的安全对齐方法常导致对无害查询的过度拒绝，这极大削弱了其在敏感场景中的实用性。为应对这一挑战，我们推出了FalseReject——一个包含16k看似有毒查询的综合资源，涵盖44个安全相关类别的结构化响应。我们提出了一种基于图的对抗多智能体交互框架，用于生成多样且复杂的提示，并通过明确推理结构化响应，帮助模型精准区分安全与不安全上下文。FalseReject为标准指令微调模型和推理导向模型提供了定制化训练数据集，并包含一个由人工标注的基准测试集。我们在29个最先进的（SOTA）LLMs上进行了广泛基准测试，发现过度拒绝问题依然存在。实证结果表明，使用FalseReject进行监督微调可显著减少不必要的拒绝，同时保持整体安全性和通用语言能力。

> Safety alignment approaches in large language models (LLMs) often lead to the over-refusal of benign queries, significantly diminishing their utility in sensitive scenarios. To address this challenge, we introduce FalseReject, a comprehensive resource containing 16k seemingly toxic queries accompanied by structured responses across 44 safety-related categories. We propose a graph-informed adversarial multi-agent interaction framework to generate diverse and complex prompts, while structuring responses with explicit reasoning to aid models in accurately distinguishing safe from unsafe contexts. FalseReject includes training datasets tailored for both standard instruction-tuned models and reasoning-oriented models, as well as a human-annotated benchmark test set. Our extensive benchmarking on 29 state-of-the-art (SOTA) LLMs reveals persistent over-refusal challenges. Empirical results demonstrate that supervised finetuning with FalseReject substantially reduces unnecessary refusals without compromising overall safety or general language capabilities.

[Arxiv](https://arxiv.org/abs/2505.08054)