# # TruthPrInt：通过潜在真实信息引导的预干预，有效缓解 LVLM 对象幻觉

发布时间：2025年03月13日

`LLM理论

理由：这篇论文探讨了大型视觉语言模型（LVLMs）中的对象幻觉（OH）问题，并深入分析了模型内部状态与幻觉之间的关系。研究者提出了新的方法（如TruthPrInt和ComnHallu框架），旨在改进模型的可信度。这些工作属于模型理论层面的分析和改进，因此归类为LLM理论。` `视觉语言模型` `可信度评估`

> TruthPrInt: Mitigating LVLM Object Hallucination Via Latent Truthful-Guided Pre-Intervention

# 摘要

> 对象幻觉（OH）是大型视觉语言模型（LVLMs）中可信度面临的主要挑战之一。近期研究表明，大型语言模型（LLMs）的内部状态（如隐藏状态）能够反映生成响应的“整体真实性”。然而，关于LVLMs内部状态的工作机制及其是否可以作为“逐标记”的幻觉指标，仍是一个值得探索的重要课题，这将为缓解OH问题提供关键思路。在本文中，我们首先深入探究了LVLM内部状态与OH问题之间的关系，发现：（1）LVLM内部状态能够作为幻觉行为的高特异性逐标记指标；（2）不同LVLMs在共同的潜在子空间中编码了普遍的幻觉模式，表明存在多种LVLM共享的“通用真实方向”。基于这些发现，我们提出了Truthful-Guided Pre-Intervention（TruthPrInt）方法，该方法通过首先学习LVLM解码的真实方向，然后在解码过程中应用真实引导的推理时间干预。此外，我们还提出了ComnHallu框架，通过构建和对齐幻觉潜在子空间来增强跨LVLM和跨数据的幻觉检测的迁移能力。我们在涵盖 popular LVLMs 和 OH 基准测试的广泛实验设置中评估了TruthPrInt，包括域内和域外场景。实验结果表明，TruthPrInt显著优于现有最优方法。相关代码将在 https://github.com/jinhaoduan/TruthPrInt 上提供。

> Object Hallucination (OH) has been acknowledged as one of the major trustworthy challenges in Large Vision-Language Models (LVLMs). Recent advancements in Large Language Models (LLMs) indicate that internal states, such as hidden states, encode the "overall truthfulness" of generated responses. However, it remains under-explored how internal states in LVLMs function and whether they could serve as "per-token" hallucination indicators, which is essential for mitigating OH. In this paper, we first conduct an in-depth exploration of LVLM internal states in relation to OH issues and discover that (1) LVLM internal states are high-specificity per-token indicators of hallucination behaviors. Moreover, (2) different LVLMs encode universal patterns of hallucinations in common latent subspaces, indicating that there exist "generic truthful directions" shared by various LVLMs. Based on these discoveries, we propose Truthful-Guided Pre-Intervention (TruthPrInt) that first learns the truthful direction of LVLM decoding and then applies truthful-guided inference-time intervention during LVLM decoding. We further propose ComnHallu to enhance both cross-LVLM and cross-data hallucination detection transferability by constructing and aligning hallucination latent subspaces. We evaluate TruthPrInt in extensive experimental settings, including in-domain and out-of-domain scenarios, over popular LVLMs and OH benchmarks. Experimental results indicate that TruthPrInt significantly outperforms state-of-the-art methods. Codes will be available at https://github.com/jinhaoduan/TruthPrInt.

[Arxiv](https://arxiv.org/abs/2503.10602)