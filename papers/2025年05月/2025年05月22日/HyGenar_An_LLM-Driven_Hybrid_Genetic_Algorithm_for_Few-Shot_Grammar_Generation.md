# HyGenar：LLM驱动的混合遗传算法，专为小样本语法生成而设计。

发布时间：2025年05月22日

`LLM应用` `代码生成`

> HyGenar: An LLM-Driven Hybrid Genetic Algorithm for Few-Shot Grammar Generation

# 摘要

> 语法在自然语言处理和文本/代码生成中起着至关重要的作用，它不仅定义了语法规则，还为解析器的创建和结构化输出提供了指导。尽管大型语言模型（LLMs）在各个领域都表现出色，但它们在语法推理和生成方面的潜力尚未得到充分挖掘。本文聚焦于提升LLMs在少样本语法生成任务中的能力，即从少量正反例中推断语法并以巴科斯-诺尔范式（Backus-Naur Form）形式生成。为此，我们构建了一个包含540个结构化语法生成挑战的新数据集，设计了6个评估指标，并对8种不同LLMs进行了全面评估。研究结果表明，现有LLMs在语法生成方面仍有较大的提升空间。针对这一问题，我们提出了一种基于LLM的混合遗传算法——HyGenar，以优化语法生成过程。HyGenar在提升生成语法的句法和语义正确性方面取得了显著成效，为LLMs在语法生成任务中的应用开辟了新的可能性。

> Grammar plays a critical role in natural language processing and text/code generation by enabling the definition of syntax, the creation of parsers, and guiding structured outputs. Although large language models (LLMs) demonstrate impressive capabilities across domains, their ability to infer and generate grammars has not yet been thoroughly explored. In this paper, we aim to study and improve the ability of LLMs for few-shot grammar generation, where grammars are inferred from sets of a small number of positive and negative examples and generated in Backus-Naur Form. To explore this, we introduced a novel dataset comprising 540 structured grammar generation challenges, devised 6 metrics, and evaluated 8 various LLMs against it. Our findings reveal that existing LLMs perform sub-optimally in grammar generation. To address this, we propose an LLM-driven hybrid genetic algorithm, namely HyGenar, to optimize grammar generation. HyGenar achieves substantial improvements in both the syntactic and semantic correctness of generated grammars across LLMs.

[Arxiv](https://arxiv.org/abs/2505.16978)