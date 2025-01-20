# 注意力引导的自我反思：大型语言模型中的零-shot幻觉检测

发布时间：2025年01月17日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLMs）的幻觉问题，并提出了一种新的方法来检测和减少幻觉。论文的核心在于提出了一种理论上的改进方法（AGSER），并通过实验验证其有效性。因此，这篇论文更偏向于LLM理论，因为它涉及对LLM内部机制的理解和改进，而不是具体的应用或代理（Agent）的实现。` `人工智能`

> Attention-guided Self-reflection for Zero-shot Hallucination Detection in Large Language Models

# 摘要

> 幻觉是LLMs有效应用的一大障碍。本文提出了一种新颖的注意力引导自我反思（AGSER）方法，用于LLMs的零-shot幻觉检测。AGSER通过注意力贡献将查询分为注意力查询和非注意力查询，并分别处理，计算生成响应与原始答案的一致性分数，其差异作为幻觉估计器。AGSER不仅高效检测幻觉，还大幅降低计算复杂度，仅需三次LLM推理和两组token。我们在三个幻觉基准上对四种主流LLMs进行了大量实验，结果表明AGSER在零-shot幻觉检测中显著优于现有方法。

> Hallucination has emerged as a significant barrier to the effective application of Large Language Models (LLMs). In this work, we introduce a novel Attention-Guided SElf-Reflection (AGSER) approach for zero-shot hallucination detection in LLMs. The AGSER method utilizes attention contributions to categorize the input query into attentive and non-attentive queries. Each query is then processed separately through the LLMs, allowing us to compute consistency scores between the generated responses and the original answer. The difference between the two consistency scores serves as a hallucination estimator. In addition to its efficacy in detecting hallucinations, AGSER notably reduces computational complexity, requiring only three passes through the LLM and utilizing two sets of tokens. We have conducted extensive experiments with four widely-used LLMs across three different hallucination benchmarks, demonstrating that our approach significantly outperforms existing methods in zero-shot hallucination detection.

[Arxiv](https://arxiv.org/abs/2501.09997)