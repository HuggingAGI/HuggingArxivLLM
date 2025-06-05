# 从真实到合成：生成数百万条多样化且复杂的用户指令，基于属性化的基础

发布时间：2025年06月04日

`LLM理论` `人工智能`

> From Real to Synthetic: Synthesizing Millions of Diversified and Complicated User Instructions with Attributed Grounding

# 摘要

> 在大规模语言模型（LLMs）的自动对齐中，多样化、复杂且大规模的指令数据至关重要。现有生成合成指令的方法要么受限于有限的来源基础，导致分布狭窄，要么依赖简单的扩展，无法在复杂性方面产生有意义的轨迹。与之不同，有助于高效对齐的指令通常基于认知见解，并以现实世界的应用场景为依据进行设计。本文中，我们通过归因化的方法来合成此类指令，具体包括：1) 一种自顶向下的归因过程，将精选的真实指令与具体用户场景相结合；2) 一种自底向上的综合过程，利用网络文档先生成情境，再生成有意义的指令。这一框架使我们能够大规模收获多样化且复杂的指令，充分利用广泛的网络文档资源。具体而言，我们构建了一个包含100万条指令的数据集，名为SynthQuestions，并证明基于此数据集训练的模型在多个常见基准测试中表现出领先性能，且随着更多网络语料的加入，性能提升持续显著。数据、模型和代码可在https://github.com/Ignoramus0817/SynthQuestions获取。

> The pursuit of diverse, complex, and large-scale instruction data is crucial for automatically aligning large language models (LLMs). While there are methods capable of generating synthetic instructions at scale, they either suffer from limited grounding sources, leading to a narrow distribution, or rely on trivial extensions that fail to produce meaningful trajectories in terms of complexity. In contrast, instructions that benefit efficient alignment are typically crafted with cognitive insights and grounded in real-world use cases. In this paper, we synthesize such instructions using attributed grounding, which involves 1) a top-down attribution process that grounds a selective set of real instructions to situated users, and 2) a bottom-up synthesis process that leverages web documents to first generate a situation, then a meaningful instruction. This framework allows us to harvest diverse and complex instructions at scale, utilizing the vast range of web documents. Specifically, we construct a dataset of 1 million instructions, called SynthQuestions, and demonstrate that models trained on it achieve leading performance on several common benchmarks, with improvements that continually scale with more web corpora. Data, models and codes will be available at https://github.com/Ignoramus0817/SynthQuestions.

[Arxiv](https://arxiv.org/abs/2506.03968)