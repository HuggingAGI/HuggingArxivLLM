# 通过摘要分析LLM在混合上下文中的幻觉评估

发布时间：2025年03月03日

`LLM应用` `文本摘要`

> Evaluating LLMs' Assessment of Mixed-Context Hallucination Through the Lens of Summarization

# 摘要

> 随着大语言模型（LLMs）的快速发展，将其作为评估者已成为文本质量评估（包括幻觉检测）中广受欢迎的方法。然而，现有研究主要聚焦于单一上下文评估（如话语忠实性或事实准确性），而现实中的幻觉往往涉及混合上下文，这一方面尚未得到充分关注。本研究以文本摘要为典型任务，全面评估LLMs在检测混合上下文幻觉方面的能力，特别是区分事实性与非事实性幻觉的能力。通过在不同规模的生成模型和检索增强模型上进行广泛实验，我们发现：(1) LLMs的内在知识引入了幻觉评估中的固有偏见；(2) 这种偏见对事实性幻觉的检测影响尤为显著，造成了明显的性能瓶颈；(3) 根本挑战在于如何有效利用知识，平衡LLMs的内在知识与外部上下文，以实现准确的混合上下文幻觉评估。

> With the rapid development of large language models (LLMs), LLM-as-a-judge has emerged as a widely adopted approach for text quality evaluation, including hallucination evaluation. While previous studies have focused exclusively on single-context evaluation (e.g., discourse faithfulness or world factuality), real-world hallucinations typically involve mixed contexts, which remains inadequately evaluated. In this study, we use summarization as a representative task to comprehensively evaluate LLMs' capability in detecting mixed-context hallucinations, specifically distinguishing between factual and non-factual hallucinations. Through extensive experiments across direct generation and retrieval-based models of varying scales, our main observations are: (1) LLMs' intrinsic knowledge introduces inherent biases in hallucination evaluation; (2) These biases particularly impact the detection of factual hallucinations, yielding a significant performance bottleneck; (3) The fundamental challenge lies in effective knowledge utilization, balancing between LLMs' intrinsic knowledge and external context for accurate mixed-context hallucination evaluation.

[Arxiv](https://arxiv.org/abs/2503.01670)