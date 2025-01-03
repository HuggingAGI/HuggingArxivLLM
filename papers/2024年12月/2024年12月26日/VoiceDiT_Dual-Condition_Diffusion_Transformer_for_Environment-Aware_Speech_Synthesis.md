# VoiceDiT: 双条件扩散变压器，实现环境感知语音合成

发布时间：2024年12月26日

`其他

理由：这篇论文主要介绍了一个多模态生成模型VoiceDiT，它能够根据文本和视觉提示生成环境感知的语音和音频。虽然涉及到文本和语音的处理，但核心内容并不直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `语音生成` `多模态`

> VoiceDiT: Dual-Condition Diffusion Transformer for Environment-Aware Speech Synthesis

# 摘要

> 我们推出了VoiceDiT，一个多模态生成模型，能够根据文本和视觉提示生成环境感知的语音和音频。尽管语音与文本的对齐对于清晰语音至关重要，但在嘈杂环境中实现这一目标仍是该领域的一大挑战。为此，我们开发了VoiceDiT音频生成管道，包含三大核心组件：（1）构建大规模合成语音数据集用于预训练，以及精细的真实语音数据集用于微调；（2）Dual-DiT模型，旨在高效保留语音对齐信息并准确反映环境条件；（3）基于扩散的图像到音频翻译器，帮助模型跨越音频与图像的鸿沟，生成与多模态提示相匹配的环境声音。实验证明，VoiceDiT在真实数据集上表现卓越，音频质量和模态融合均有显著提升。

> We present VoiceDiT, a multi-modal generative model for producing environment-aware speech and audio from text and visual prompts. While aligning speech with text is crucial for intelligible speech, achieving this alignment in noisy conditions remains a significant and underexplored challenge in the field. To address this, we present a novel audio generation pipeline named VoiceDiT. This pipeline includes three key components: (1) the creation of a large-scale synthetic speech dataset for pre-training and a refined real-world speech dataset for fine-tuning, (2) the Dual-DiT, a model designed to efficiently preserve aligned speech information while accurately reflecting environmental conditions, and (3) a diffusion-based Image-to-Audio Translator that allows the model to bridge the gap between audio and image, facilitating the generation of environmental sound that aligns with the multi-modal prompts. Extensive experimental results demonstrate that VoiceDiT outperforms previous models on real-world datasets, showcasing significant improvements in both audio quality and modality integration.

[Arxiv](https://arxiv.org/abs/2412.19259)