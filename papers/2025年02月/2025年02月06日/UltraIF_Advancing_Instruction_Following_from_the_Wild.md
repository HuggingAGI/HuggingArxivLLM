# UltraIF: 从实际场景中提升指令跟随能力

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了如何通过UltraIF方法来驯服大型语言模型（LLMs）以处理复杂指令，并展示了该方法在多个基准测试中的成功应用。论文的核心在于如何改进LLMs的指令跟随能力，这属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `人工智能`

> UltraIF: Advancing Instruction Following from the Wild

# 摘要

> # 摘要
指令跟随让现代大型语言模型（LLMs）成为得力助手，但如何驯服LLMs处理复杂指令仍是个谜，尤其是开源社区与领先公司训练的模型之间存在巨大差距。为此，我们提出了UltraIF，一种简单且可扩展的方法，利用开源数据构建能处理复杂指令的LLMs。UltraIF首先将用户提示拆解为简单查询、约束及对应的评估问题，随后训练UltraComposer将约束提示与评估问题组合。这一提示组合器不仅能合成复杂指令，还能通过评估问题过滤响应。实验中，我们首次成功将LLaMA-3.1-8B-Base与其指令版本在5个指令跟随基准上对齐，且无需任何基准信息，仅用8B模型作为生成器和评估器。对齐后的模型在其他基准上也表现出色。此外，UltraIF还能通过自我对齐进一步提升LLaMA-3.1-8B-Instruct，展现了该方法的广泛应用潜力。代码已开源：https://github.com/kkk-an/UltraIF。

> Instruction-following made modern large language models (LLMs) helpful assistants. However, the key to taming LLMs on complex instructions remains mysterious, for that there are huge gaps between models trained by open-source community and those trained by leading companies. To bridge the gap, we propose a simple and scalable approach UltraIF for building LLMs that can follow complex instructions with open-source data. UltraIF first decomposes real-world user prompts into simpler queries, constraints, and corresponding evaluation questions for the constraints. Then, we train an UltraComposer to compose constraint-associated prompts with evaluation questions. This prompt composer allows us to synthesize complicated instructions as well as filter responses with evaluation questions. In our experiment, for the first time, we successfully align LLaMA-3.1-8B-Base to catch up with its instruct version on 5 instruction-following benchmarks without any benchmark information, using only 8B model as response generator and evaluator. The aligned model also achieved competitive scores on other benchmarks. Moreover, we also show that UltraIF could further improve LLaMA-3.1-8B-Instruct through self-alignment, motivating broader use cases for the method. Our code will be available at https://github.com/kkk-an/UltraIF.

[Arxiv](https://arxiv.org/abs/2502.04153)