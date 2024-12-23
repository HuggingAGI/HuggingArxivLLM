# TelcoLM：致力于为电信领域收集数据、开展适配工作并对语言模型进行基准测试

发布时间：2024年12月20日

`LLM应用` `语言模型`

> TelcoLM: collecting data, adapting, and benchmarking language models for the telecommunication domain

# 摘要

> 尽管在众多任务中表现出众，但大型语言模型（LLMs）在应对高技术领域时仍不够精准。特别是电信（telco）领域，因其大量的词汇、语义和概念特性而极具挑战性。不过，该领域存在诸多与工业需求直接挂钩的宝贵用例。所以，此文探讨了如何让LLMs适配电信领域。文中讲述了我们为（i）收集大量特定领域的数据语料库（8亿个标记，8万个指令），（ii）运用多种方法进行适配，以及（iii）在需要广泛电信知识的下游任务中与更大型的通用模型进行基准测试所付出的努力。我们在Llama-2-7b上的实验表明，领域适配模型能够挑战大型通用模型。同时也表明，适配可仅局限于独特的指令调整步骤，无需事先对原始文本进行任何微调。

> Despite outstanding processes in many tasks, Large Language Models (LLMs) still lack accuracy when dealing with highly technical domains. Especially, telecommunications (telco) is a particularly challenging domain due the large amount of lexical, semantic and conceptual peculiarities. Yet, this domain holds many valuable use cases, directly linked to industrial needs. Hence, this paper studies how LLMs can be adapted to the telco domain. It reports our effort to (i) collect a massive corpus of domain-specific data (800M tokens, 80K instructions), (ii) perform adaptation using various methodologies, and (iii) benchmark them against larger generalist models in downstream tasks that require extensive knowledge of telecommunications. Our experiments on Llama-2-7b show that domain-adapted models can challenge the large generalist models. They also suggest that adaptation can be restricted to a unique instruction-tuning step, dicarding the need for any fine-tuning on raw texts beforehand.

[Arxiv](https://arxiv.org/abs/2412.15891)