# # OmniGenBench：跨越50+任务的全能多模态生成基准

发布时间：2025年05月24日

`LLM应用

理由：这篇论文讨论了大型多模态模型（LMMs）在生成图像方面的应用，并提出了一个全面的基准测试OmniGenBench来评估这些模型的指令遵循能力。它主要关注模型的实际应用和性能评估，因此属于LLM应用类别。` `人工智能` `生成模型`

> OmniGenBench: A Benchmark for Omnipotent Multimodal Generation across 50+ Tasks

# 摘要

> 大型多模态模型（LMMs）近期的突破性进展，如GPT-4o-Native，已展现出在遵循通用指令生成图像方面的卓越能力。然而，现有基准测试在评估这些模型的多样化能力时往往显得力不从心。为解决这一问题，我们推出了OmniGenBench——一个全新且全面的基准测试，它专门设计用于评估最先进的LMMs在感知中心和认知中心两个维度上的指令遵循能力。OmniGenBench包含57个基于现实场景的多样化子任务，这些任务根据所需的具体模型能力进行了系统分类。为了确保评估的严谨性，我们采用了双模式协议：利用现成的视觉解析工具处理感知中心任务，并借助强大的基于LLM的评估器处理认知中心任务，以评估生成图像与用户指令的一致性。通过OmniGenBench，我们对包括GPT-4o、Gemini-2.0-Flash和Seedream在内的主流生成模型进行了评估，并提供了对其性能的深入比较和分析。代码和数据可在https://github.com/emilia113/OmniGenBench获取。

> Recent breakthroughs in large multimodal models (LMMs), such as the impressive GPT-4o-Native, have demonstrated remarkable proficiency in following general-purpose instructions for image generation. However, current benchmarks often lack the necessary breadth and depth to fully evaluate the diverse capabilities of these models. To overcome this limitation, we introduce OmniGenBench, a novel and comprehensive benchmark meticulously designed to assess the instruction-following abilities of state-of-the-art LMMs across both perception-centric and cognition-centric dimensions. Our OmniGenBench includes 57 diverse sub-tasks grounded in real-world scenarios, systematically categorized according to the specific model capabilities they demand. For rigorous evaluation, we further employ a dual-mode protocol. This protocol utilizes off-the-shelf visual parsing tools for perception-centric tasks and a powerful LLM-based judger for cognition-centric tasks to assess the alignment between generated images and user instructions. Using OmniGenBench, we evaluate mainstream generative models, including prevalent models like GPT-4o, Gemini-2.0-Flash, and Seedream, and provide in-depth comparisons and analyses of their performance.Code and data are available at https://github.com/emilia113/OmniGenBench.

[Arxiv](https://arxiv.org/abs/2505.18775)