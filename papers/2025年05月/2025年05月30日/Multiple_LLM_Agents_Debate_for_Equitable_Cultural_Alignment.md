# 多个 LLM 代理就公平文化对齐展开辩论

发布时间：2025年05月30日

`Agent` `跨文化交流` `多智能体系统`

> Multiple LLM Agents Debate for Equitable Cultural Alignment

# 摘要

> 大型语言模型 (LLMs) 需要适应多样化的文化背景，以服务全球各地的不同社区。与以往专注于单一 LLM 和单轮方法的研究不同，我们提出通过多个 LLM 的互补优势来提升文化适应性。为此，我们设计了一个多智能体辩论框架，其中两个基于 LLM 的智能体围绕文化场景展开辩论，并共同制定最终决策。我们提出了两种变体：一种是 LLM 智能体仅进行辩论，另一种是它们在轮次中动态选择自我反思或辩论。我们使用包含 7 个开源 LLM（和 21 种 LLM 组合）的 NormAd-ETI 基准，在 75 个国家的社会礼仪规范上评估这些方法。实验结果表明，相比单一 LLM 基线，辩论方法在整体准确性和文化群体公平性方面均有显著提升。值得注意的是，多智能体辩论使相对较小的 LLM（7-9B 参数）能够达到与更大模型（27B 参数）相当的准确度。

> Large Language Models (LLMs) need to adapt their predictions to diverse cultural contexts to benefit diverse communities across the world. While previous efforts have focused on single-LLM, single-turn approaches, we propose to exploit the complementary strengths of multiple LLMs to promote cultural adaptability. We introduce a Multi-Agent Debate framework, where two LLM-based agents debate over a cultural scenario and collaboratively reach a final decision. We propose two variants: one where either LLM agents exclusively debate and another where they dynamically choose between self-reflection and debate during their turns. We evaluate these approaches on 7 open-weight LLMs (and 21 LLM combinations) using the NormAd-ETI benchmark for social etiquette norms in 75 countries. Experiments show that debate improves both overall accuracy and cultural group parity over single-LLM baselines. Notably, multi-agent debate enables relatively small LLMs (7-9B) to achieve accuracies comparable to that of a much larger model (27B parameters).

[Arxiv](https://arxiv.org/abs/2505.24671)