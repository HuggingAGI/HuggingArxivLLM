# SafeVid：致力于安全对齐的视频大型多模态模型

发布时间：2025年05月17日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于视频多模态模型（VLMMs）的安全性问题，通过构建特定的数据集和使用直接偏好优化（DPO）来提升模型的安全性。因此，它属于LLM应用类别。`

> SafeVid: Toward Safety Aligned Video Large Multimodal Models

# 摘要

> 视频大型多模态模型（VLMMs）的快速发展带来了显著的安全挑战，尤其是模型泛化不匹配问题，即静态安全对齐无法有效应用于动态视频环境。为此，我们提出了 SafeVid 框架，旨在为 VLMMs 注入视频特定的安全原则。SafeVid 的独特之处在于，它通过详细的文字视频描述作为桥梁，成功将强大的文本安全对齐能力迁移到视频领域，从而实现基于 LLM 的规则驱动安全推理。这一目标通过以下闭环系统实现：1）构建包含 35 万对的 SafeVid-350K 视频特定安全偏好数据集；2）利用直接偏好优化（DPO）对 VLMMs 进行定向对齐；3）通过全新基准 SafeVidBench 进行全面评估。与 SafeVid-350K 对齐后，VLMM 的安全性显著提升，例如 LLaVA-NeXT-Video 在 SafeVidBench 上的性能提升了高达 42.39%。SafeVid 提供了关键资源和系统化方法，证明了通过文本描述作为中介进行安全推理能显著提高 VLMMs 的安全对齐能力。我们已将 SafeVid-350K 数据集（https://huggingface.co/datasets/yxwang/SafeVid-350K）公开发布。

> As Video Large Multimodal Models (VLMMs) rapidly advance, their inherent complexity introduces significant safety challenges, particularly the issue of mismatched generalization where static safety alignments fail to transfer to dynamic video contexts. We introduce SafeVid, a framework designed to instill video-specific safety principles in VLMMs. SafeVid uniquely transfers robust textual safety alignment capabilities to the video domain by employing detailed textual video descriptions as an interpretive bridge, facilitating LLM-based rule-driven safety reasoning. This is achieved through a closed-loop system comprising: 1) generation of SafeVid-350K, a novel 350,000-pair video-specific safety preference dataset; 2) targeted alignment of VLMMs using Direct Preference Optimization (DPO); and 3) comprehensive evaluation via our new SafeVidBench benchmark. Alignment with SafeVid-350K significantly enhances VLMM safety, with models like LLaVA-NeXT-Video demonstrating substantial improvements (e.g., up to 42.39%) on SafeVidBench. SafeVid provides critical resources and a structured approach, demonstrating that leveraging textual descriptions as a conduit for safety reasoning markedly improves the safety alignment of VLMMs. We have made SafeVid-350K dataset (https://huggingface.co/datasets/yxwang/SafeVid-350K) publicly available.

[Arxiv](https://arxiv.org/abs/2505.11926)