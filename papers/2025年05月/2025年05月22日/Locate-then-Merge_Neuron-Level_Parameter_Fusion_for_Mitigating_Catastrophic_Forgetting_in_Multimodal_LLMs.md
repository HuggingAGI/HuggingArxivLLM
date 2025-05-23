# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月22日

`其他` `多模态`

> Locate-then-Merge: Neuron-Level Parameter Fusion for Mitigating Catastrophic Forgetting in Multimodal LLMs

# 摘要

> 多模态大语言模型（MLLMs）虽然表现出色，但在多模态指令微调阶段，基础大语言模型（LLM）的语言能力往往会出现灾难性遗忘，这一问题甚至在Llama3等强大模型中也难以避免。为解决这一问题，我们提出了一种名为Locate-then-Merge的无训练参数融合框架，该框架通过定位关键参数并有选择性地进行融合。此外，我们引入了Neuron-Fusion策略，这是一种神经元级别的融合方法，它能够保留那些参数变化显著的神经元（这些神经元很可能负责新获得的视觉能力）的影响，同时减弱参数变化较小的神经元（这些神经元可能编码了通用语言技能）的影响。这种设计不仅能够更好地保留视觉适应能力，还能够有效缓解语言能力的退化。在涵盖语言和视觉任务的13个基准测试中，实验结果表明Neuron-Fusion策略始终优于现有的模型融合方法。进一步的分析表明，我们的方法能够有效降低生成过程中出现的上下文幻觉现象。

> Although multimodal large language models (MLLMs) have achieved impressive performance, the multimodal instruction tuning stage often causes catastrophic forgetting of the base LLM's language ability, even in strong models like Llama3. To address this, we propose Locate-then-Merge, a training-free parameter fusion framework that first locates important parameters and then selectively merges them. We further introduce Neuron-Fusion, a neuron-level strategy that preserves the influence of neurons with large parameter shifts--neurons likely responsible for newly acquired visual capabilities--while attenuating the influence of neurons with smaller changes that likely encode general-purpose language skills. This design enables better retention of visual adaptation while mitigating language degradation. Experiments on 13 benchmarks across both language and visual tasks show that Neuron-Fusion consistently outperforms existing model merging methods. Further analysis reveals that our method effectively reduces context hallucination in generation.

[Arxiv](https://arxiv.org/abs/2505.16703)