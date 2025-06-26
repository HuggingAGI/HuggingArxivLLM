# # 反向翻译蒸馏：工具知识注入语言模型

发布时间：2025年06月23日

`Agent` `AI教育`

> Distilling Tool Knowledge into Language Models via Back-Translated Traces

# 摘要

> 大型语言模型（LLMs）在处理需要精确计算或多步代数推理的数学问题时往往表现欠佳。工具集成推理（TIR）通过借助代码解释器等外部工具来确保结果正确性，但同时也带来了推理时的依赖性问题，影响了其扩展性和实际部署。本研究提出了一种全新的解决方案，通过纯自然语言的方式将工具知识注入到LLMs中。我们首先构建了一个Solver Agent，它通过规划、符号工具调用和反思性推理的交替进行来解决数学问题。随后，我们利用一个由多个LLM驱动代理组成的逆向翻译流水线，将这些交替的TIR轨迹转换为自然语言推理轨迹。Translator Agent负责为每个工具调用生成解释，而Rephrase Agent则将这些解释整合成一个流畅且全局连贯的叙述。实验结果表明，通过在这些合成轨迹上微调一个小型开源模型，可以使模型同时掌握工具知识和结构化推理模式，从而在无需推理时依赖工具的情况下，显著提升其在竞赛级别数学基准测试中的表现。

> Large language models (LLMs) often struggle with mathematical problems that require exact computation or multi-step algebraic reasoning. Tool-integrated reasoning (TIR) offers a promising solution by leveraging external tools such as code interpreters to ensure correctness, but it introduces inference-time dependencies that hinder scalability and deployment. In this work, we propose a new paradigm for distilling tool knowledge into LLMs purely through natural language. We first construct a Solver Agent that solves math problems by interleaving planning, symbolic tool calls, and reflective reasoning. Then, using a back-translation pipeline powered by multiple LLM-based agents, we convert interleaved TIR traces into natural language reasoning traces. A Translator Agent generates explanations for individual tool calls, while a Rephrase Agent merges them into a fluent and globally coherent narrative. Empirically, we show that fine-tuning a small open-source model on these synthesized traces enables it to internalize both tool knowledge and structured reasoning patterns, yielding gains on competition-level math benchmarks without requiring tool access at inference.

[Arxiv](https://arxiv.org/abs/2506.19171)