# AsyMoE：借助模态不对称性增强大型视觉-语言模型的专家专精

发布时间：2025年09月16日

`LLM应用` `基础理论`

> AsyMoE: Leveraging Modal Asymmetry for Enhanced Expert Specialization in Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）凭借规模化架构和海量训练数据，在多模态任务中表现卓越。然而，现有的专家混合模型（MoE）方法因视觉与语言处理的不对称性而陷入困境：视觉信息具有空间完整性，语言则需保持序列上下文。这导致MoE模型难以平衡模态特定特征与跨模态交互。通过系统分析，我们发现深层语言专家会逐渐失去上下文关联，更多依赖参数化知识，而非利用输入的视觉与语言信息。为此，我们提出AsyMoE——一种新颖架构，通过三个专用专家组对这种不对称性进行建模。我们设计了模态内专家负责模态特定处理、双曲跨模态专家处理层级跨模态交互，以及证据优先语言专家来抑制参数偏差并维持上下文关联。大量实验结果显示，AsyMoE相比普通MoE和模态特定MoE的准确率分别提升了26.58%和15.45%，且激活参数比密集模型减少25.45%。

> Large Vision-Language Models (LVLMs) have demonstrated impressive performance on multimodal tasks through scaled architectures and extensive training. However, existing Mixture of Experts (MoE) approaches face challenges due to the asymmetry between visual and linguistic processing. Visual information is spatially complete, while language requires maintaining sequential context. As a result, MoE models struggle to balance modality-specific features and cross-modal interactions. Through systematic analysis, we observe that language experts in deeper layers progressively lose contextual grounding and rely more on parametric knowledge rather than utilizing the provided visual and linguistic information. To address this, we propose AsyMoE, a novel architecture that models this asymmetry using three specialized expert groups. We design intra-modality experts for modality-specific processing, hyperbolic inter-modality experts for hierarchical cross-modal interactions, and evidence-priority language experts to suppress parametric biases and maintain contextual grounding. Extensive experiments demonstrate that AsyMoE achieves 26.58% and 15.45% accuracy improvements over vanilla MoE and modality-specific MoE respectively, with 25.45% fewer activated parameters than dense models.

[Arxiv](https://arxiv.org/abs/2509.12715)