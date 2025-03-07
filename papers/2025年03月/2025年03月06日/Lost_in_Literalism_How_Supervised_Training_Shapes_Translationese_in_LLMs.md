# 字面主义迷途：监督式训练如何塑造LLMs的翻译腔

发布时间：2025年03月06日

`LLM应用` `机器翻译`

> Lost in Literalism: How Supervised Training Shapes Translationese in LLMs

# 摘要

> 大型语言模型（LLMs）在机器翻译领域表现卓越，但在多种语言应用中仍面临直译化（translationese）的挑战。尽管LLMs基于大规模自然语料库预训练，但监督微调（SFT）过程中引入的偏差导致直译化错误和不自然翻译频发。本研究系统评估了LLMs生成翻译中的直译化现象，并深入探究其在监督训练中的根源。我们提出优化黄金参考和过滤不自然训练实例等方法，实证表明这些方法显著降低了直译化现象，提升了翻译自然度，人工评估和自动指标均证实了这一结论。研究结果强调了在训练过程中进行有意识调整的重要性，为更流畅且符合目标语言习惯的翻译提供了新思路。我们在https://github.com/yafuly/LLM_Translationese上公开了相关数据和代码。

> Large language models (LLMs) have achieved remarkable success in machine translation, demonstrating impressive performance across diverse languages. However, translationese, characterized by overly literal and unnatural translations, remains a persistent challenge in LLM-based translation systems. Despite their pre-training on vast corpora of natural utterances, LLMs exhibit translationese errors and generate unexpected unnatural translations, stemming from biases introduced during supervised fine-tuning (SFT). In this work, we systematically evaluate the prevalence of translationese in LLM-generated translations and investigate its roots during supervised training. We introduce methods to mitigate these biases, including polishing golden references and filtering unnatural training instances. Empirical evaluations demonstrate that these approaches significantly reduce translationese while improving translation naturalness, validated by human evaluations and automatic metrics. Our findings highlight the need for training-aware adjustments to optimize LLM translation outputs, paving the way for more fluent and target-language-consistent translations. We release the data and code at https://github.com/yafuly/LLM_Translationese.

[Arxiv](https://arxiv.org/abs/2503.04369)