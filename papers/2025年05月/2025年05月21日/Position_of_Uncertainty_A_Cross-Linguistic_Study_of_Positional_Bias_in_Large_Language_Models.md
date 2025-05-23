# 不确定性与位置：大型语言模型的跨语言偏差研究

发布时间：2025年05月21日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）的位置偏见及其与语言多样性之间的相互作用，属于对LLM内在特性和行为的理论研究。` `跨语言技术`

> Position of Uncertainty: A Cross-Linguistic Study of Positional Bias in Large Language Models

# 摘要

> 大型语言模型存在位置偏见，即对特定上下文位置信息的系统性忽略，但其与语言多样性之间的相互作用尚不明确。我们针对五种语系特征各异的语言（英语、俄语、德语、印地语、越南语）进行了跨语言研究，重点分析位置偏见与模型不确定性、句法及提示策略之间的相互作用。研究发现：(1) 位置偏见由模型驱动，且存在语言特异性差异，例如Qwen2.5-7B更倾向于后期位置，这挑战了早期标记偏见的假设；(2) 明确的位置引导（如正确上下文位于位置X）会降低多种语言的准确性，这表明提示工程实践的效果可能受到影响；(3) 将上下文与位置偏见对齐会增加熵值，但低熵值并不能准确预测模型性能；(4) 在自由语序语言（如印地语）中，大型语言模型对主语-动词-宾语的顺序有不同的主导影响。

> Large language models exhibit positional bias -- systematic neglect of information at specific context positions -- yet its interplay with linguistic diversity remains poorly understood. We present a cross-linguistic study across five typologically distinct languages (English, Russian, German, Hindi, Vietnamese), examining how positional bias interacts with model uncertainty, syntax, and prompting. Key findings: (1) Positional bias is model-driven, with language-specific variations -- Qwen2.5-7B favors late positions, challenging assumptions of early-token bias; (2) Explicit positional guidance (e.g., correct context is at position X) reduces accuracy across languages, undermining prompt-engineering practices; (3) Aligning context with positional bias increases entropy, yet minimal entropy does not predict accuracy. (4) We further uncover that LLMs differently impose dominant word order in free-word-order languages like Hindi.

[Arxiv](https://arxiv.org/abs/2505.16134)