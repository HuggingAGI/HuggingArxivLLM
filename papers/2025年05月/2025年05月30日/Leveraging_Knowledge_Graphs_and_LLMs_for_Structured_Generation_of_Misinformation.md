# # 利用知识图谱与大型语言模型构建结构化错误信息

发布时间：2025年05月30日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型生成虚假信息，并分析了这些模型在检测虚假信息方面的表现。它专注于LLMs的应用，特别是生成和检测方面，因此归类为LLM应用。` `虚假信息` `知识图谱`

> Leveraging Knowledge Graphs and LLMs for Structured Generation of Misinformation

# 摘要

> 虚假信息的迅速传播，尤其是在生成式AI的推动下，正给社会带来前所未有的威胁，影响公众舆论、民主稳定乃至国家安全。为应对这一挑战，我们需要探索更结构化、可扩展的虚假信息生成方法。本文提出了一种基于知识图谱（KGs）的创新方法，系统性生成虚假三元组。通过分析KGs的结构特性，如实体间距离及其谓词关系，我们识别出看似合理但实际上是虚假的关系。这些三元组随后被用于指导大型语言模型（LLMs）生成具有不同可信度级别的误导信息。通过利用结构化的语义关系，我们的方法生成的虚假信息极具欺骗性，且仅依赖公开可用的知识图谱（如WikiGraphs）。此外，我们还深入探究了LLMs在区分真实信息与人工生成虚假信息方面的表现。分析结果揭示了现有基于LLM的检测方法存在明显局限性，凸显了改进检测策略和深入研究生成模型内在偏见的必要性。

> The rapid spread of misinformation, further amplified by recent advances in generative AI, poses significant threats to society, impacting public opinion, democratic stability, and national security. Understanding and proactively assessing these threats requires exploring methodologies that enable structured and scalable misinformation generation. In this paper, we propose a novel approach that leverages knowledge graphs (KGs) as structured semantic resources to systematically generate fake triplets. By analyzing the structural properties of KGs, such as the distance between entities and their predicates, we identify plausibly false relationships. These triplets are then used to guide large language models (LLMs) in generating misinformation statements with varying degrees of credibility. By utilizing structured semantic relationships, our deterministic approach produces misinformation inherently challenging for humans to detect, drawing exclusively upon publicly available KGs (e.g., WikiGraphs).
  Additionally, we investigate the effectiveness of LLMs in distinguishing between genuine and artificially generated misinformation. Our analysis highlights significant limitations in current LLM-based detection methods, underscoring the necessity for enhanced detection strategies and a deeper exploration of inherent biases in generative models.

[Arxiv](https://arxiv.org/abs/2505.24479)