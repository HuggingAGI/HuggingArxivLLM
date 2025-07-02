# 用于看似矛盾道德的自我修正的语篇启发式方法

发布时间：2025年07月01日

`LLM理论` `伦理学` `人工智能`

> Discourse Heuristics For Paradoxically Moral Self-Correction

# 摘要

> 道德自我修正作为一种有前途的方法出现，用于使大型语言模型（LLMs）的输出与人类道德价值观保持一致。然而，这一技术面临两大主要悖论：首先，尽管有实证和理论支持自我修正的有效性，但这种LLM能力仅在表面上运作；其次，尽管LLMs具备自我诊断其输出中不道德方面的功能，但它们在自我修正过程中难以识别这种道德不一致的原因。为了更好地理解和解决这些悖论，我们分析了旨在提高道德自我修正效果的微调语料库中的语篇构建，揭示了有效构建背后存在启发式方法。我们证明，道德自我修正依赖于反映启发式捷径的语篇构建，而这些启发式捷径的存在导致了在尝试同时增强自我修正和自我诊断能力时出现不一致。基于我们的发现，我们提出了一种解决方案，通过利用精选数据集的启发式方法来改进道德自我修正。我们还强调了这一能力在泛化方面的挑战，特别是在从具体语境学习和模型规模方面。

> Moral self-correction has emerged as a promising approach for aligning the output of Large Language Models (LLMs) with human moral values. However, moral self-correction techniques are subject to two primary paradoxes. First, despite empirical and theoretical evidence to support the effectiveness of self-correction, this LLM capability only operates at a superficial level. Second, while LLMs possess the capability of self-diagnosing immoral aspects of their output, they struggle to identify the cause of this moral inconsistency during their self-correction process. To better understand and address these paradoxes, we analyze the discourse constructions in fine-tuning corpora designed to enhance moral self-correction, uncovering the existence of the heuristics underlying effective constructions. We demonstrate that moral self-correction relies on discourse constructions that reflect heuristic shortcuts, and that the presence of these heuristic shortcuts during self-correction leads to inconsistency when attempting to enhance both self-correction and self-diagnosis capabilities jointly. Based on our findings, we propose a solution to improve moral self-correction by leveraging the heuristics of curated datasets. We also highlight the generalization challenges of this capability, particularly in terms of learning from situated context and model scales.

[Arxiv](https://arxiv.org/abs/2507.00985)