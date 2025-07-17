# 简化即是绝对化：简化语言如何降低LLM生成定义中的词义感知度

发布时间：2025年07月16日

`LLM应用`

> Simplifications are Absolutists: How Simplified Language Reduces Word Sense Awareness in LLM-Generated Definitions

# 摘要

> 大型语言模型（LLMs）能够为任何语境提供精准的单词定义和解释，但在不同目标群体中，定义的范围会有所调整，尤其是针对儿童和语言学习者。这一点在同音词（具有多种含义的单词）中尤为重要，因为过度简化可能导致关键含义的遗漏，从而引发信息丢失，误导依赖LLM输出的用户。我们研究了简化对同音词定义质量的影响，针对普通组、简化组和ELI5组三个目标群体进行了分析。通过使用两个跨多语言的新型评估数据集，我们对DeepSeek v3、Llama 4 Maverick、Qwen3-30B A3B、GPT-4o mini和Llama 3.1 8B进行了测试，采用了LLM作为评估者和人工标注的方法。结果显示，简化因忽视多义性而导致定义完整性的严重下降，增加了误解的风险。通过直接偏好优化对Llama 3.1 8B进行微调，显著提升了所有提示类型下的同音词回应质量。这些发现强调了在教育型NLP中平衡简化与完整性的必要性，以确保为所有学习者提供可靠且语境感知的定义。

> Large Language Models (LLMs) can provide accurate word definitions and explanations for any context. However, the scope of the definition changes for different target groups, like children or language learners. This is especially relevant for homonyms, words with multiple meanings, where oversimplification might risk information loss by omitting key senses, potentially misleading users who trust LLM outputs. We investigate how simplification impacts homonym definition quality across three target groups: Normal, Simple, and ELI5. Using two novel evaluation datasets spanning multiple languages, we test DeepSeek v3, Llama 4 Maverick, Qwen3-30B A3B, GPT-4o mini, and Llama 3.1 8B via LLM-as-Judge and human annotations. Our results show that simplification drastically degrades definition completeness by neglecting polysemy, increasing the risk of misunderstanding. Fine-tuning Llama 3.1 8B with Direct Preference Optimization substantially improves homonym response quality across all prompt types. These findings highlight the need to balance simplicity and completeness in educational NLP to ensure reliable, context-aware definitions for all learners.

[Arxiv](https://arxiv.org/abs/2507.11981)