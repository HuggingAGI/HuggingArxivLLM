# LLM评估与答案生成的集成框架

发布时间：2025年09月24日

`LLM应用` `基础理论`

> Integrated Framework for LLM Evaluation with Answer Generation

# 摘要

> 大型语言模型的可靠评估是确保其在实际场景中适用的关键。传统基于基准的评估方法往往依赖固定参考答案，难以捕捉生成响应中重要的定性特征。为此，我们提出了名为“自优化描述性评估与专家驱动诊断”（SPEED）的综合评估框架，该框架借助专业功能专家对模型输出开展全面的描述性分析。与传统方法不同，SPEED主动纳入多维度专家反馈，涵盖幻觉检测、毒性评估及词汇语境适配性等方面。实验结果显示，SPEED在不同领域和数据集上均展现出稳健且一致的评估表现。此外，由于采用相对精简的专家模型，SPEED比大规模评估器具有更高的资源效率。这些发现表明，SPEED大幅提升了LLM评估的公平性和可解释性，为现有评估方法提供了极具潜力的替代方案。

> Reliable evaluation of large language models is essential to ensure their applicability in practical scenarios. Traditional benchmark-based evaluation methods often rely on fixed reference answers, limiting their ability to capture important qualitative aspects of generated responses. To address these shortcomings, we propose an integrated evaluation framework called \textit{self-refining descriptive evaluation with expert-driven diagnostics}, SPEED, which utilizes specialized functional experts to perform comprehensive, descriptive analyses of model outputs. Unlike conventional approaches, SPEED actively incorporates expert feedback across multiple dimensions, including hallucination detection, toxicity assessment, and lexical-contextual appropriateness. Experimental results demonstrate that SPEED achieves robust and consistent evaluation performance across diverse domains and datasets. Additionally, by employing relatively compact expert models, SPEED demonstrates superior resource efficiency compared to larger-scale evaluators. These findings illustrate that SPEED significantly enhances fairness and interpretability in LLM evaluations, offering a promising alternative to existing evaluation methodologies.

[Arxiv](https://arxiv.org/abs/2509.20097)