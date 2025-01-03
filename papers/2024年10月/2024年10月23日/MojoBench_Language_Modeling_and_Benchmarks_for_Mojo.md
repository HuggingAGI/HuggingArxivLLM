# MojoBench: Mojo 的语言建模与基准测试

发布时间：2024年10月23日

`LLM应用

**解释**：这篇论文主要讨论了Mojo编程语言在代码生成领域的应用，特别是通过构建MojoBench框架和Mojo-Coder模型来提升代码生成LLM的性能。论文的核心在于如何利用LLM来生成Mojo代码，并探讨了LLM在新兴编程语言中的表现和适应性。因此，这篇论文属于**LLM应用**的范畴。` `编程语言` `人工智能`

> MojoBench: Language Modeling and Benchmarks for Mojo

# 摘要

> Modular新推出的Mojo编程语言（PL）因其宣称比Python有显著的速度提升，在科学界备受瞩目。尽管代码大型语言模型（LLMs）在各种PL中取得了进展，但Mojo在这一领域仍未被探索。为此，我们推出了MojoBench，首个专为Mojo代码生成设计的框架。MojoBench包含HumanEval-Mojo，一个用于评估Mojo代码LLMs的基准数据集，以及Mojo-Coder，首个为Mojo代码生成预训练和微调的LLM，支持5种自然语言（NLs）的指令。结果显示，Mojo-Coder在性能上比GPT-4o和Claude-3.5-Sonnet等领先模型提升了30-35%。此外，我们还深入探讨了LLM在代表性不足和未见过的PL中的表现，提出了增强模型适应性的潜在策略。MojoBench为我们理解新兴编程范式中LLM的能力和局限性提供了宝贵见解，推动了更健壮的代码生成系统的发展。

> The recently introduced Mojo programming language (PL) by Modular, has received significant attention in the scientific community due to its claimed significant speed boost over Python. Despite advancements in code Large Language Models (LLMs) across various PLs, Mojo remains unexplored in this context. To address this gap, we introduce MojoBench, the first framework for Mojo code generation. MojoBench includes HumanEval-Mojo, a benchmark dataset designed for evaluating code LLMs on Mojo, and Mojo-Coder, the first LLM pretrained and finetuned for Mojo code generation, which supports instructions in 5 natural languages (NLs). Our results show that Mojo-Coder achieves a 30-35% performance improvement over leading models like GPT-4o and Claude-3.5-Sonnet. Furthermore, we provide insights into LLM behavior with underrepresented and unseen PLs, offering potential strategies for enhancing model adaptability. MojoBench contributes to our understanding of LLM capabilities and limitations in emerging programming paradigms fostering more robust code generation systems.

[Arxiv](https://arxiv.org/abs/2410.17736)