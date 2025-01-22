# 调整注意力失衡，缓解大型视觉语言模型的上下文幻觉

发布时间：2025年01月21日

`LLM应用

**理由**：该论文主要研究的是大型视觉语言模型（LVLMs）在视觉内容理解和描述中的应用问题，特别是针对模型生成描述时出现的幻觉现象。论文提出了一种创新的注意力调整方法，旨在减少幻觉现象并提升模型的视觉基础。这属于对现有大型语言模型（LLM）在实际应用中的改进和优化，因此归类为LLM应用。` `计算机视觉`

> Fixing Imbalanced Attention to Mitigate In-Context Hallucination of Large Vision-Language Model

# 摘要

> 大型视觉语言模型（LVLMs）在视觉内容理解和描述方面表现出色，在多种视觉语言任务中达到了顶尖水平。然而，这些模型常出现幻觉现象，即生成的描述中包含了图像中并不存在的对象或细节。本研究通过分析跨变压器层和头的注意力模式，发现幻觉往往源于深层视觉基础的逐渐退化。为此，我们提出了一种创新的注意力调整方法，结合选择性标记强调和头特定调制，确保生成过程中视觉基础的稳固。该方法包含两个核心要素：（1）双流标记选择机制，用于识别并优先处理局部信息丰富和空间显著的视觉标记；（2）基于个体注意力头视觉敏感度的调制策略，差异性地增强视觉信息处理。通过在MSCOCO数据集上的大量实验，我们证实该方法将幻觉率降低了高达62.3\%，同时保持了任务性能。分析表明，通过选择性地调制不同视觉敏感度的注意力头中的标记，可显著提升视觉基础，且无需重新训练模型。

> Large Vision Language Models (LVLMs) have demonstrated remarkable capabilities in understanding and describing visual content, achieving state-of-the-art performance across various vision-language tasks. However, these models frequently exhibit hallucination behavior, where they generate descriptions containing objects or details absent in the input image. Our work investigates this phenomenon by analyzing attention patterns across transformer layers and heads, revealing that hallucinations often stem from progressive degradation of visual grounding in deeper layers. We propose a novel attention modification approach that combines selective token emphasis and head-specific modulation to maintain visual grounding throughout the generation process. Our method introduces two key components: (1) a dual-stream token selection mechanism that identifies and prioritizes both locally informative and spatially significant visual tokens, and (2) an attention head-specific modulation strategy that differentially amplifies visual information processing based on measured visual sensitivity of individual attention heads. Through extensive experimentation on the MSCOCO dataset, we demonstrate that our approach reduces hallucination rates by up to 62.3\% compared to baseline models while maintaining comparable task performance. Our analysis reveals that selectively modulating tokens across attention heads with varying levels of visual sensitivity can significantly improve visual grounding without requiring model retraining.

[Arxiv](https://arxiv.org/abs/2501.12206)