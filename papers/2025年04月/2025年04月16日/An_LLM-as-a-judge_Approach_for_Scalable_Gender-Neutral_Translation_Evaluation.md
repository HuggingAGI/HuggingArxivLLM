# LLM作为评估者：一种用于大规模中立性别翻译评估的方法

发布时间：2025年04月16日

`LLM应用` `机器翻译`

> An LLM-as-a-judge Approach for Scalable Gender-Neutral Translation Evaluation

# 摘要

> 性别中立翻译（GNT）旨在避免在源文本未明确性别信息时表达人类指代的性别。自动评估GNT极具挑战性，现有解决方案仅限于单语种分类器，这些方案存在不足：它们忽视源句内容，且需专用数据和微调才能扩展至新语言。本研究通过探索将大型语言模型（LLMs）作为GNT评估工具，解决上述局限。具体而言，我们采用两种提示方法：一种是LLMs仅生成句子级别评估，另一种则先进行详细短语级别注释，再做句子级别判断，类似于链式思维方法。通过在多种语言及五个模型（含开源与专有模型）上进行广泛实验，我们证实LLMs可有效担任GNT评估角色。更重要的是，我们在句子级别评估前加入短语级别注释提示，显著提升了所有模型的准确性，为现有方案提供了更优且更具扩展性的替代方案。

> Gender-neutral translation (GNT) aims to avoid expressing the gender of human referents when the source text lacks explicit cues about the gender of those referents. Evaluating GNT automatically is particularly challenging, with current solutions being limited to monolingual classifiers. Such solutions are not ideal because they do not factor in the source sentence and require dedicated data and fine-tuning to scale to new languages. In this work, we address such limitations by investigating the use of large language models (LLMs) as evaluators of GNT. Specifically, we explore two prompting approaches: one in which LLMs generate sentence-level assessments only, and another, akin to a chain-of-thought approach, where they first produce detailed phrase-level annotations before a sentence-level judgment. Through extensive experiments on multiple languages with five models, both open and proprietary, we show that LLMs can serve as evaluators of GNT. Moreover, we find that prompting for phrase-level annotations before sentence-level assessments consistently improves the accuracy of all models, providing a better and more scalable alternative to current solutions.

[Arxiv](https://arxiv.org/abs/2504.11934)