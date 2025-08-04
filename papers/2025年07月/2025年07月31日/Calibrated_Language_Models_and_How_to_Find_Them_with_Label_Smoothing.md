# 校准语言模型：如何通过标签平滑方法发现它们

发布时间：2025年07月31日

`LLM理论` `人工智能`

> Calibrated Language Models and How to Find Them with Label Smoothing

# 摘要

> 自然语言处理（NLP）的最新进展为通过提升指令遵循能力，使微调后的大型语言模型（LLMs）成为更强大的交互式代理开辟了更多可能。然而，关于这一改进如何影响可靠输出的信心校准，研究仍不充分。本研究考察了多种开源LLMs，发现每种模型在指令调优后均出现显著的信心校准下降。为寻找实用解决方案，我们引入标签平滑，这是一种已被证明可有效缓解过于自信预测的方法，但在大型语言模型的监督微调（SFT）中尚未广泛应用。我们首先解释了标签平滑为何能在整个SFT过程中维持校准。然而，对于大词汇量的LLMs（LV-LLMs），平滑效果显著减弱。我们提出，这源于模型过度自信的能力，其与隐藏层大小和词汇量大小密切相关，并通过理论与实验加以证实。最后，我们解决了一个关于标签平滑损失设置下交叉熵损失计算内存占用的未决问题，设计了一种定制内核，与现有非平滑损失解决方案相比，大幅降低了内存消耗，同时保持速度与性能。

> Recent advances in natural language processing (NLP) have opened up greater opportunities to enable fine-tuned large language models (LLMs) to behave as more powerful interactive agents through improved instruction-following ability. However, understanding how this impacts confidence calibration for reliable model output has not been researched in full. In this work, we examine various open-sourced LLMs, identifying significant calibration degradation after instruction tuning in each. Seeking a practical solution, we look towards label smoothing, which has been shown as an effective method to regularize for overconfident predictions but has yet to be widely adopted in the supervised fine-tuning (SFT) of LLMs. We first provide insight as to why label smoothing is sufficient to maintain calibration throughout the SFT process. However, settings remain where the effectiveness of smoothing is severely diminished, in particular the case of large vocabulary LLMs (LV-LLMs). We posit the cause to stem from the ability to become over-confident, which has a direct relationship with the hidden size and vocabulary size, and justify this theoretically and experimentally. Finally, we address an outstanding issue regarding the memory footprint of the cross-entropy loss computation in the label smoothed loss setting, designing a customized kernel to dramatically reduce memory consumption without sacrificing speed or performance in comparison to existing solutions for non-smoothed losses.

[Arxiv](https://arxiv.org/abs/2508.00264)