# 重新审视大型语言模型的组合泛化能力：结合指令遵循能力

发布时间：2025年06月18日

`LLM应用` `常识推理` `指令遵循`

> Revisiting Compositional Generalization Capability of Large Language Models Considering Instruction Following Ability

# 摘要

> 在生成型常识推理任务（如CommonGen）中，LLMs擅长生成包含所有给定概念的句子。然而，当涉及指令遵循能力时，若提示指定了概念顺序，LLMs需严格按此顺序生成句子。为此，我们提出了Ordered CommonGen，这是一个专门设计的基准测试，旨在评估LLMs的组合泛化能力和指令遵循能力。该基准通过测量有序覆盖率，判断概念是否按指定顺序生成，从而实现对两种能力的同步评估。我们对36个LLMs进行了全面分析，发现尽管LLMs通常能准确理解指令意图，但对特定概念顺序模式的偏好常导致输出多样性不足或结果重复，即使改变顺序也不例外。值得注意的是，即使是表现最好的LLM，其有序覆盖率也只有约75%，这表明在指令遵循和组合泛化能力方面仍有提升空间。

> In generative commonsense reasoning tasks such as CommonGen, generative large language models (LLMs) compose sentences that include all given concepts. However, when focusing on instruction-following capabilities, if a prompt specifies a concept order, LLMs must generate sentences that adhere to the specified order. To address this, we propose Ordered CommonGen, a benchmark designed to evaluate the compositional generalization and instruction-following abilities of LLMs. This benchmark measures ordered coverage to assess whether concepts are generated in the specified order, enabling a simultaneous evaluation of both abilities. We conducted a comprehensive analysis using 36 LLMs and found that, while LLMs generally understand the intent of instructions, biases toward specific concept order patterns often lead to low-diversity outputs or identical results even when the concept order is altered. Moreover, even the most instruction-compliant LLM achieved only about 75% ordered coverage, highlighting the need for improvements in both instruction-following and compositional generalization capabilities.

[Arxiv](https://arxiv.org/abs/2506.15629)