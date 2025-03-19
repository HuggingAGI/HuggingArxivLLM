# MP-GUI：基于多模态大语言模型的GUI理解与模态感知研究

发布时间：2025年03月18日

`LLM应用` `人工智能` `用户界面`

> MP-GUI: Modality Perception with MLLMs for GUI Understanding

# 摘要

> 图形用户界面（GUI）已成为现代社会的重要组成部分，对于以人类为中心的系统而言，理解 GUI 至关重要。然而，与自然图像或文档不同，GUI 由人工设计的图形元素组成，这些元素经过排列以传达特定的语义含义。当前的多模态大型语言模型（MLLMs）虽然在处理图形和文本组件方面已经非常熟练，但由于缺乏对 GUI 明确的空间结构建模，它们在理解 GUI 方面仍然面临障碍。此外，由于隐私问题和嘈杂环境，获取高质量的空间结构数据也极具挑战性。为了解决这些挑战，我们提出了 MP-GUI，一种专门设计用于 GUI 理解的 MLLM。MP-GUI 配备了三个精确专业的感知器，可以从屏幕中提取图形、文本和空间模式，作为 GUI 专用的视觉线索，并通过空间结构细化策略和自适应融合门结合，以满足不同 GUI 理解任务的具体偏好。为了应对训练数据稀缺的问题，我们还引入了一条自动数据收集的管道。大量实验表明，MP-GUI 在有限数据的情况下，能够在各种 GUI 理解任务中取得令人瞩目的成果。

> Graphical user interface (GUI) has become integral to modern society, making it crucial to be understood for human-centric systems. However, unlike natural images or documents, GUIs comprise artificially designed graphical elements arranged to convey specific semantic meanings. Current multi-modal large language models (MLLMs) already proficient in processing graphical and textual components suffer from hurdles in GUI understanding due to the lack of explicit spatial structure modeling. Moreover, obtaining high-quality spatial structure data is challenging due to privacy issues and noisy environments. To address these challenges, we present MP-GUI, a specially designed MLLM for GUI understanding. MP-GUI features three precisely specialized perceivers to extract graphical, textual, and spatial modalities from the screen as GUI-tailored visual clues, with spatial structure refinement strategy and adaptively combined via a fusion gate to meet the specific preferences of different GUI understanding tasks. To cope with the scarcity of training data, we also introduce a pipeline for automatically data collecting. Extensive experiments demonstrate that MP-GUI achieves impressive results on various GUI understanding tasks with limited data.

[Arxiv](https://arxiv.org/abs/2503.14021)