# 通过注意力校准缓解大型视觉-语言模型中的物体幻觉

发布时间：2025年02月03日

`LLM应用

**理由**：该论文主要讨论了大型视觉-语言模型（LVLMs）在生成响应时产生的物体幻觉问题，并提出了两种解决方案（UAC和DAC）来缓解这一问题。这些方法旨在改进模型的多模态推理能力，属于对现有大型语言模型（LLM）在实际应用中的优化和改进，因此应归类为LLM应用。` `计算机视觉` `多模态学习`

> Mitigating Object Hallucinations in Large Vision-Language Models via Attention Calibration

# 摘要

> 大型视觉-语言模型（LVLMs）展现了强大的多模态推理能力，但依然容易产生物体幻觉，即模型生成的响应与视觉内容不符。最近的研究指出，这一问题源于LVLMs的固有偏差——视觉标记的注意力图与空间位置存在固定关联，并提出了通过重新排序视觉标记来缓解这一问题。然而，我们发现不同LVLMs的注意力与空间位置的相关性各异，导致现有方案难以推广。为此，我们首先提出了一种无需训练的解决方案——均匀注意力校准（UAC），它通过单个无意义图像估计偏差，并利用校准矩阵纠正注意力失衡。为进一步缓解偏差，我们放宽了UAC中对单个无意义输入的假设，引入了一种微调方案——动态注意力校准（DAC），通过即插即用模块确保模型在物体位置变化时输出一致。多个基准测试表明，UAC和DAC显著减少了物体幻觉，同时提升了多模态对齐效果。我们的方法在各种LVLM架构上均达到了最先进的性能。

> Large Vision-Language Models (LVLMs) exhibit impressive multimodal reasoning capabilities but remain highly susceptible to object hallucination, where models generate responses that are not factually aligned with the visual content. Recent works attribute this issue to an inherent bias of LVLMs where vision token attention map has a fixed correlation with spatial position, and propose to mitigate this issue by reordering visual tokens. However, we find that different LVLMs exhibit different correlations between attention and spatial position, which makes the existing solution difficult to generalize to other LVLMs. To address this issue, we first introduce a training-free solution, Uniform Attention Calibration (UAC), that estimates the bias from single meaningless input image and applies a calibration matrix to rectify attention imbalances. To further alleviate the bias, we relax the assumption of single meaningless input in UAC and introduce a fine-tuning solution, Dynamic Attention Calibration (DAC), that enforces the consistent outputs wherever the object locates in the image via a plug-and-plays module. Comprehensive experiments across multiple benchmarks demonstrate that UAC and DAC significantly reduce object hallucination while improving general multimodal alignment. Our methods achieve state-of-the-art performance across diverse LVLM architectures on various metrics.

[Arxiv](https://arxiv.org/abs/2502.01969)