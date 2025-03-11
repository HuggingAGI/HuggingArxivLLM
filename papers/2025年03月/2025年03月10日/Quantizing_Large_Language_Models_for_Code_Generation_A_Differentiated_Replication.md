# 量化大型语言模型用于代码生成：一种有区分度的复制方法

发布时间：2025年03月10日

`LLM应用

摘要讨论了大型语言模型在代码生成中的应用，特别是量化技术的应用以减少内存占用，同时保持性能。这属于LLM的应用层面研究，因此归类为LLM应用。` `软件工程` `代码生成`

> Quantizing Large Language Models for Code Generation: A Differentiated Replication

# 摘要

> 大型语言模型（LLMs）在代码生成领域表现卓越，尤其擅长将自然语言描述的需求自动转化为代码实现。通常来说，模型参数规模越大，LLM 的代码实现能力越强。然而，部署基于 LLM 的代码生成器时，更大的模型会带来内存占用和碳排放方面的挑战。此前，Wei 等人提出了一种通过量化技术减少基于 LLM 的代码生成器内存占用而不显著影响性能的方法。他们研究了具有多达 160 亿参数的 LLM，将精度从 32 位浮点量化到 8 位整数，并发现这种量化对代码生成性能影响有限。鉴于 LLM 能力和量化技术的快速发展，本研究提出了一种与 Wei 等人工作有所区别的复现研究，主要考虑以下几点：(i) 更新、更大规模的与代码相关的 LLM，参数规模高达 340 亿；(ii) 最新的模型量化技术进展，允许将压缩推向每模型参数 2 位的极端量化水平；(iii) 不同类型的校准数据集，包括专门针对代码的，以指导量化过程。我们的实证评估表明，LLM 量化的最新前沿是 4 位精度，与原始模型相比，平均内存占用减少了 70%，而性能未见显著下降。此外，当量化变得更加极端（3 位和 2 位）时，专门针对代码的校准数据集有助于限制性能损失。

> Large Language Models (LLMs) have shown an impressive capability in code generation and, specifically, to automatically implement requirements described in natural language. The LLM effectiveness generally increases with its size: The higher the number of LLM's trainable parameters the better its ability to implement code. However, when it comes to deploying LLM-based code generators, larger LLMs pose significant challenges related to their memory (and, consequently, carbon) footprint. A previous work by Wei et al. proposed to leverage quantization techniques to reduce the memory footprint of LLM-based code generators without substantially degrading their effectiveness. In short, they studied LLMs featuring up to 16B parameters, quantizing their precision from floating point 32 bits down to int 8 bits and showing their limited impact on code generation performance. Given the fast pace at which LLM capabilities and quantization techniques are evolving, in this work we present a differentiated replication of the work by Wei et al. in which we consider (i) on the one side, more recent and larger code-related LLMs, of up to 34B parameters; (ii) the latest advancements in model quantization techniques, which allow pushing the compression to the extreme quantization level of 2 bits per model parameter and; (iii) different types of calibration datasets to guide the quantization process, including code-specific ones. Our empirical evaluation reveals that the new frontier for LLM quantization is 4-bit precision, resulting in an average memory footprint reduction of 70% compared to the original model without observing any significant decrease in performance. Additionally, when the quantization becomes even more extreme (3 and 2 bits), a code-specific calibration dataset helps to limit the loss of performance.

[Arxiv](https://arxiv.org/abs/2503.07103)