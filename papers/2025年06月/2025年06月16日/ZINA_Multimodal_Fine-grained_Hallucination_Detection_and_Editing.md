# ZINA：多模态细粒度幻觉检测与编辑

发布时间：2025年06月16日

`LLM应用` `多模态`

> ZINA: Multimodal Fine-grained Hallucination Detection and Editing

# 摘要

> 多模态大型语言模型 (MLLMs) 常常会出现输出与视觉内容不符的“幻觉”现象。鉴于这些幻觉可能呈现多种形态，因此在细粒度层面上检测幻觉对于全面评估和分析至关重要。为此，我们提出了一项全新的任务——针对 MLLMs 的多模态细粒度幻觉检测与编辑。同时，我们提出了一种名为 ZINA 的创新方法，该方法能够在细粒度层面上识别幻觉片段，将其错误类型分类为六类，并建议适当的改进方案。为了训练和评估这一任务的模型，我们构建了 VisionHall 数据集，该数据集包含来自十二个 MLLMs 的 6.9 千个输出，这些输出由 211 名标注员手动标注，并通过一种基于图的方法生成了 2 万个人工合成样本，该方法能够捕捉错误类型之间的依赖关系。实验结果表明，ZINA 在检测和编辑任务中均优于现有方法，包括 GPT-4o 和 LLama-3.2。

> Multimodal Large Language Models (MLLMs) often generate hallucinations, where the output deviates from the visual content. Given that these hallucinations can take diverse forms, detecting hallucinations at a fine-grained level is essential for comprehensive evaluation and analysis. To this end, we propose a novel task of multimodal fine-grained hallucination detection and editing for MLLMs. Moreover, we propose ZINA, a novel method that identifies hallucinated spans at a fine-grained level, classifies their error types into six categories, and suggests appropriate refinements. To train and evaluate models for this task, we constructed VisionHall, a dataset comprising 6.9k outputs from twelve MLLMs manually annotated by 211 annotators, and 20k synthetic samples generated using a graph-based method that captures dependencies among error types. We demonstrated that ZINA outperformed existing methods, including GPT-4o and LLama-3.2, in both detection and editing tasks.

[Arxiv](https://arxiv.org/abs/2506.13130)