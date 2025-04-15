# FUSION：深度跨模态理解的视觉语言表示全面整合方案

发布时间：2025年04月14日

`LLM应用

理由：这篇论文介绍了FUSION，一个多模态大型语言模型家族，探讨了其架构、创新技术以及在多模态任务中的应用和优化。虽然涉及模型的理论方面，但主要关注点在于实际应用和性能提升，因此归类为LLM应用。` `问答系统` `计算机视觉`

> FUSION: Fully Integration of Vision-Language Representations for Deep Cross-Modal Understanding

# 摘要

> 我们很高兴推出FUSION——一个全新的多模态大型语言模型家族。与现有方法不同，FUSION不仅限于在解码阶段依赖模态交互，而是实现了从输入到输出的深度动态整合。具体来说，我们提出了两项创新技术：基于文本引导的统一视觉编码和上下文感知递归对齐解码。前者通过在视觉编码中引入文本信息实现像素级的深度整合，后者通过递归聚合基于文本上下文的视觉特征，实现了细粒度、问题级别的语义整合。为了进一步优化模型性能，我们开发了双监督语义映射损失，并通过一种全新的数据合成方法构建了一个高质量的问答数据集。在这些创新的基础上，我们推出了FUSION 3B和FUSION 8B两个版本。实验结果表明，FUSION在多项基准测试中超越了现有的8B参数模型，甚至在视觉令牌数量大幅减少的情况下仍保持优势。我们的消融实验进一步证明了FUSION方法的有效性。为了促进研究，我们已将代码、模型权重和数据集开源。https://github.com/starriver030515/FUSION

> We introduce FUSION, a family of multimodal large language models (MLLMs) with a fully vision-language alignment and integration paradigm. Unlike existing methods that primarily rely on late-stage modality interaction during LLM decoding, our approach achieves deep, dynamic integration throughout the entire processing pipeline. To this end, we propose Text-Guided Unified Vision Encoding, incorporating textual information in vision encoding to achieve pixel-level integration. We further design Context-Aware Recursive Alignment Decoding that recursively aggregates visual features conditioned on textual context during decoding, enabling fine-grained, question-level semantic integration. To guide feature mapping and mitigate modality discrepancies, we develop Dual-Supervised Semantic Mapping Loss. Additionally, we construct a Synthesized Language-Driven Question-Answer (QA) dataset through a new data synthesis method, prioritizing high-quality QA pairs to optimize text-guided feature integration. Building on these foundations, we train FUSION at two scales-3B, 8B-and demonstrate that our full-modality integration approach significantly outperforms existing methods with only 630 vision tokens. Notably, FUSION 3B surpasses Cambrian-1 8B and Florence-VL 8B on most benchmarks. FUSION 3B continues to outperform Cambrian-1 8B even when limited to 300 vision tokens. Our ablation studies show that FUSION outperforms LLaVA-NeXT on over half of the benchmarks under same configuration without dynamic resolution, highlighting the effectiveness of our approach. We release our code, model weights, and dataset. https://github.com/starriver030515/FUSION

[Arxiv](https://arxiv.org/abs/2504.09925)