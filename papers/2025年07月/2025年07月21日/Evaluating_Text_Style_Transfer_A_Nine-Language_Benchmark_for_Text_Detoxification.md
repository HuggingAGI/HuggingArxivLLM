# # 评测文本风格迁移：面向文本去毒的九语言基准测试

发布时间：2025年07月21日

`LLM应用

理由：这篇论文探讨了大型语言模型在文本风格迁移任务中的评估，特别是多语言环境下的评估。它关注于如何评估这些模型在不同语言中的表现，属于应用层面的研究，因此归类为LLM应用。` `机器翻译`

> Evaluating Text Style Transfer: A Nine-Language Benchmark for Text Detoxification

# 摘要

> 尽管大型语言模型（LLMs）在文本生成任务上取得了显著进展，但对文本风格迁移（TST）等任务的评估仍是重要难题。近期研究表明（Dementieva et al., 2024; Pauli et al., 2025），自动评估指标与人工评价之间存在显著差异。此外，现有研究多集中于英语，而多语言TST评估领域仍待探索。本文首次针对九种语言（英语、西班牙语、德语、中文、阿拉伯语、印地语、乌克兰语、俄语和阿姆哈拉语）的文本去毒系统展开全面评估研究。借鉴机器翻译领域的思路，我们不仅考察了现代神经网络评估模型的效果，还研究了基于提示词驱动的LLM评估方法。我们的研究发现为设计更可靠的多语言TST评估流程提供了实用方案，特别是在文本去毒领域。

> Despite recent progress in large language models (LLMs), evaluation of text generation tasks such as text style transfer (TST) remains a significant challenge. Recent studies (Dementieva et al., 2024; Pauli et al., 2025) revealed a substantial gap between automatic metrics and human judgments. Moreover, most prior work focuses exclusively on English, leaving multilingual TST evaluation largely unexplored. In this paper, we perform the first comprehensive multilingual study on evaluation of text detoxification system across nine languages: English, Spanish, German, Chinese, Arabic, Hindi, Ukrainian, Russian, Amharic. Drawing inspiration from the machine translation, we assess the effectiveness of modern neural-based evaluation models alongside prompting-based LLM-as-a-judge approaches. Our findings provide a practical recipe for designing more reliable multilingual TST evaluation pipeline in the text detoxification case.

[Arxiv](https://arxiv.org/abs/2507.15557)