# 重新审视跨模态不对齐下的大型视觉语言模型中的视觉令牌减少问题

发布时间：2025年06月27日

`LLM理论` `计算机视觉`

> Rethinking Visual Token Reduction in LVLMs under Cross-modal Misalignment

# 摘要

> 大型视觉语言模型（LVLMs）通过密集的补丁级标记序列编码视觉输入，以捕捉精细语义。然而，视觉标记数量远超文本标记，导致巨大计算开销，限制了模型的实际扩展性。尽管先前研究尝试通过LLM内外的视觉标记减少来优化，但大多数方法依赖文本引导，假设文本能可靠反映视觉重要性。我们重新审视这一假设，揭示了跨模态对齐中的因果、语义和空间错位，这些错位严重削弱了基于文本的视觉标记减少效果。为此，我们提出VisionDrop——一个无训练、纯视觉的剪枝框架，通过视觉到视觉的注意力选择信息丰富标记，无需文本信号。进一步地，我们将视觉编码器与LLM整合为统一系统，设计渐进式剪枝管道，在多阶段执行主导标记选择与轻量级上下文合并，即使在激进标记预算下也能保留精细视觉信息。实验表明，VisionDrop显著优于现有方法，且无需额外训练或复杂修改。其简洁高效的设计实现了快速推理，同时保持了跨任务的强大性能。

> Large Vision-Language Models (LVLMs) encode visual inputs as dense sequences of patch-level tokens to capture fine-grained semantics. These visual tokens often outnumber their textual counterparts by a large margin, leading to substantial computational overhead and limiting the scalability of LVLMs in practice. Previous efforts have explored visual token reduction either prior to or within the large language models (LLM). However, most in-LLM reduction approaches rely on text-conditioned interactions, implicitly assuming that textual tokens can reliably capture the importance of visual tokens. In this work, we revisit this assumption and reveal causal, semantic, and spatial forms of cross-modal misalignment. These misalignments undermine the effectiveness of text-guided visual token reduction. To address this, we introduce VisionDrop, a training-free, visual-only pruning framework that selects informative visual tokens based on intra-modal (visual-to-visual) attention, without relying on textual signals. To further suppress redundancy throughout the model hierarchy, we treat the visual encoder and the LLM as a unified system and design a progressive pruning pipeline. Our method performs dominant token selection and lightweight contextual merging at multiple stages, enabling fine-grained visual information to be retained even under aggressive token budgets. Extensive experiments across diverse benchmarks show that VisionDrop achieves consistent improvements over existing methods, despite requiring no additional training or complex modifications. Its simple yet effective design enables efficient inference while preserving strong performance across tasks.

[Arxiv](https://arxiv.org/abs/2506.22283)