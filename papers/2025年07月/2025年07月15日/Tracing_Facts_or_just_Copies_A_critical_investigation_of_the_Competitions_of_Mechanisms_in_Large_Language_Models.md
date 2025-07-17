# 追踪事实还是仅仅复制？深入探讨大型语言模型中的机制竞争

发布时间：2025年07月15日

`LLM理论` `人工智能`

> Tracing Facts or just Copies? A critical investigation of the Competitions of Mechanisms in Large Language Models

# 摘要

> 本文提出了一项可重复性研究，探讨大型语言模型（LLMs）在处理事实与反事实信息时的表现，特别关注注意力头的作用。我们试图复制并调和Ortu等人、Yu、Merullo以及Pavlick和McDougall等人近期的研究成果，这些研究通过机制可解释性工具调查了模型学习的事实与矛盾上下文信息之间的竞争。本研究具体分析了注意力头强度与事实输出比例之间的关系，评估了关于注意力头抑制机制的相互竞争的假设，并探讨了这些注意力模式的领域特异性。我们的研究发现表明，促进事实输出的注意力头是通过通用的复制抑制，而非选择性反事实抑制来实现的，因为加强它们也会抑制正确的事实。此外，我们展示了注意力头的行为是领域依赖的，更大的模型表现出更专业和类别敏感的模式。

> This paper presents a reproducibility study examining how Large Language Models (LLMs) manage competing factual and counterfactual information, focusing on the role of attention heads in this process. We attempt to reproduce and reconcile findings from three recent studies by Ortu et al., Yu, Merullo, and Pavlick and McDougall et al. that investigate the competition between model-learned facts and contradictory context information through Mechanistic Interpretability tools. Our study specifically examines the relationship between attention head strength and factual output ratios, evaluates competing hypotheses about attention heads' suppression mechanisms, and investigates the domain specificity of these attention patterns. Our findings suggest that attention heads promoting factual output do so via general copy suppression rather than selective counterfactual suppression, as strengthening them can also inhibit correct facts. Additionally, we show that attention head behavior is domain-dependent, with larger models exhibiting more specialized and category-sensitive patterns.

[Arxiv](https://arxiv.org/abs/2507.11809)