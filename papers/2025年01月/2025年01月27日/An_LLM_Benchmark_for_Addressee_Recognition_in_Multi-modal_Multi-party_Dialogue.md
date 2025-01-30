# 多模态多方对话中收件人识别的LLM基准

发布时间：2025年01月27日

`LLM应用

**理由**：该论文主要关注的是大型语言模型（如GPT-4o）在多方对话系统中的表现，特别是受话者识别任务。这属于将大型语言模型应用于特定任务（多方对话系统）的研究，因此应归类为LLM应用。` `口语对话系统` `多方交互`

> An LLM Benchmark for Addressee Recognition in Multi-modal Multi-party Dialogue

# 摘要

> 处理多方对话是推进口语对话系统的重要一步，这需要开发专门针对多方交互的任务。为此，我们构建了一个多模态的三方对话语料库。本文聚焦于受话者识别任务，即确定下一个发言者，这是多方对话系统的关键环节。语料库的一个子集标注了受话者信息，结果显示约20%的对话轮次中明确指出了受话者。为了评估任务难度，我们对GPT-4o在受话者识别任务上的表现进行了基准测试。结果显示，GPT-4o的准确率仅略高于随机猜测，突显了多方对话中受话者识别的挑战。这些发现表明，需要进一步研究以提升大型语言模型在理解和应对多方对话动态复杂性方面的能力。

> Handling multi-party dialogues represents a significant step for advancing spoken dialogue systems, necessitating the development of tasks specific to multi-party interactions. To address this challenge, we are constructing a multi-modal multi-party dialogue corpus of triadic (three-participant) discussions. This paper focuses on the task of addressee recognition, identifying who is being addressed to take the next turn, a critical component unique to multi-party dialogue systems. A subset of the corpus was annotated with addressee information, revealing that explicit addressees are indicated in approximately 20% of conversational turns. To evaluate the task's complexity, we benchmarked the performance of a large language model (GPT-4o) on addressee recognition. The results showed that GPT-4o achieved an accuracy only marginally above chance, underscoring the challenges of addressee recognition in multi-party dialogue. These findings highlight the need for further research to enhance the capabilities of large language models in understanding and navigating the intricacies of multi-party conversational dynamics.

[Arxiv](https://arxiv.org/abs/2501.16643)