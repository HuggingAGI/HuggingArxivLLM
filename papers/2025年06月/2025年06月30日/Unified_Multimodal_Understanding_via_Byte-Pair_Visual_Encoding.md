# # 统一多模态理解：通过字节对视觉编码实现

发布时间：2025年06月30日

`LLM理论` `视觉语言` `多模态模型`

> Unified Multimodal Understanding via Byte-Pair Visual Encoding

# 摘要

> 多模态大型语言模型（MLLMs）在视觉语言理解领域取得了长足的进步，但如何有效整合不同模态的信息仍是关键挑战。我们提出了一种全新框架，通过将字节对编码应用于视觉标记，实现了多模态理解的统一。与传统方法依赖模态专属编码器不同，我们的方法直接将结构信息融入视觉标记，这一策略灵感源自仅用于文本的语言模型中的成功标记化方案。我们创新性地引入了一种基于优先级的编码方案，综合考量频率和空间一致性，并结合数据驱动的多阶段训练流程。这些优化显著提升了Transformer模型捕捉跨模态关系和视觉推理的能力。详实的实验结果表明，我们的方法在各类视觉语言任务中均表现优异。通过有效弥合视觉与文本表示之间的鸿沟，我们的研究为构建更强大、更高效的多模态基础模型奠定了坚实基础。

> Multimodal large language models (MLLMs) have made significant progress in vision-language understanding, yet effectively aligning different modalities remains a fundamental challenge. We present a framework that unifies multimodal understanding by applying byte-pair encoding to visual tokens. Unlike conventional approaches that rely on modality-specific encoders, our method directly incorporates structural information into visual tokens, mirroring successful tokenization strategies in text-only language models. We introduce a priority-guided encoding scheme that considers both frequency and spatial consistency, coupled with a multi-stage training procedure based on curriculum-driven data composition. These enhancements enable the transformer model to better capture cross-modal relationships and reason with visual information. Comprehensive experiments demonstrate improved performance across diverse vision-language tasks. By bridging the gap between visual and textual representations, our approach contributes to the advancement of more capable and efficient multimodal foundation models.

[Arxiv](https://arxiv.org/abs/2506.23639)