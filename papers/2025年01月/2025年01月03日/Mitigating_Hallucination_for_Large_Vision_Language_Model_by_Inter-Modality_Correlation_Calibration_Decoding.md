# 跨模态相关性校准解码：减轻大型视觉语言模型的幻觉问题

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了大型视觉语言模型（LVLMs）在生成任务中的幻觉问题，并提出了一种新的解码方法（IMCCD）来减轻这一问题。虽然涉及多模态任务，但其核心是改进LLM在生成任务中的应用效果，因此应归类为LLM应用。` `计算机视觉`

> Mitigating Hallucination for Large Vision Language Model by Inter-Modality Correlation Calibration Decoding

# 摘要

> # 摘要
大型视觉语言模型（LVLMs）在多模态任务的视觉语言理解中表现出色，但在复杂生成任务中仍存在幻觉问题，导致视觉输入与生成内容不一致。为此，一些方法引入了推理时干预，如对比解码和注意力校正，以减少对语言先验的过度依赖。然而，这些方法忽略了由虚假跨模态相关性引发的幻觉。本文提出了一种跨模态相关性校准解码（IMCCD）方法，无需训练即可减轻LVLMs中的幻觉。我们设计了跨模态值增强解码（CMVED）模块，通过新颖的对比解码机制缓解幻觉。在估计失真分布时，CMVED屏蔽了与显著跨模态注意力权重相关的值向量，解决了单模态过度依赖和误导性跨模态相关性的问题。此外，内容驱动的注意力精炼（CDAR）模块优化了跨模态注意力权重，引导LVLMs聚焦重要视觉内容。在多种幻觉基准上的实验结果验证了我们的方法在减少LVLM文本生成中的幻觉方面优于现有技术。代码将在https://github.com/lijm48/IMCCD上提供。

> Large vision-language models (LVLMs) have shown remarkable capabilities in visual-language understanding for downstream multi-modal tasks. Despite their success, LVLMs still suffer from generating hallucinations in complex generation tasks, leading to inconsistencies between visual inputs and generated content. To address this issue, some approaches have introduced inference-time interventions, such as contrastive decoding and attention rectification, to reduce overreliance on language priors. However, these approaches overlook hallucinations stemming from spurious inter-modality correlations. In this paper, we propose an Inter-Modality Correlation Calibration Decoding (IMCCD) method to mitigate hallucinations in LVLMs in a training-free manner. In this method, we design a Cross-Modal Value-Enhanced Decoding(CMVED) module to alleviate hallucination by a novel contrastive decoding mechanism. During the estimation of distorted distribution, CMVED masks the value vectors associated with significant cross-modal attention weights, which address both uni-modality overreliance and misleading inter-modality correlations. Additionally, a Content-Driven Attention Refinement(CDAR) module refines cross-modal attention weights, guiding LVLMs to focus on important visual content. Experimental results on diverse hallucination benchmarks validate the superiority of our method over existing state-of-the-art techniques in reducing hallucinations in LVLM text generation. Our code will be available at https://github.com/lijm48/IMCCD.

[Arxiv](https://arxiv.org/abs/2501.01926)