# 研究多模态语言模型中的细粒度对齐，增强视觉理解能力

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了视觉嵌入与大型语言模型（LLMs）的对齐问题，特别是在提升多模态LLMs能力方面的作用。研究提出了一种新的方法，即补丁级别对齐和补丁对齐训练，以增强LLMs对视觉信息的理解。这些改进在多个任务中提升了性能，属于LLM应用的范畴，因为它专注于如何将LLMs应用于多模态数据处理，而不是理论上的改进或新的模型结构。` `多模态` `计算机视觉`

> Analyzing Fine-Grained Alignment and Enhancing Vision Understanding in Multimodal Language Models

# 摘要

> 视觉嵌入与LLMs的对齐对提升多模态LLMs的能力至关重要，特别是对于那些依赖预训练视觉编码器和LLMs的模型。通常，我们通过在视觉编码器后添加一个投影器来连接视觉编码器和LLM。然而，现有的投影器主要为生成描述而设计，LLM如何理解每个视觉标记仍是个谜。本研究首先探讨了投影器在压缩视觉嵌入和与词嵌入对齐方面的作用。我们发现，投影器能够有效压缩视觉信息，在去除冗余细节的同时保留关键内容，从而帮助LLM更好地理解视觉信息。随后，我们提出了*补丁级别对齐*的概念，并基于此提出了*多语义对齐假设*。通过分析发现，基于描述损失训练的投影器仅能实现有限的补丁级别对齐，导致对齐效果较弱。为解决这一问题，我们提出了*补丁对齐训练*方法，显著提升了补丁级别的对齐效果。实验结果表明，补丁对齐训练不仅增强了压缩能力，还能生成更高质量的描述，同时在引用表达接地任务、问答任务和现代指令遵循基准测试中分别提升了16%、4%和3%的性能。这一方法具有良好的扩展性，可适用于其他多模态模型。

> Achieving better alignment between vision embeddings and Large Language Models (LLMs) is crucial for enhancing the abilities of Multimodal LLMs (MLLMs), particularly for recent models that rely on powerful pretrained vision encoders and LLMs. A common approach to connect the pretrained vision encoder and LLM is through a projector applied after the vision encoder. However, the projector is often trained to enable the LLM to generate captions, and hence the mechanism by which LLMs understand each vision token remains unclear. In this work, we first investigate the role of the projector in compressing vision embeddings and aligning them with word embeddings. We show that the projector significantly compresses visual information, removing redundant details while preserving essential elements necessary for the LLM to understand visual content. We then examine patch-level alignment -- the alignment between each vision patch and its corresponding semantic words -- and propose a *multi-semantic alignment hypothesis*. Our analysis indicates that the projector trained by caption loss improves patch-level alignment but only to a limited extent, resulting in weak and coarse alignment. To address this issue, we propose *patch-aligned training* to efficiently enhance patch-level alignment. Our experiments show that patch-aligned training (1) achieves stronger compression capability and improved patch-level alignment, enabling the MLLM to generate higher-quality captions, (2) improves the MLLM's performance by 16% on referring expression grounding tasks, 4% on question-answering tasks, and 3% on modern instruction-following benchmarks when using the same supervised fine-tuning (SFT) setting. The proposed method can be easily extended to other multimodal models.

[Arxiv](https://arxiv.org/abs/2505.17316)