# 情感-Qwen：统一情感与视觉语言理解的混合专家训练

发布时间：2025年05月10日

`LLM应用` `情感分析` `多模态处理`

> Emotion-Qwen: Training Hybrid Experts for Unified Emotion and General Vision-Language Understanding

# 摘要

> 视频情感理解的目标是通过结合上下文、视觉、文本和听觉线索，准确识别人的情感状态。尽管大型多模态模型（LMMs）在视觉-语言任务上取得了显著进展，但它们在情感特定场景中的表现仍有局限。此外，针对情感任务对LMMs进行微调往往会导致灾难性遗忘，限制了它们在不同任务间的泛化能力。为了解决这些问题，我们提出了Emotion-Qwen——一个专为提升情感理解和通用视觉-语言推理能力而设计的多模态框架。Emotion-Qwen采用了基于专家混合（MoE）范式的混合压缩器，能够动态路由输入，平衡情感特定处理与通用处理。该模型通过在大规模通用和情感图像数据集上进行三阶段预训练，形成了稳健的多模态表示能力。此外，我们构建了视频情感推理（VER）数据集，包含超过40,000个双语视频片段，配有精细的描述性标注，进一步增强了Emotion-Qwen的情感推理能力。实验结果表明，Emotion-Qwen在多个情感识别基准测试中达到了前沿水平，同时在通用视觉-语言任务中也保持了竞争力。代码和模型可在https://anonymous.4open.science/r/Emotion-Qwen-Anonymous获取。

> Emotion understanding in videos aims to accurately recognize and interpret individuals' emotional states by integrating contextual, visual, textual, and auditory cues. While Large Multimodal Models (LMMs) have demonstrated significant progress in general vision-language (VL) tasks, their performance in emotion-specific scenarios remains limited. Moreover, fine-tuning LMMs on emotion-related tasks often leads to catastrophic forgetting, hindering their ability to generalize across diverse tasks. To address these challenges, we present Emotion-Qwen, a tailored multimodal framework designed to enhance both emotion understanding and general VL reasoning. Emotion-Qwen incorporates a sophisticated Hybrid Compressor based on the Mixture of Experts (MoE) paradigm, which dynamically routes inputs to balance emotion-specific and general-purpose processing. The model is pre-trained in a three-stage pipeline on large-scale general and emotional image datasets to support robust multimodal representations. Furthermore, we construct the Video Emotion Reasoning (VER) dataset, comprising more than 40K bilingual video clips with fine-grained descriptive annotations, to further enrich Emotion-Qwen's emotional reasoning capability. Experimental results demonstrate that Emotion-Qwen achieves state-of-the-art performance on multiple emotion recognition benchmarks, while maintaining competitive results on general VL tasks. Code and models are available at https://anonymous.4open.science/r/Emotion-Qwen-Anonymous.

[Arxiv](https://arxiv.org/abs/2505.06685)