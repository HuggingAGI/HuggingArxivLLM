# IMPACT：屈折形态学探针跨复杂语型研究

发布时间：2025年06月30日

`LLM应用` `多语言处理` `形态学`

> IMPACT: Inflectional Morphology Probes Across Complex Typologies

# 摘要

> 大型语言模型（LLMs）在多语言基准测试中取得了显著进展，并越来越多地被用于生成和评估非英语语言的文本。然而，尽管LLMs能够生成流利的输出，但它们对这些语言的内在语言复杂性的真正理解程度，尤其是形态学方面，仍有待验证。为此，我们开发了IMPACT框架，这是一个专注于屈折形态学的合成生成评估工具，现已公开发布。该框架旨在评估LLM在阿拉伯语、俄语、芬兰语、土耳其语和希伯来语等五种形态丰富的语言中的表现。IMPACT包含多种单元测试案例，涵盖从基本动词屈折（如时态、数量、性别）到各语言独特特征（如阿拉伯语的反向性别一致性和芬兰语及土耳其语的元音和谐）等现象。我们对八种多语言LLM进行了评估，尽管这些模型在英语方面表现出色，但面对其他语言和不常见的形态模式时却显得力不从心，尤其在判断不正确语法示例时表现挣扎。此外，我们还发现链式思维和思考模型可能会对性能产生负面影响。我们的研究揭示了LLMs在处理语言复杂性方面的不足，为未来改进指明了方向。为了支持进一步的研究，我们已公开发布了IMPACT框架。

> Large Language Models (LLMs) have shown significant progress on various multilingual benchmarks and are increasingly used to generate and evaluate text in non-English languages. However, while they may produce fluent outputs, it remains unclear to what extent these models truly grasp the underlying linguistic complexity of those languages, particularly in morphology. To investigate this, we introduce IMPACT, a synthetically generated evaluation framework focused on inflectional morphology, which we publicly release, designed to evaluate LLM performance across five morphologically rich languages: Arabic, Russian, Finnish, Turkish, and Hebrew. IMPACT includes unit-test-style cases covering both shared and language-specific phenomena, from basic verb inflections (e.g., tense, number, gender) to unique features like Arabic's reverse gender agreement and vowel harmony in Finnish and Turkish. We assess eight multilingual LLMs that, despite strong English performance, struggle with other languages and uncommon morphological patterns, especially when judging ungrammatical examples. We also show that Chain of Thought and Thinking Models can degrade performance. Our work exposes gaps in LLMs' handling of linguistic complexity, pointing to clear room for improvement. To support further research, we publicly release the IMPACT framework.

[Arxiv](https://arxiv.org/abs/2506.23929)