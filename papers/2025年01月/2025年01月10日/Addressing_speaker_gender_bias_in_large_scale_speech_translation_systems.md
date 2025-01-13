# 应对大规模语音翻译系统中的说话者性别偏见

发布时间：2025年01月10日

`LLM应用

**理由**：该论文主要探讨了如何利用大型语言模型（LLMs）来纠正语音翻译系统中的性别偏见问题，并通过微调ST模型来改进翻译质量。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `语音翻译` `性别偏见`

> Addressing speaker gender bias in large scale speech translation systems

# 摘要

> 本研究聚焦于语音翻译（ST）系统中的说话者性别偏见问题，这种偏见可能导致冒犯性和不准确的翻译。大规模ST系统中常见的男性偏见通常源自机器翻译（MT）系统的训练数据。我们的解决方案分为两步：首先，利用大型语言模型（LLMs）高效地根据说话者性别纠正翻译；其次，使用纠正后的数据微调ST模型，使其能够直接从音频线索生成特定性别的翻译，无需显式性别输入。此外，我们还提出了一种三模式微调模型，适用于说话者性别已预定义或不应从语音线索推断的场景。在MuST-SHE测试集上，我们的方法使女性说话者的翻译质量比基线和其他大规模ST系统（如Seamless M4T和Canary）提高了70%。

> This study addresses the issue of speaker gender bias in Speech Translation (ST) systems, which can lead to offensive and inaccurate translations. The masculine bias often found in large-scale ST systems is typically perpetuated through training data derived from Machine Translation (MT) systems. Our approach involves two key steps. First, we employ Large Language Models (LLMs) to rectify translations based on the speaker's gender in a cost-effective manner. Second, we fine-tune the ST model with the corrected data, enabling the model to generate gender-specific translations directly from audio cues, without the need for explicit gender input. Additionally, we propose a three-mode fine-tuned model for scenarios where the speaker's gender is either predefined or should not be inferred from speech cues. We demonstrate a 70% improvement in translations for female speakers compared to our baseline and other large-scale ST systems, such as Seamless M4T and Canary, on the MuST-SHE test set.

[Arxiv](https://arxiv.org/abs/2501.05989)