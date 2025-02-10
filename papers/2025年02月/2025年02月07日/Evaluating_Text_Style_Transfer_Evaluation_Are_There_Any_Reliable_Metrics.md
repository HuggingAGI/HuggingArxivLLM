# # 评估文本风格迁移：是否存在可靠的评估指标？

发布时间：2025年02月07日

`LLM应用`

> Evaluating Text Style Transfer Evaluation: Are There Any Reliable Metrics?

# 摘要

> 文本风格迁移（TST）旨在在保持原文内容的同时，将文本转换为特定风格。评估 TST 输出是一个多维度的挑战，需要从风格迁移的准确性、内容的保留度以及自然度三个方面进行考量。尽管人类评估是理想选择，但成本较高，与其他自然语言处理（NLP）任务类似。然而，与机器翻译或摘要等任务相比，针对 TST 的自动指标并未受到同等关注。本文从更广泛的 NLP 任务中选取现有和新颖指标，重点评估 TST 在情感迁移和去毒化两种流行子任务中的表现，涵盖英语、印地语和孟加拉语的多语言场景。通过与人工判断的相关性进行元评估，我们验证了这些指标在单独使用和组合使用时的有效性。此外，我们还探索了大语言模型（LLMs）作为 TST 评估工具的潜力。研究发现表明，某些先进的 NLP 指标和实验-混合技术比现有 TST 指标更具优势，能够提供更准确、一致且可重复的 TST 评估结果。

> Text Style Transfer (TST) is the task of transforming a text to reflect a particular style while preserving its original content. Evaluating TST outputs is a multidimensional challenge, requiring the assessment of style transfer accuracy, content preservation, and naturalness. Using human evaluation is ideal but costly, same as in other natural language processing (NLP) tasks, however, automatic metrics for TST have not received as much attention as metrics for, e.g., machine translation or summarization. In this paper, we examine both set of existing and novel metrics from broader NLP tasks for TST evaluation, focusing on two popular subtasks-sentiment transfer and detoxification-in a multilingual context comprising English, Hindi, and Bengali. By conducting meta-evaluation through correlation with human judgments, we demonstrate the effectiveness of these metrics when used individually and in ensembles. Additionally, we investigate the potential of Large Language Models (LLMs) as tools for TST evaluation. Our findings highlight that certain advanced NLP metrics and experimental-hybrid-techniques, provide better insights than existing TST metrics for delivering more accurate, consistent, and reproducible TST evaluations.

[Arxiv](https://arxiv.org/abs/2502.04718)