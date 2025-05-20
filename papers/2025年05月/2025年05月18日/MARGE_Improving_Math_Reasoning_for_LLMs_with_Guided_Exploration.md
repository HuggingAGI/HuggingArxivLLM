# MARGE：助力LLMs数学推理能力提升的引导式探索方法

发布时间：2025年05月18日

`LLM理论

理由：这篇论文探讨了如何通过MARGE方法提升大型语言模型的数学推理能力，属于对模型机制和优化的理论研究，因此归类为LLM理论。` `推理系统`

> MARGE: Improving Math Reasoning for LLMs with Guided Exploration

# 摘要

> 大型语言模型（LLMs）在数学推理方面潜力巨大，但其效果常受限于高质量查询的匮乏。为突破这一瓶颈，我们引入了	extbf{MARGE}（	extbf{Ma}th 	extbf{R}easoning with 	extbf{G}uided 	extbf{E}xploration），一种通过指导式探索提升数学推理能力的新方法。MARGE系统性地探索自生成解决方案中的中间推理状态，从而在推理过程中实现更充分的探索和更精准的信用分配。通过在多个基础模型和基准测试上的广泛实验，我们证明了MARGE显著提升了推理能力，且无需额外标注或训练价值模型。值得注意的是，MARGE不仅提高了单次推理的准确性，还增强了探索多样性，成功缓解了对齐方法中常见的权衡问题。这些结果充分证明了MARGE在提升数学推理能力方面的有效性，以及在扩展自生成训练数据潜力方面的优势。我们的代码和模型可在以下链接获取：\href{https://github.com/georgao35/MARGE}{此链接}。

> Large Language Models (LLMs) exhibit strong potential in mathematical reasoning, yet their effectiveness is often limited by a shortage of high-quality queries. This limitation necessitates scaling up computational responses through self-generated data, yet current methods struggle due to spurious correlated data caused by ineffective exploration across all reasoning stages. To address such challenge, we introduce \textbf{MARGE}: Improving \textbf{Ma}th \textbf{R}easoning with \textbf{G}uided \textbf{E}xploration, a novel method to address this issue and enhance mathematical reasoning through hit-guided exploration. MARGE systematically explores intermediate reasoning states derived from self-generated solutions, enabling adequate exploration and improved credit assignment throughout the reasoning process. Through extensive experiments across multiple backbone models and benchmarks, we demonstrate that MARGE significantly improves reasoning capabilities without requiring external annotations or training additional value models. Notably, MARGE improves both single-shot accuracy and exploration diversity, mitigating a common trade-off in alignment methods. These results demonstrate MARGE's effectiveness in enhancing mathematical reasoning capabilities and unlocking the potential of scaling self-generated training data. Our code and models are available at \href{https://github.com/georgao35/MARGE}{this link}.

[Arxiv](https://arxiv.org/abs/2505.12500)