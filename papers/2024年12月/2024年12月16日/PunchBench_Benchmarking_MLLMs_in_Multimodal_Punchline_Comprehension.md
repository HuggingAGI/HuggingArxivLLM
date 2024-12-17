# PunchBench：针对多模态妙语理解中的大型多模态语言模型开展基准测试

发布时间：2024年12月16日

`LLM应用` `多媒体` `在线交流`

> PunchBench: Benchmarking MLLMs in Multimodal Punchline Comprehension

# 摘要

> 多模态妙语，即在图像与说明的搭配中传递幽默或讽刺，是在线多媒体平台上常见的交流方式。随着多模态大型语言模型（MLLMs）的迅速发展，评估它们有效理解这类妙语的能力变得至关重要。然而，现有的妙语理解基准存在三大局限：1. 存在语言捷径，导致模型仅依赖文本；2. 问题缺乏多样性；3. 对多模态内容的特定领域（比如卡通）关注面狭窄。为应对这些局限，我们推出了一个多模态的【妙语】理解【基准】，名为【PunchBench】，专门用于对妙语理解进行准确且全面的评估。为提升评估的准确性，我们通过修改原始说明生成同义及反义说明，从而降低说明中捷径的影响。为提供全面评估，PunchBench 整合了来自不同领域的多种问题格式和图像-说明。在此基础上，我们进行了广泛评估，发现最先进的 MLLMs 与人类在妙语理解方面存在显著差距。为改进妙语理解，我们提出了从简单到复杂的问题链（SC-CoQ）策略，让模型先掌握简单问题，再逐步处理复杂问题。SC-CoQ 有效提升了各种 MLLMs 在 PunchBench 上的表现，超越了上下文学习和思维链。

> Multimodal punchlines, which involve humor or sarcasm conveyed in image-caption pairs, are a popular way of communication on online multimedia platforms. With the rapid development of multimodal large language models (MLLMs), it is essential to assess their ability to effectively comprehend these punchlines. However, existing benchmarks on punchline comprehension suffer from three major limitations: 1) language shortcuts that allow models to solely rely on text, 2) lack of question diversity, and 3) narrow focus on a specific domain of multimodal content (e.g., cartoon). To address these limitations, we introduce a multimodal \textbf{Punch}line comprehension \textbf{Bench}mark, named \textbf{PunchBench}, which is tailored for accurate and comprehensive evaluation of punchline comprehension. To enhance the evaluation accuracy, we generate synonymous and antonymous captions by modifying original captions, which mitigates the impact of shortcuts in the captions. To provide a comprehensive evaluation, PunchBench incorporates diverse question formats and image-captions from various domains. On this basis, we conduct extensive evaluations and reveal a significant gap between state-of-the-art MLLMs and humans in punchline comprehension. To improve punchline comprehension, we propose Simple-to-Complex Chain-of-Question (SC-CoQ) strategy, enabling the models to incrementally address complicated questions by first mastering simple ones. SC-CoQ effectively enhances the performance of various MLLMs on PunchBench, surpassing in-context learning and chain-of-thought.

[Arxiv](https://arxiv.org/abs/2412.11906)