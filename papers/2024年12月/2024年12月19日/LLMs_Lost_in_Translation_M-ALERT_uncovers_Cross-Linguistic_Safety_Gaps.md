# LLMs 在翻译时迷失方向：M-ALERT 揭示了跨语言的安全差距

发布时间：2024年12月19日

`LLM应用` `语言模型` `安全性评估`

> LLMs Lost in Translation: M-ALERT uncovers Cross-Linguistic Safety Gaps

# 摘要

> 构建涵盖多种语言的安全大型语言模型（LLMs）对于保障安全访问和语言的多样性极为关键。为此，我们推出了 M-ALERT，这一多语言基准用于评估英语、法语、德语、意大利语和西班牙语这五种语言中 LLMs 的安全性。M-ALERT 每种语言都有 15000 个高质量提示，总计 75000 个，遵循了详尽的 ALERT 分类法。我们针对 10 个前沿的 LLMs 展开的大量实验凸显了特定语言安全性分析的重要性，表明模型在不同语言和类别中的安全性往往存在显著的不一致。比如，Llama3.2 在意大利语的犯罪_税收类别中表现出高度不安全，但在其他语言中却是安全的。在所有模型中都能观察到类似的差别。相反，某些类别，像物质_大麻和犯罪_宣传，在所有模型和语言中都会持续引发不安全的响应。这些发现强调了 LLMs 中需要强有力的多语言安全实践，以确保在不同的用户群体中能够安全且负责地使用。

> Building safe Large Language Models (LLMs) across multiple languages is essential in ensuring both safe access and linguistic diversity. To this end, we introduce M-ALERT, a multilingual benchmark that evaluates the safety of LLMs in five languages: English, French, German, Italian, and Spanish. M-ALERT includes 15k high-quality prompts per language, totaling 75k, following the detailed ALERT taxonomy. Our extensive experiments on 10 state-of-the-art LLMs highlight the importance of language-specific safety analysis, revealing that models often exhibit significant inconsistencies in safety across languages and categories. For instance, Llama3.2 shows high unsafety in the category crime_tax for Italian but remains safe in other languages. Similar differences can be observed across all models. In contrast, certain categories, such as substance_cannabis and crime_propaganda, consistently trigger unsafe responses across models and languages. These findings underscore the need for robust multilingual safety practices in LLMs to ensure safe and responsible usage across diverse user communities.

[Arxiv](https://arxiv.org/abs/2412.15035)