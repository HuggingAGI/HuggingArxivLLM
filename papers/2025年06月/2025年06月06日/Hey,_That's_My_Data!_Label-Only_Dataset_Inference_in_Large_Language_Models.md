# 嘿，那是我的数据！大型语言模型中的仅标签数据集推断

发布时间：2025年06月06日

`LLM应用

理由：这篇论文探讨了大型语言模型的数据集推理问题，并提出了一种基于灾难性遗忘的仅标签数据集推理框架CatShift，用于检测数据集是否属于模型的原始训练语料库。这属于大型语言模型的应用场景，特别是数据安全和隐私保护方面的应用。` `数据安全`

> Hey, That's My Data! Label-Only Dataset Inference in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 凭借其在理解、推理和生成人类语言方面的卓越能力，彻底改变了自然语言处理领域。然而，它们对大规模、通常为专有数据集的依赖带来了一个关键挑战：未经授权使用此类数据可能导致版权侵犯和重大财务损失。现有的数据集推理方法通常依赖于对数概率来检测可疑的训练材料，但许多领先的 LLM 已经开始隐藏或模糊这些信号。这一现实凸显了开发仅依赖标签的方法的迫切需求，这些方法可以在不依赖内部模型对数概率的情况下识别数据集成员。我们通过引入 CatShift 来填补这一空白，这是一个基于灾难性遗忘的仅标签数据集推理框架：当 LLM 暴露于新数据时，它倾向于覆盖之前学到的知识。如果可疑数据集曾被模型见过，那么在该数据集的一部分上进行微调会引发模型输出的显著后调优变化；反之，真正新颖的数据则会引起较小的变化。通过比较可疑数据集与已知非成员验证集在模型输出上的变化，我们从统计上确定可疑数据集是否可能属于模型的原始训练语料库。在开源和基于 API 的 LLM 上进行的广泛实验验证了 CatShift 在对数概率不可访问设置下的有效性，为保护专有数据提供了一个强大而实用的解决方案。

> Large Language Models (LLMs) have revolutionized Natural Language Processing by excelling at interpreting, reasoning about, and generating human language. However, their reliance on large-scale, often proprietary datasets poses a critical challenge: unauthorized usage of such data can lead to copyright infringement and significant financial harm. Existing dataset-inference methods typically depend on log probabilities to detect suspicious training material, yet many leading LLMs have begun withholding or obfuscating these signals. This reality underscores the pressing need for label-only approaches capable of identifying dataset membership without relying on internal model logits.
  We address this gap by introducing CatShift, a label-only dataset-inference framework that capitalizes on catastrophic forgetting: the tendency of an LLM to overwrite previously learned knowledge when exposed to new data. If a suspicious dataset was previously seen by the model, fine-tuning on a portion of it triggers a pronounced post-tuning shift in the model's outputs; conversely, truly novel data elicits more modest changes. By comparing the model's output shifts for a suspicious dataset against those for a known non-member validation set, we statistically determine whether the suspicious set is likely to have been part of the model's original training corpus. Extensive experiments on both open-source and API-based LLMs validate CatShift's effectiveness in logit-inaccessible settings, offering a robust and practical solution for safeguarding proprietary data.

[Arxiv](https://arxiv.org/abs/2506.06057)