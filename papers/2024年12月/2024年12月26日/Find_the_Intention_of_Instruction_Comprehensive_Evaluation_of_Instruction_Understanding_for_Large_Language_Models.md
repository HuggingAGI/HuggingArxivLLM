# 探寻指令真意：大型语言模型指令理解能力全面评估

发布时间：2024年12月26日

`LLM理论

**理由**：这篇论文主要关注的是大型语言模型（LLMs）的指令理解能力，并提出了一个新的基准（IoInst）来评估LLMs在指令理解上的表现。这涉及到对LLMs的理论理解和性能评估，因此属于“LLM理论”分类。` `人工智能`

> Find the Intention of Instruction: Comprehensive Evaluation of Instruction Understanding for Large Language Models

# 摘要

> 大型语言模型（LLMs）的一大亮点是它们能通过生成对指令的恰当响应与人类互动。这种指令跟随能力，不仅为LLMs在各领域的应用铺平了道路，还是评估其性能的重要指标。尽管已有众多评估基准，但它们大多只关注清晰连贯的指令。我们却发现，LLMs容易被指令格式的陈述带偏，从而忽视其指令理解能力。为此，我们推出了指令意图（IoInst）基准，旨在评估LLMs在不被无关指令干扰的情况下，保持专注并理解指令的能力。该基准的核心任务是找出能准确指导生成给定上下文的指令。研究发现，即便是最新推出的顶尖模型，在指令理解上仍有不足。此外，我们还对可能适用于IoInst的多种策略进行了深入分析。

> One of the key strengths of Large Language Models (LLMs) is their ability to interact with humans by generating appropriate responses to given instructions. This ability, known as instruction-following capability, has established a foundation for the use of LLMs across various fields and serves as a crucial metric for evaluating their performance. While numerous evaluation benchmarks have been developed, most focus solely on clear and coherent instructions. However, we have noted that LLMs can become easily distracted by instruction-formatted statements, which may lead to an oversight of their instruction comprehension skills. To address this issue, we introduce the Intention of Instruction (IoInst) benchmark. This benchmark evaluates LLMs' capacity to remain focused and understand instructions without being misled by extraneous instructions. The primary objective of this benchmark is to identify the appropriate instruction that accurately guides the generation of a given context. Our findings suggest that even recently introduced state-of-the-art models still lack instruction understanding capability. Along with the proposition of IoInst in this study, we also present broad analyses of the several strategies potentially applicable to IoInst.

[Arxiv](https://arxiv.org/abs/2412.19450)