# 大型语言模型的位置脆性：偏移效应如何重塑我们对记忆风险的理解

发布时间：2025年05月19日

`LLM理论` `大型语言模型`

> Positional Fragility in LLMs: How Offset Effects Reshape Our Understanding of Memorization Risks

# 摘要

> 大型语言模型的记忆特性可能引发版权风险。为系统评估这一问题，我们从零开始预训练了三种规模的语言模型（10亿/30亿/80亿参数），使用了8300亿个令牌的数据集，其中包括网络数据和公共领域书籍，后者被用于模拟受版权保护的内容，且长度远超先前研究。我们发现了一个显著现象——偏移效应，其特征为：(1) 逐字记忆最易被上下文窗口起始处的简短前缀触发，而随着前缀长度增加，记忆强度反而降低；(2) 当前缀偏离上下文窗口起始位置时，逐字回忆能力急剧下降。这一现象源于模型的位置脆性：它们过度依赖上下文窗口起始位置的令牌作为检索锚点，因此对任何微小偏移都异常敏感。当模型无法检索记忆内容时，通常会生成质量下降的文本。通过将敏感数据更深地嵌入上下文窗口，我们成功抑制了可提取记忆和文本退化现象。我们的研究揭示，位置偏移是评估记忆风险的关键维度，此前研究未能充分关注这一点。

> Large language models are known to memorize parts of their training data, posing risk of copyright violations. To systematically examine this risk, we pretrain language models (1B/3B/8B) from scratch on 83B tokens, mixing web-scale data with public domain books used to simulate copyrighted content at controlled frequencies at lengths at least ten times longer than prior work. We thereby identified the offset effect, a phenomenon characterized by two key findings: (1) verbatim memorization is most strongly triggered by short prefixes drawn from the beginning of the context window, with memorization decreasing counterintuitively as prefix length increases; and (2) a sharp decline in verbatim recall when prefix begins offset from the initial tokens of the context window. We attribute this to positional fragility: models rely disproportionately on the earliest tokens in their context window as retrieval anchors, making them sensitive to even slight shifts. We further observe that when the model fails to retrieve memorized content, it often produces degenerated text. Leveraging these findings, we show that shifting sensitive data deeper into the context window suppresses both extractable memorization and degeneration. Our results suggest that positional offset is a critical and previously overlooked axis for evaluating memorization risks, since prior work implicitly assumed uniformity by probing only from the beginning of training sequences.

[Arxiv](https://arxiv.org/abs/2505.13171)