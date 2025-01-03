# 通过自下而上的整体推理解决多模态LLM的幻觉问题

发布时间：2024年12月15日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在视觉-语言任务中的应用，特别是如何解决MLLMs在感知和认知层面的幻觉问题。论文提出了一种新的推理框架来提升MLLMs的可靠性，并进行了实验验证。因此，这篇论文属于LLM应用类别，因为它关注的是如何在实际应用中改进和优化大型语言模型的性能。` `计算机视觉`

> Combating Multimodal LLM Hallucination via Bottom-up Holistic Reasoning

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）的最新进展在视觉-语言任务中展现了前所未有的能力。然而，MLLMs面临着幻觉和与输入数据不符的误导性输出的重大挑战。尽管现有研究致力于对抗MLLM的幻觉，但几个关键问题仍未解决。首先，当前方法主要关注感知层面的错误，而认知层面需要事实常识的错误可能被忽视。其次，现有方法在视觉输入表示上存在不足，这仍是触发视觉幻觉的关键瓶颈。此外，MLLMs常被错误的文本输入误导并产生幻觉，而这一问题长期被忽视。受人类处理幻觉的直觉启发，本文提出了一种新颖的自下而上推理框架。该框架通过验证和整合感知与认知层面的常识知识，系统解决了视觉和文本输入中的潜在问题，确保了更可靠的输出。大量实验表明，集成该框架后，MLLMs在多个幻觉基准测试中表现显著提升。深入分析揭示了该方法在解决感知和认知层面幻觉方面的巨大潜力。

> Recent advancements in multimodal large language models (MLLMs) have shown unprecedented capabilities in advancing various vision-language tasks. However, MLLMs face significant challenges with hallucinations, and misleading outputs that do not align with the input data. While existing efforts are paid to combat MLLM hallucinations, several pivotal challenges are still unsolved. First, while current approaches aggressively focus on addressing errors at the perception level, another important type at the cognition level requiring factual commonsense can be overlooked. In addition, existing methods might fall short in finding a more effective way to represent visual input, which is yet a key bottleneck that triggers visual hallucinations. Moreover, MLLMs can frequently be misled by faulty textual inputs and cause hallucinations, while unfortunately, this type of issue has long been overlooked by existing studies. Inspired by human intuition in handling hallucinations, this paper introduces a novel bottom-up reasoning framework. Our framework systematically addresses potential issues in both visual and textual inputs by verifying and integrating perception-level information with cognition-level commonsense knowledge, ensuring more reliable outputs. Extensive experiments demonstrate significant improvements in multiple hallucination benchmarks after integrating MLLMs with the proposed framework. In-depth analyses reveal the great potential of our methods in addressing perception- and cognition-level hallucinations.

[Arxiv](https://arxiv.org/abs/2412.11124)