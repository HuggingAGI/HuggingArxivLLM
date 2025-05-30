# NegVQA：视觉语言模型能否真正理解否定？

发布时间：2025年05月28日

`其他

理由：这篇论文主要探讨了视觉语言模型（VLMs）在处理否定理解方面的能力，构建了一个名为NegVQA的基准测试。虽然它涉及到了大型语言模型的应用，但其核心研究对象是视觉语言模型，并非专门讨论大型语言模型（LLM）本身的应用或理论。因此，它更适合归类为其他。` `计算机视觉` `视觉问答系统`

> NegVQA: Can Vision Language Models Understand Negation?

# 摘要

> 否定是语言现象中的基本要素，它能够完全反转一个句子的含义。随着视觉语言模型 (VLMs) 的持续发展并在高风险应用中得到部署，评估它们对否定的理解能力变得至关重要。为此，我们推出了 NegVQA，这是一个包含 7,379 个二选一问题的视觉问答 (VQA) 基准测试，涵盖了多样化的否定场景和图像-问题分布。通过利用大型语言模型从现有 VQA 数据集中生成否定版本的问题，我们构建了 NegVQA。在七种模型家族的 20 个最先进 VLM 上进行评估后，我们发现这些模型在处理否定时表现吃力，与回答原始问题相比，性能显著下降。此外，我们发现了一个 U 型扩展趋势：随着模型规模的增加，性能在最初下降后才有所提升。NegVQA 揭示了 VLMs 在否定理解方面的关键差距，并为未来 VLM 的发展提供了重要启示。项目页面可访问 https://yuhui-zh15.github.io/NegVQA/ 查看。

> Negation is a fundamental linguistic phenomenon that can entirely reverse the meaning of a sentence. As vision language models (VLMs) continue to advance and are deployed in high-stakes applications, assessing their ability to comprehend negation becomes essential. To address this, we introduce NegVQA, a visual question answering (VQA) benchmark consisting of 7,379 two-choice questions covering diverse negation scenarios and image-question distributions. We construct NegVQA by leveraging large language models to generate negated versions of questions from existing VQA datasets. Evaluating 20 state-of-the-art VLMs across seven model families, we find that these models struggle significantly with negation, exhibiting a substantial performance drop compared to their responses to the original questions. Furthermore, we uncover a U-shaped scaling trend, where increasing model size initially degrades performance on NegVQA before leading to improvements. Our benchmark reveals critical gaps in VLMs' negation understanding and offers insights into future VLM development. Project page available at https://yuhui-zh15.github.io/NegVQA/.

[Arxiv](https://arxiv.org/abs/2505.22946)