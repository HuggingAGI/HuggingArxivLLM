# # 探究 LLM 内容审核中的关联偏见过敏感问题
LLM 的内容审核系统在检测敏感内容时可能会出现过度敏感的情况，这通常与模型对某些关联偏见的过度学习有关。本研究通过实证分析，揭示了这些偏见是如何影响内容审核决策的，并提出了改进审核策略的建议以减少误判。

发布时间：2025年05月29日

`LLM应用` `内容审核`

> Probing Association Biases in LLM Moderation Over-Sensitivity

# 摘要

> 大型语言模型在内容审核中广泛应用，但常出现将良性评论误判为有毒的情况，导致过度敏感。以往研究主要将此归因于攻击性词汇的存在，而我们发现了一个更深层次的原因：大型语言模型在隐性关联中存在系统性主题偏见。受认知心理学中隐性关联测试的启发，我们提出了主题关联分析，这是一种语义层面的方法，用于量化大型语言模型如何将某些主题与毒性联系起来。通过提示大型语言模型为误分类的良性评论生成自由联想的场景，并分析其主题放大程度，我们发现，尽管更先进的模型（如GPT-4 Turbo）整体误报率较低，但其主题刻板印象更为明显。这些偏见表明，大型语言模型不仅对明确的攻击性语言做出反应，还依赖于学习到的主题关联，从而影响其审核决策。我们的研究结果强调了在关键词过滤基础上进行改进的必要性，并揭示了导致大型语言模型过度敏感的潜在机制。

> Large Language Models are widely used for content moderation but often misclassify benign comments as toxic, leading to over-sensitivity. While previous research attributes this issue primarily to the presence of offensive terms, we reveal a potential cause beyond token level: LLMs exhibit systematic topic biases in their implicit associations. Inspired by cognitive psychology's implicit association tests, we introduce Topic Association Analysis, a semantic-level approach to quantify how LLMs associate certain topics with toxicity. By prompting LLMs to generate free-form scenario imagination for misclassified benign comments and analyzing their topic amplification levels, we find that more advanced models (e.g., GPT-4 Turbo) demonstrate stronger topic stereotype despite lower overall false positive rates. These biases suggest that LLMs do not merely react to explicit, offensive language but rely on learned topic associations, shaping their moderation decisions. Our findings highlight the need for refinement beyond keyword-based filtering, providing insights into the underlying mechanisms driving LLM over-sensitivity.

[Arxiv](https://arxiv.org/abs/2505.23914)