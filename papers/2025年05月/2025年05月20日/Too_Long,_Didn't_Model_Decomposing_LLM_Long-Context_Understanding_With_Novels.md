# 长篇小说揭示LLM长上下文理解机制：深入拆解模型的长文本处理能力

发布时间：2025年05月20日

`LLM应用`

> Too Long, Didn't Model: Decomposing LLM Long-Context Understanding With Novels

# 摘要

> 尽管大型语言模型（LLMs）的上下文长度已扩展至数百万token，但超越简单的“大海捞针”方法来评估其有效性仍具挑战。我们认为小说是研究复杂结构和长距离语义依赖（常超过128k tokens）的理想案例。受计算小说分析的启发，我们推出了“Too Long, Didn't Model (TLDM)”基准测试，旨在评估模型在情节摘要、故事情节配置和叙述时间流逝方面的表现。研究发现，所有测试的前沿LLMs在处理超过64k tokens的内容时，均无法保持稳定的理解能力。这意味着语言模型开发者在评估复杂长上下文场景下的性能时，需突破传统的“迷失在中间”基准测试。为了推动进一步研究，我们发布了TLDM基准测试，并附带参考代码和数据集。

> Although the context length of large language models (LLMs) has increased to millions of tokens, evaluating their effectiveness beyond needle-in-a-haystack approaches has proven difficult. We argue that novels provide a case study of subtle, complicated structure and long-range semantic dependencies often over 128k tokens in length. Inspired by work on computational novel analysis, we release the Too Long, Didn't Model (TLDM) benchmark, which tests a model's ability to report plot summary, storyworld configuration, and elapsed narrative time. We find that none of seven tested frontier LLMs retain stable understanding beyond 64k tokens. Our results suggest language model developers must look beyond "lost in the middle" benchmarks when evaluating model performance in complex long-context scenarios. To aid in further development we release the TLDM benchmark together with reference code and data.

[Arxiv](https://arxiv.org/abs/2505.14925)