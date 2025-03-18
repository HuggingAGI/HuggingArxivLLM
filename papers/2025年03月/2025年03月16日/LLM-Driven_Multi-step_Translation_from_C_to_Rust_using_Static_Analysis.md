# 基于大型语言模型的多步C到Rust翻译，通过静态分析实现。

发布时间：2025年03月16日

`LLM应用` `编程语言` `人工智能`

> LLM-Driven Multi-step Translation from C to Rust using Static Analysis

# 摘要

> 将C代码翻译为Rust代码可以在保持高性能的同时显著提升内存安全性。然而，手动翻译不仅繁琐易错，还常生成不符合Rust语言习惯的代码。大型语言模型（LLMs）虽然能生成符合习惯的翻译，但无法保证正确性，因为它们无法完全捕捉源语言和目标语言之间的语义差异。为了解决这一问题，我们提出了SACTOR——一种基于LLM的C到Rust零样本翻译工具。SACTOR采用两步翻译方法：首先进行“不符合习惯”的翻译，将C代码转换为Rust代码并保留语义；然后进行“符合习惯”的优化，使代码遵循Rust的语义标准。SACTOR通过分析源C程序的静态信息来应对指针语义和依赖项解析等挑战。为了验证每一步翻译结果的正确性，我们通过外函数接口进行端到端测试，将翻译后的代码段嵌入到原代码中。我们对来自两个数据集的200个程序以及两个案例研究进行了翻译评估，并比较了GPT-4o、Claude 3.5 Sonnet、Gemini 2.0 Flash、Llama 3.3 70B和DeepSeek-R1在SACTOR中的性能。实验结果表明，SACTOR在正确性和符合习惯性方面表现优异：最佳模型（DeepSeek-R1）达到了93%的符合习惯性，而（GPT-4o、Claude 3.5、DeepSeek-R1）分别在各自数据集中达到了84%的正确性。此外，SACTOR生成的翻译相比现有方法更加自然且符合Rust规范。

> Translating software written in legacy languages to modern languages, such as C to Rust, has significant benefits in improving memory safety while maintaining high performance. However, manual translation is cumbersome, error-prone, and produces unidiomatic code. Large language models (LLMs) have demonstrated promise in producing idiomatic translations, but offer no correctness guarantees as they lack the ability to capture all the semantics differences between the source and target languages. To resolve this issue, we propose SACTOR, an LLM-driven C-to-Rust zero-shot translation tool using a two-step translation methodology: an "unidiomatic" step to translate C into Rust while preserving semantics, and an "idiomatic" step to refine the code to follow Rust's semantic standards. SACTOR utilizes information provided by static analysis of the source C program to address challenges such as pointer semantics and dependency resolution. To validate the correctness of the translated result from each step, we use end-to-end testing via the foreign function interface to embed our translated code segment into the original code. We evaluate the translation of 200 programs from two datasets and two case studies, comparing the performance of GPT-4o, Claude 3.5 Sonnet, Gemini 2.0 Flash, Llama 3.3 70B and DeepSeek-R1 in SACTOR. Our results demonstrate that SACTOR achieves high correctness and improved idiomaticity, with the best-performing model (DeepSeek-R1) reaching 93% and (GPT-4o, Claude 3.5, DeepSeek-R1) reaching 84% correctness (on each dataset, respectively), while producing more natural and Rust-compliant translations compared to existing methods.

[Arxiv](https://arxiv.org/abs/2503.12511)