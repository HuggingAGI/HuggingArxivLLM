# 面向多语言编程的混合语言专家架构

发布时间：2025年06月18日

`LLM应用` `软件开发`

> Mix-of-Language-Experts Architecture for Multilingual Programming

# 摘要

> 大型语言模型（LLMs）在代码理解、生成和翻译等任务中表现出色。然而，支持多语言编程时，现有方法面临效率与专业化的权衡：微调单一LLM虽经济但缺乏专业性，而为每种语言分别微调则成本高昂。本文提出MoLE（语言专家混合模型），一种创新架构，兼顾多语言编程的效率与专业化。MoLE由基础模型、共享LoRA模块及语言特定LoRA模块组成，微调过程中协同优化，实现跨语言知识共享与专业化。推理时，MoLE自动选择对应语言的LoRA模块。实验显示，MoLE在参数效率上优于单独训练方法，且在准确性上超越了单一共享LLM。


> Large language models (LLMs) have demonstrated impressive capabilities in aiding developers with tasks like code comprehension, generation, and translation. Supporting multilingual programming -- i.e., coding tasks across multiple programming languages -- typically requires either (1) finetuning a single LLM across all programming languages, which is cost-efficient but sacrifices language-specific specialization and performance, or (2) finetuning separate LLMs for each programming language, which allows for specialization but is computationally expensive and storage-intensive due to the duplication of parameters. This paper introduces MoLE (Mix-of-Language-Experts), a novel architecture that balances efficiency and specialization for multilingual programming. MoLE is composed of a base model, a shared LoRA (low-rank adaptation) module, and a collection of language-specific LoRA modules. These modules are jointly optimized during the finetuning process, enabling effective knowledge sharing and specialization across programming languages. During inference, MoLE automatically routes to the language-specific LoRA module corresponding to the programming language of the code token being generated. Our experiments demonstrate that MoLE achieves greater parameter efficiency compared to training separate language-specific LoRAs, while outperforming a single shared LLM finetuned for all programming languages in terms of accuracy.

[Arxiv](https://arxiv.org/abs/2506.18923)