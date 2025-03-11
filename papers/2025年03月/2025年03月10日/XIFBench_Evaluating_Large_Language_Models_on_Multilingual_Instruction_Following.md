# XIFBench：评测大型语言模型的跨语言指令执行能力

发布时间：2025年03月10日

`LLM应用` `多语言技术`

> XIFBench: Evaluating Large Language Models on Multilingual Instruction Following

# 摘要

> 大型语言模型（LLMs）在多种应用中展现了卓越的指令遵循能力。然而，它们在多语言设置中的表现仍不明确，现有评估缺乏细致的约束分析。我们引入XIFBench，这是一个全面的基于约束的基准测试，用于评估LLMs的多语言指令遵循能力，包含五个约束类别的新分类法和涵盖六种语言、不同资源水平的465个平行指令。为确保跨语言评估的一致性，我们开发了一个基于需求的协议，利用英语需求作为语义锚点。这些需求随后用于验证跨语言的翻译。对各种LLMs的广泛实验揭示了资源水平下的指令遵循性能存在显著差异，并确定了关键影响因素，如约束类别、指令复杂性和文化特异性。

> Large Language Models (LLMs) have demonstrated remarkable instruction-following capabilities across various applications. However, their performance in multilingual settings remains poorly understood, as existing evaluations lack fine-grained constraint analysis. We introduce XIFBench, a comprehensive constraint-based benchmark for assessing multilingual instruction-following abilities of LLMs, featuring a novel taxonomy of five constraint categories and 465 parallel instructions across six languages spanning different resource levels. To ensure consistent cross-lingual evaluation, we develop a requirement-based protocol that leverages English requirements as semantic anchors. These requirements are then used to validate the translations across languages. Extensive experiments with various LLMs reveal notable variations in instruction-following performance across resource levels, identifying key influencing factors such as constraint categories, instruction complexity, and cultural specificity.

[Arxiv](https://arxiv.org/abs/2503.07539)