# 面向 Verilog 的推测性解码方法：速度与质量二者兼得

发布时间：2025年03月18日

`LLM应用` `代码生成`

> Speculative Decoding for Verilog: Speed and Quality, All in One

# 摘要

> 大型语言模型 (LLMs) 的飞速发展彻底改变了跨多种编程语言的代码生成领域。然而，编程语言的独特性，尤其是像 Verilog 这样具有特定语法且在训练数据中代表性较低的语言，给传统分词和解码方法带来了巨大挑战。本文提出了一种针对 Verilog 代码生成的推测式解码新应用，实验证明它能同时提升推理速度和输出质量，实现速度与质量的完美结合。与传统 LLM 分词方案不同，我们的方法将解码停止点与语法关键标记对齐，使模型更易于学习标记分布。这一改进不仅解决了传统分词的固有问题，还显著提升了模型捕捉 Verilog 逻辑结构的能力。实验结果显示，相比传统训练策略，我们的方法在 Verilog 代码生成中实现了最高 5.05 倍的速度提升，并将 RTLLM 上的 pass@10 功能准确性提高了 17.19%。这些结果表明，推测式解码是弥合专业编程语言代码生成质量差距的极具潜力的方法。

> The rapid advancement of large language models (LLMs) has revolutionized code generation tasks across various programming languages. However, the unique characteristics of programming languages, particularly those like Verilog with specific syntax and lower representation in training datasets, pose significant challenges for conventional tokenization and decoding approaches. In this paper, we introduce a novel application of speculative decoding for Verilog code generation, showing that it can improve both inference speed and output quality, effectively achieving speed and quality all in one. Unlike standard LLM tokenization schemes, which often fragment meaningful code structures, our approach aligns decoding stops with syntactically significant tokens, making it easier for models to learn the token distribution. This refinement addresses inherent tokenization issues and enhances the model's ability to capture Verilog's logical constructs more effectively. Our experimental results show that our method achieves up to a 5.05x speedup in Verilog code generation and increases pass@10 functional accuracy on RTLLM by up to 17.19% compared to conventional training strategies. These findings highlight speculative decoding as a promising approach to bridge the quality gap in code generation for specialized programming languages.

[Arxiv](https://arxiv.org/abs/2503.14153)