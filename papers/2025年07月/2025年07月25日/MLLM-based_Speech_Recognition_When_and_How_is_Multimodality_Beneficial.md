# 基于多模态大型语言模型的语音识别：何时及如何受益于多模态？

发布时间：2025年07月25日

`LLM应用` `语音识别` `多模态技术`

> MLLM-based Speech Recognition: When and How is Multimodality Beneficial?

# 摘要

> 多模态大语言模型（MLLMs）的最新进展为语音、文本、图像等多模态信息的统一建模带来了全新可能。基于前期研究成果，本文深入探讨了噪声环境下，多模态输入如何优化自动语音识别（ASR）性能的条件及模型架构。通过合成数据与真实场景数据的实验，我们得出以下发现：(1) 整合多模态信息通常能显著提升ASR准确性，因各模态信息互补，但提升幅度受噪声强度影响。(2) 同步模态（如口型动作）在高噪声环境下更具优势，而不同步模态（如图像背景）则在中等噪声环境下表现更佳。(3) 更高质量的视觉表示始终有助于提升ASR性能，凸显了开发更强大视觉编码器的重要性。(4) Mamba与Transformers在多模态优势方面呈现相似趋势。(5) 模态的输入顺序及其在损失函数中的权重设置对最终准确性影响重大。这些发现不仅为实际应用提供了宝贵见解，更深化了我们对复杂条件下多模态语音识别机制的理解。

> Recent advances in multi-modal large language models (MLLMs) have opened new possibilities for unified modeling of speech, text, images, and other modalities. Building on our prior work, this paper examines the conditions and model architectures under which multiple input modalities can improve automatic speech recognition (ASR) accuracy in noisy environments. Through experiments on synthetic and real-world data, we find that (1) harnessing more modalities usually improves ASR accuracy, as each modality provides complementary information, but the improvement depends on the amount of auditory noise. (2) Synchronized modalities (e.g., lip movements) are more useful at high noise levels whereas unsynchronized modalities (e.g., image context) are most helpful at moderate noise levels. (3) Higher-quality visual representations consistently improve ASR accuracy, highlighting the importance of developing more powerful visual encoders. (4) Mamba exhibits similar trends regarding the benefits of multimodality as do Transformers. (5) The input order of modalities as well as their weights in the loss function can significantly impact accuracy. These findings both offer practical insights and help to deepen our understanding of multi-modal speech recognition under challenging conditions.

[Arxiv](https://arxiv.org/abs/2507.19037)