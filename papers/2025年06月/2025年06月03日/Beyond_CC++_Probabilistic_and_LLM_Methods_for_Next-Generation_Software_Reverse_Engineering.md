# # 超越C/C++：探索下一代软件逆向工程，基于概率与大语言模型的方法

发布时间：2025年06月03日

`LLM应用` `逆向工程` `软件开发`

> Beyond C/C++: Probabilistic and LLM Methods for Next-Generation Software Reverse Engineering

# 摘要

> 本提案探讨了逆向工程现代软件二进制文件的挑战，尤其是针对Rust、Go和Mojo等新系统编程语言。传统逆向工程技术主要面向C和C++，依赖过时的启发式规则，难以充分利用二进制中的语义信息。再加上现有数据驱动方法易产生幻觉，结果不准确。为此，我们提出一种结合概率二进制分析与微调LLM的新方法。该方法系统建模逆向工程中的不确定性，提升对不完整或模糊信息的推理能力。通过引入LLMs，突破传统启发式限制，使分析更富创造性和上下文感知，尤其适用于多种语言编译的二进制文件。这种方法不仅提升了逆向工程的稳健性和准确性，还提供了适应快速演变的软件开发环境的可扩展解决方案。

> This proposal discusses the growing challenges in reverse engineering modern software binaries, particularly those compiled from newer system programming languages such as Rust, Go, and Mojo. Traditional reverse engineering techniques, developed with a focus on C and C++, fall short when applied to these newer languages due to their reliance on outdated heuristics and failure to fully utilize the rich semantic information embedded in binary programs. These challenges are exacerbated by the limitations of current data-driven methods, which are susceptible to generating inaccurate results, commonly referred to as hallucinations. To overcome these limitations, we propose a novel approach that integrates probabilistic binary analysis with fine-tuned large language models (LLMs). Our method systematically models the uncertainties inherent in reverse engineering, enabling more accurate reasoning about incomplete or ambiguous information. By incorporating LLMs, we extend the analysis beyond traditional heuristics, allowing for more creative and context-aware inferences, particularly for binaries from diverse programming languages. This hybrid approach not only enhances the robustness and accuracy of reverse engineering efforts but also offers a scalable solution adaptable to the rapidly evolving landscape of software development.

[Arxiv](https://arxiv.org/abs/2506.03504)