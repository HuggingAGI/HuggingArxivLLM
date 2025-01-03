# 注意力驱动的 GUI 接地：无需微调，直接利用预训练的多模态大语言模型

发布时间：2024年12月14日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在图形用户界面（GUIs）解析中的应用，特别是提出了一种无需微调的注意力驱动 grounding 方法。该方法利用预训练 MLLMs 的注意力模式来完成任务，属于将大型语言模型应用于具体任务（GUI解析）的范畴，因此分类为LLM应用。` `人机交互` `图形用户界面`

> Attention-driven GUI Grounding: Leveraging Pretrained Multimodal Large Language Models without Fine-Tuning

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）的最新进展引发了对其自主交互和解析图形用户界面（GUIs）能力的广泛关注。这些系统面临的一个核心挑战是 grounding——即基于 GUI 图像和文本查询，精准识别关键组件（如文本或图标）。传统方法依赖于对 MLLMs 进行专门的微调来直接预测组件位置。然而，本文提出了一种创新的无调优注意力驱动 grounding（TAG）方法，利用预训练 MLLMs 的固有注意力模式，无需额外微调即可完成任务。该方法通过从精心设计的查询提示中提取并聚合特定标记的注意力图来实现。应用于前沿 MLLM MiniCPM-Llama3-V 2.5 时，我们的无调优方法在文本定位等任务中表现优异，性能媲美基于调优的方法。此外，基于注意力图的 grounding 技术显著优于 MiniCPM-Llama3-V 2.5 的直接定位预测，展现了预训练 MLLMs 注意力图的巨大潜力，为该领域的未来创新奠定了基础。

> Recent advancements in Multimodal Large Language Models (MLLMs) have generated significant interest in their ability to autonomously interact with and interpret Graphical User Interfaces (GUIs). A major challenge in these systems is grounding-accurately identifying critical GUI components such as text or icons based on a GUI image and a corresponding text query. Traditionally, this task has relied on fine-tuning MLLMs with specialized training data to predict component locations directly. However, in this paper, we propose a novel Tuning-free Attention-driven Grounding (TAG) method that leverages the inherent attention patterns in pretrained MLLMs to accomplish this task without the need for additional fine-tuning. Our method involves identifying and aggregating attention maps from specific tokens within a carefully constructed query prompt. Applied to MiniCPM-Llama3-V 2.5, a state-of-the-art MLLM, our tuning-free approach achieves performance comparable to tuning-based methods, with notable success in text localization. Additionally, we demonstrate that our attention map-based grounding technique significantly outperforms direct localization predictions from MiniCPM-Llama3-V 2.5, highlighting the potential of using attention maps from pretrained MLLMs and paving the way for future innovations in this domain.

[Arxiv](https://arxiv.org/abs/2412.10840)