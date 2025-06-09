# # 当语义误导视觉：研究大模型在场景文本检测与理解中的幻觉现象及缓解方法

发布时间：2025年06月05日

`LLM应用` `视觉感知` `计算机视觉`

> When Semantics Mislead Vision: Mitigating Large Multimodal Models Hallucinations in Scene Text Spotting and Understanding

# 摘要

> 大型多模态模型（LMMs）在视觉感知与推理领域取得了显著进展，但在处理视觉模糊或非语义场景文本时，常因生成语义合理却视觉错误的回答而产生语义幻觉。本研究深入探究了语义幻觉的成因，发现大型语言模型（LLM）中注意力机制更强的Transformer层更少出现此类问题。基于此，我们提出了一种无需训练的语义幻觉缓解框架，包含两大核心组件：(1) ZoomText，一种无需外部检测器的从粗到细策略，用于识别潜在文本区域；(2) 基于事实的层校正，通过自适应利用更不易产生幻觉的层的内部表示指导解码，有效纠正非语义样本的幻觉输出，同时保留有意义样本的语义。为确保评估的严谨性，我们构建了TextHalu-Bench基准测试，涵盖1,730多个样本，包含语义与非语义案例，并附带手动整理的问题-答案对，专门用于探测模型幻觉。实验结果表明，本方法不仅显著缓解了语义幻觉，还在场景文本识别与理解的公共基准测试中表现优异。

> Large Multimodal Models (LMMs) have achieved impressive progress in visual perception and reasoning. However, when confronted with visually ambiguous or non-semantic scene text, they often struggle to accurately spot and understand the content, frequently generating semantically plausible yet visually incorrect answers, which we refer to as semantic hallucination. In this work, we investigate the underlying causes of semantic hallucination and identify a key finding: Transformer layers in LLM with stronger attention focus on scene text regions are less prone to producing semantic hallucinations. Thus, we propose a training-free semantic hallucination mitigation framework comprising two key components: (1) ZoomText, a coarse-to-fine strategy that identifies potential text regions without external detectors; and (2) Grounded Layer Correction, which adaptively leverages the internal representations from layers less prone to hallucination to guide decoding, correcting hallucinated outputs for non-semantic samples while preserving the semantics of meaningful ones. To enable rigorous evaluation, we introduce TextHalu-Bench, a benchmark of over 1,730 samples spanning both semantic and non-semantic cases, with manually curated question-answer pairs designed to probe model hallucinations. Extensive experiments demonstrate that our method not only effectively mitigates semantic hallucination but also achieves strong performance on public benchmarks for scene text spotting and understanding.

[Arxiv](https://arxiv.org/abs/2506.05551)