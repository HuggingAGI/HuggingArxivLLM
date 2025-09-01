# # 锚定无锚定内容：一种量化多模态大型语言模型幻觉的谱图框架

发布时间：2025年08月26日

`LLM理论` `基础理论`

> Grounding the Ungrounded: A Spectral-Graph Framework for Quantifying Hallucinations in multimodal LLMs

# 摘要

> 大型语言模型（LLMs）的幻觉问题始终是可信AI的核心障碍，尤其在医疗、法律和金融等高风险多模态领域。现有评估技术多依赖定性基准测试或临时经验缓解等启发式方法，既缺乏系统性量化手段，也无法提供可落地的理论保障。这种局限导致我们在理解幻觉的产生机制、传播路径及跨模态相互作用时存在关键盲区。我们（据我们所知）首次提出基于扩散动力学的严格信息几何框架，用于量化多模态大型语言模型（MLLMs）的幻觉问题，推动该领域从定性检测迈向数学化的精准测量。该方法将MLLM输出表示为多模态图拉普拉斯算子的谱嵌入，将真相与不一致性之间的流形间隙定义为语义失真，进而将多模态幻觉能量的紧瑞利-里兹界表示为时间依赖温度曲线的泛函。通过再生核希尔伯特空间（RKHS）嵌入中的本征模分解，我们的框架可生成模态感知、理论可解释的指标，精准捕捉幻觉随时间和输入提示通过温度退火的演变过程。这项研究为幻觉的量化与界定奠定了系统性基础，将其从定性风险转化为可分析、可调控的具体现象。

> Hallucinations in large language models (LLMs) remain a fundamental obstacle to trustworthy AI, particularly in high-stakes multimodal domains such as medicine, law, and finance. Existing evaluation techniques are largely heuristic -- anchored in qualitative benchmarking or ad-hoc empirical mitigation -- providing neither principled quantification nor actionable theoretical guarantees. This gap leaves a critical blind spot in understanding how hallucinations arise, propagate, and interact across modalities. We introduce the first (to our knowledge) rigorous information geometric framework in diffusion dynamics for quantifying hallucinations in multimodal LLMs (MLLMs), advancing the field from qualitative detection to mathematically grounded measurement. Our approach represents MLLM outputs as the spectral embeddings over multimodal graph Laplacians and characterizes the manifold gaps of truth vs inconsistencies as the semantic distortion, enabling the tight Rayleigh--Ritz bounds on the multimodal hallucination energy as a functional of time-dependent temperature profiles. By leveraging eigenmode decompositions in Reproducing Kernel Hilbert Space (RKHS) embeddings, our framework delivers modality-aware, theoretically interpretable metrics that capture the evolution of hallucinations across time and input prompts through temperature annealing. This work establishes a principled foundation for quantifying and bounding hallucinations, transforming them from a qualitative risk to a tractable, analyzable phenomenon.

[Arxiv](https://arxiv.org/abs/2508.19366)