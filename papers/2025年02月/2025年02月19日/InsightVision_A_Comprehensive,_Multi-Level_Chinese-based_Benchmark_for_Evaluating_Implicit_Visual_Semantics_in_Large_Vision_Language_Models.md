# InsightVision：综合性多层级中文评测基准，专为大型视觉语言模型隐式视觉语义评估而设计。

发布时间：2025年02月19日

`LLM应用` `图像理解`

> InsightVision: A Comprehensive, Multi-Level Chinese-based Benchmark for Evaluating Implicit Visual Semantics in Large Vision Language Models

# 摘要

> 在多模态语言模型的快速发展中，如何准确理解图像中通过视觉线索传达的微妙含义（如讽刺、侮辱或批评）仍然是一个重大挑战。现有的评估基准主要集中在直接任务，如图像描述，或局限于对幽默或讽刺等狭窄类别的深度语义理解。为了解决这一空白，我们首次提出了一项全面的、多层级的中文基准测试，专门用于评估对图像中隐含意义的理解能力。该基准测试系统地分为四个子任务：表面内容理解、象征意义解读、背景知识理解以及隐含意义理解。我们还提出了一种创新的半自动数据集构建方法，并遵循既定的构建协议。通过这一基准测试，我们评估了15个开源的大视觉语言模型（LVLMs）和GPT-4o，发现即使是表现最佳的模型，在理解隐含意义方面也比人类水平落后近14%。我们的研究结果凸显了当前LVLMs在捕捉微妙视觉语义方面所面临的内在挑战，并为未来在这一领域的研究和开发指明了重要方向。我们将公开发布我们的InsightVision数据集和代码，待论文接受后。


> In the evolving landscape of multimodal language models, understanding the nuanced meanings conveyed through visual cues - such as satire, insult, or critique - remains a significant challenge. Existing evaluation benchmarks primarily focus on direct tasks like image captioning or are limited to a narrow set of categories, such as humor or satire, for deep semantic understanding. To address this gap, we introduce, for the first time, a comprehensive, multi-level Chinese-based benchmark designed specifically for evaluating the understanding of implicit meanings in images. This benchmark is systematically categorized into four subtasks: surface-level content understanding, symbolic meaning interpretation, background knowledge comprehension, and implicit meaning comprehension. We propose an innovative semi-automatic method for constructing datasets, adhering to established construction protocols. Using this benchmark, we evaluate 15 open-source large vision language models (LVLMs) and GPT-4o, revealing that even the best-performing model lags behind human performance by nearly 14% in understanding implicit meaning. Our findings underscore the intrinsic challenges current LVLMs face in grasping nuanced visual semantics, highlighting significant opportunities for future research and development in this domain. We will publicly release our InsightVision dataset, code upon acceptance of the paper.

[Arxiv](https://arxiv.org/abs/2502.15812)