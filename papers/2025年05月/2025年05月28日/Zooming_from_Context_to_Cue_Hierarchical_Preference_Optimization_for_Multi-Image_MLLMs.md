# 从上下文到提示的层级缩放视角：多图像MLLMs的层级偏好优化方法

发布时间：2025年05月28日

`LLM应用` `计算机视觉` `多模态学习`

> Zooming from Context to Cue: Hierarchical Preference Optimization for Multi-Image MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在处理单张图片时表现出色，但在面对多张图片时，往往因跨模态对齐问题而导致理解偏差，出现幻觉现象（如上下文遗漏、信息混杂和误解）。现有的直接偏好优化（DPO）方法仅关注输入序列中的单一图片参考，忽视了整体上下文的建模。为此，我们提出了上下文到线索的直接偏好优化（CcDPO），这是一个多层级的偏好优化框架，通过聚焦从序列上下文到局部细节的视觉线索，提升多图环境下的图片感知能力。CcDPO的主要特点包括：(i) 上下文层级优化：深入分析MLLMs在多图语境理解中的认知偏差，并引入一系列低成本的全局序列偏好，有效缓解偏差问题。(ii) 细节层级优化：借助区域定向的视觉提示和多模态偏好监督，引导模型关注精细的视觉细节。为了支持大规模优化，我们还构建了MultiScope-42k，一个自动化的高质量多层级偏好对数据集。实验结果表明，CcDPO显著减少了幻觉现象，并在单图和多图任务中均实现了性能的显著提升。

> Multi-modal Large Language Models (MLLMs) excel at single-image tasks but struggle with multi-image understanding due to cross-modal misalignment, leading to hallucinations (context omission, conflation, and misinterpretation). Existing methods using Direct Preference Optimization (DPO) constrain optimization to a solitary image reference within the input sequence, neglecting holistic context modeling. We propose Context-to-Cue Direct Preference Optimization (CcDPO), a multi-level preference optimization framework that enhances per-image perception in multi-image settings by zooming into visual clues -- from sequential context to local details. It features: (i) Context-Level Optimization : Re-evaluates cognitive biases underlying MLLMs' multi-image context comprehension and integrates a spectrum of low-cost global sequence preferences for bias mitigation. (ii) Needle-Level Optimization : Directs attention to fine-grained visual details through region-targeted visual prompts and multimodal preference supervision. To support scalable optimization, we also construct MultiScope-42k, an automatically generated dataset with high-quality multi-level preference pairs. Experiments show that CcDPO significantly reduces hallucinations and yields consistent performance gains across general single- and multi-image tasks.

[Arxiv](https://arxiv.org/abs/2505.22396)