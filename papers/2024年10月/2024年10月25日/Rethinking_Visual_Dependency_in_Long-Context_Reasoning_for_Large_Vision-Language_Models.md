# 重新思索大型视觉语言模型在长上下文推理中的视觉依赖

发布时间：2024年10月25日

`LLM应用` `计算机视觉` `人工智能`

> Rethinking Visual Dependency in Long-Context Reasoning for Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在跨模型任务中表现优异，然而在长上下文推理方面，由于过度依赖文本信息且视觉依赖度降低，其性能有所下滑。本研究对 LVLMs 在长上下文推理中的情况展开实证分析，发现上下文长度增加会导致对语言的依赖度提高，而牺牲了视觉依赖。为应对此问题，我们提出一种全新的无需训练的上下文修剪方法，有选择性地去除不太关键的文本信息。该方法增强了视觉依赖，降低了文本噪声，进而提升了 LVLMs 在长上下文推理中的性能。我们通过构建长上下文数据集来验证此方法，展示了其在各类 LVLMs 中的有效性。此外，进一步的分析证实了不同令牌修剪策略的稳健性，并初步探究了修剪率与上下文长度之间的缩放规律。

> Large Vision-Language Models (LVLMs) excel in cross-model tasks but experience performance declines in long-context reasoning due to overreliance on textual information and reduced visual dependency. In this study, we empirically analyze LVLMs in long-context reasoning, revealing that increased context length leads to a higher dependence on language at the expense of visual dependency. To address this issue, we propose a novel training-free context pruning method that selectively removes less critical textual information. Our approach enhances visual dependency and reduces textual noise, thereby improving LVLM performance in long-context reasoning. We validate our method by constructing a long-context dataset, demonstrating its effectiveness across various LVLMs. Moreover, further analysis confirms the robustness of different token pruning strategies and preliminary explores scaling laws between pruning rates and context length.

[Arxiv](https://arxiv.org/abs/2410.19732)