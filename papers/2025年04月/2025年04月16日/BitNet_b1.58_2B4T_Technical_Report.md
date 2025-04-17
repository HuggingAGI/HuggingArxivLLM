# BitNet b1.58 2B4T 技术报告

发布时间：2025年04月16日

`LLM应用` `人工智能`

> BitNet b1.58 2B4T Technical Report

# 摘要

> 我们推出BitNet b1.58 2B4T——首个开源的、原生1位量化、20亿参数规模的大语言模型（LLM）。该模型基于4万亿标记的语料库训练而成，并在语言理解、数学推理、编程能力和对话能力等多方面基准测试中表现优异。实验结果表明，BitNet b1.58 2B4T不仅性能可与同规模的领先开源全精度LLM比肩，还在计算效率上展现出显著优势，包括更低的内存占用、能耗和解码延迟。为推动进一步研究与应用，我们已通过Hugging Face平台开源了模型权重，并提供了适用于GPU和CPU架构的推理实现。

> We introduce BitNet b1.58 2B4T, the first open-source, native 1-bit Large Language Model (LLM) at the 2-billion parameter scale. Trained on a corpus of 4 trillion tokens, the model has been rigorously evaluated across benchmarks covering language understanding, mathematical reasoning, coding proficiency, and conversational ability. Our results demonstrate that BitNet b1.58 2B4T achieves performance on par with leading open-weight, full-precision LLMs of similar size, while offering significant advantages in computational efficiency, including substantially reduced memory footprint, energy consumption, and decoding latency. To facilitate further research and adoption, the model weights are released via Hugging Face along with open-source inference implementations for both GPU and CPU architectures.

[Arxiv](https://arxiv.org/abs/2504.12285)