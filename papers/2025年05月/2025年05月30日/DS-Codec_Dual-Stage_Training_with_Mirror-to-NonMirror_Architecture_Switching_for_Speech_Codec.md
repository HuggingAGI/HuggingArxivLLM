# DS-Codec：通过镜像架构切换实现的双阶段训练语音编解码器

发布时间：2025年05月30日

`其他` `语音合成` `语音处理`

> DS-Codec: Dual-Stage Training with Mirror-to-NonMirror Architecture Switching for Speech Codec

# 摘要

> 神经语音编解码器是推动文本到语音（TTS）系统发展的关键。随着大型语言模型在文本生成领域的成功，开发高质量的语音分词器变得日益重要。本文提出了DS-Codec，一种创新的神经语音编解码器，其双阶段训练框架通过镜像与非镜像架构的切换设计，以实现更优的语音重构效果。我们进行了深入的实验和消融研究，验证了训练策略的有效性，并对两种架构的性能进行了对比。结果显示，镜像结构显著提升了代码本的鲁棒性，而我们的训练策略成功平衡了镜像与非镜像结构的优势，最终实现了更高保真的语音重构效果。

> Neural speech codecs are essential for advancing text-to-speech (TTS) systems. With the recent success of large language models in text generation, developing high-quality speech tokenizers has become increasingly important. This paper introduces DS-Codec, a novel neural speech codec featuring a dual-stage training framework with mirror and non-mirror architectures switching, designed to achieve superior speech reconstruction. We conduct extensive experiments and ablation studies to evaluate the effectiveness of our training strategy and compare the performance of the two architectures. Our results show that the mirrored structure significantly enhances the robustness of the learned codebooks, and the training strategy balances the advantages between mirrored and non-mirrored structures, leading to improved high-fidelity speech reconstruction.

[Arxiv](https://arxiv.org/abs/2505.24314)