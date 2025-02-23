# RAG 在处理长上下文时真的表现不佳吗？

发布时间：2025年02月17日

`RAG` `长上下文处理`

> Does RAG Really Perform Bad For Long-Context Processing?

# 摘要

> 处理长上下文的高效性对大型语言模型（LLMs）提出了严峻的挑战。最近，检索增强生成（RAG）作为一种有前景的策略，使得LLMs能够对长上下文进行选择性利用，从而实现高效计算。然而，现有的RAG方法由于检索不准确和上下文碎片化等固有局限性，相较于其他长上下文处理方法仍显不足。为应对这些挑战，我们提出了RetroLM，一种用于长上下文处理的新型RAG框架。与传统方法不同，RetroLM采用了KV级别检索增强，即将LLMs的KV缓存划分为连续页面，并从中检索最关键的部分进行高效计算。这种方法增强了对检索不准确的鲁棒性，促进了对碎片化上下文的有效利用，并减少了重复计算的成本。在此框架基础上，我们进一步开发了一种专用检索器以实现对关键页面的精准检索，并进行了无监督的后训练以优化模型利用检索信息的能力。我们通过LongBench、InfiniteBench和RULER等多种基准测试进行了全面评估，结果显示RetroLM在需要密集推理或极长上下文理解的任务中，显著超越现有的长上下文LLMs和高效长上下文处理方法。

> The efficient processing of long context poses a serious challenge for large language models (LLMs). Recently, retrieval-augmented generation (RAG) has emerged as a promising strategy for this problem, as it enables LLMs to make selective use of the long context for efficient computation. However, existing RAG approaches lag behind other long-context processing methods due to inherent limitations on inaccurate retrieval and fragmented contexts. To address these challenges, we introduce RetroLM, a novel RAG framework for long-context processing. Unlike traditional methods, RetroLM employs KV-level retrieval augmentation, where it partitions the LLM's KV cache into contiguous pages and retrieves the most crucial ones for efficient computation. This approach enhances robustness to retrieval inaccuracy, facilitates effective utilization of fragmented contexts, and saves the cost from repeated computation. Building on this framework, we further develop a specialized retriever for precise retrieval of critical pages and conduct unsupervised post-training to optimize the model's ability to leverage retrieved information. We conduct comprehensive evaluations with a variety of benchmarks, including LongBench, InfiniteBench, and RULER, where RetroLM significantly outperforms existing long-context LLMs and efficient long-context processing methods, particularly in tasks requiring intensive reasoning or extremely long-context comprehension.

[Arxiv](https://arxiv.org/abs/2502.11444)