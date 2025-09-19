# 释放多模态大型语言模型（LLMs）在零样本时空视频定位中的潜能

发布时间：2025年09月18日

`LLM应用` `媒体与娱乐`

> Unleashing the Potential of Multimodal LLMs for Zero-Shot Spatio-Temporal Video Grounding

# 摘要

> 时空视频定位（STVG）的目标是根据输入文本查询，定位视频中的时空片段。本文利用多模态大型语言模型（MLLMs），探索了STVG的零样本解决方案。我们发现MLLMs存在两个关键特性：（1）它们会动态分配特殊标记（称为grounding tokens）来完成文本查询的定位；（2）由于无法充分整合文本查询中的线索（如属性、动作）进行推理，MLLMs的定位效果往往不理想。基于这些发现，我们提出了一个基于MLLM的STVG零样本框架，其中包含新颖的分解时空高亮（DSTH）和时间增强组装（TAS）策略，以充分发挥MLLMs的推理能力。DSTH策略首先将原始查询分解为属性子查询和动作子查询，分别从空间和时间维度查询目标是否存在。接着，该策略通过一种新颖的logit引导重注意力（LRA）模块，对每个子查询的标记预测进行正则化，从而学习潜在变量作为空间和时间提示。这些提示分别突出属性和动作线索，引导模型关注可靠的时空相关视觉区域。此外，考虑到属性子查询的空间定位需保持时间一致性，我们引入TAS策略，将原始视频帧和时间增强帧作为输入来组装预测结果，从而提升时间一致性。我们在多种MLLMs上对该方法进行了评估，结果表明它在三个常用的STVG基准测试中性能优于现有SOTA方法。相关代码将发布于https://github.com/zaiquanyang/LLaVA_Next_STVG。

> Spatio-temporal video grounding (STVG) aims at localizing the spatio-temporal tube of a video, as specified by the input text query. In this paper, we utilize multimodal large language models (MLLMs) to explore a zero-shot solution in STVG. We reveal two key insights about MLLMs: (1) MLLMs tend to dynamically assign special tokens, referred to as \textit{grounding tokens}, for grounding the text query; and (2) MLLMs often suffer from suboptimal grounding due to the inability to fully integrate the cues in the text query (\textit{e.g.}, attributes, actions) for inference. Based on these insights, we propose a MLLM-based zero-shot framework for STVG, which includes novel decomposed spatio-temporal highlighting (DSTH) and temporal-augmented assembling (TAS) strategies to unleash the reasoning ability of MLLMs. The DSTH strategy first decouples the original query into attribute and action sub-queries for inquiring the existence of the target both spatially and temporally. It then uses a novel logit-guided re-attention (LRA) module to learn latent variables as spatial and temporal prompts, by regularizing token predictions for each sub-query. These prompts highlight attribute and action cues, respectively, directing the model's attention to reliable spatial and temporal related visual regions. In addition, as the spatial grounding by the attribute sub-query should be temporally consistent, we introduce the TAS strategy to assemble the predictions using the original video frames and the temporal-augmented frames as inputs to help improve temporal consistency. We evaluate our method on various MLLMs, and show that it outperforms SOTA methods on three common STVG benchmarks.
  The code will be available at https://github.com/zaiquanyang/LLaVA_Next_STVG.

[Arxiv](https://arxiv.org/abs/2509.15178)