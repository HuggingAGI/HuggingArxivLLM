# LiveLongBench：探索直播口语文本的长上下文理解

发布时间：2025年04月24日

`LLM应用

摘要讨论了大型语言模型在长上下文理解中的应用，特别是在真实对话场景中的表现。论文构建了一个新的数据集，并评估了现有模型在不同任务中的表现，提出了改进的方法。这属于LLM的应用研究。` `电子商务`

> LiveLongBench: Tackling Long-Context Understanding for Spoken Texts from Live Streams

# 摘要

> 长上下文理解在自然语言处理领域是一项重大挑战，尤其在以语音为基础、高冗余和信息密度不均为特点的真实对话场景中表现突出。尽管大型语言模型（LLMs）在现有基准测试中取得了令人印象深刻的成果，但这些数据集未能充分反映出真实场景文本的复杂性，限制了其在实际应用中的效果。为填补这一研究空白，我们构建了首个基于真实直播数据的长文本数据集，旨在真实还原现实场景中高冗余和对话式的特性。我们设计了三类任务：依赖检索型、依赖推理型和混合型。随后，我们对流行的LLMs和专门方法进行了全面评估，以测试它们在这些任务中对长上下文的理解能力。我们的研究结果显示，现有方法表现出明显任务偏好，并在高度冗余的输入上表现欠佳，没有任何单一方法能够持续领先。我们提出了一种新基线方法，该方法能够更好地处理语音文本中的冗余信息，并在各项任务中表现出色。我们的研究结果不仅揭示了现有方法的关键局限性，还为改进长上下文理解提供了未来研究方向。最后，我们的基准填补了长上下文语音语言理解评估领域的空白，并为开发实际的电子商务系统提供了实用基础。代码和基准数据集可在https://github.com/Yarayx/livelongbench获取。

> Long-context understanding poses significant challenges in natural language processing, particularly for real-world dialogues characterized by speech-based elements, high redundancy, and uneven information density. Although large language models (LLMs) achieve impressive results on existing benchmarks, these datasets fail to reflect the complexities of such texts, limiting their applicability to practical scenarios. To bridge this gap, we construct the first spoken long-text dataset, derived from live streams, designed to reflect the redundancy-rich and conversational nature of real-world scenarios. We construct tasks in three categories: retrieval-dependent, reasoning-dependent, and hybrid. We then evaluate both popular LLMs and specialized methods to assess their ability to understand long-contexts in these tasks. Our results show that current methods exhibit strong task-specific preferences and perform poorly on highly redundant inputs, with no single method consistently outperforming others. We propose a new baseline that better handles redundancy in spoken text and achieves strong performance across tasks. Our findings highlight key limitations of current methods and suggest future directions for improving long-context understanding. Finally, our benchmark fills a gap in evaluating long-context spoken language understanding and provides a practical foundation for developing real-world e-commerce systems. The code and benchmark are available at https://github.com/Yarayx/livelongbench.

[Arxiv](https://arxiv.org/abs/2504.17366)