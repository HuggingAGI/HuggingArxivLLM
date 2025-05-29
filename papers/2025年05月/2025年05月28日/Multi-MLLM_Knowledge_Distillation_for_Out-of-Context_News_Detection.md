# 多模型知识蒸馏在上下文外新闻检测中的应用

发布时间：2025年05月28日

`LLM应用

摘要讨论了使用多模态大语言模型（MLLMs）检测图片新闻失实信息，并提出了一种通过知识蒸馏框架优化模型性能的方法。这属于将语言模型应用于具体任务并进行优化的范畴，因此归类为LLM应用。` `信息真实性`

> Multi-MLLM Knowledge Distillation for Out-of-Context News Detection

# 摘要

> # 摘要
多模态图片新闻失实信息是一种信息失实类型，其中图片被用于其原始上下文之外的场景。许多现有研究已经利用多模态大语言模型（MLLMs）来检测图片新闻失实信息。然而，观察到较小的 MLLMs 在零-shot 场景下的性能有限，因此它们通常需要丰富的标签微调和/或昂贵的 GPT 模型 API 调用来提高性能，这在资源匮乏的场景中并不实际。相比之下，我们旨在以更高效和经济的方式提升小型 MLLMs 的性能。为此，我们首先提示多个教师 MLLMs 生成标签预测及其相应的推理，这些共同作为教师的知识。然后，我们引入一个两阶段的知识蒸馏框架，将此知识转移到学生 MLLM。在第一阶段，我们使用所有训练数据对 student 模型应用 LoRA 微调。在第二阶段，我们进一步使用 LoRA 微调和 DPO 在教师预测冲突的数据点上对 student 模型进行微调。这种两阶段策略降低了标注成本，并帮助 student 模型发现更具挑战性案例中的细微模式。实验结果表明，我们的方法使用不到 10% 的标签数据即可达到最先进的性能。

> Multimodal out-of-context news is a type of misinformation in which the image is used outside of its original context. Many existing works have leveraged multimodal large language models (MLLMs) for detecting out-of-context news. However, observing the limited zero-shot performance of smaller MLLMs, they generally require label-rich fine-tuning and/or expensive API calls to GPT models to improve the performance, which is impractical in low-resource scenarios. In contrast, we aim to improve the performance of small MLLMs in a more label-efficient and cost-effective manner. To this end, we first prompt multiple teacher MLLMs to generate both label predictions and corresponding rationales, which collectively serve as the teachers' knowledge. We then introduce a two-stage knowledge distillation framework to transfer this knowledge to a student MLLM. In Stage 1, we apply LoRA fine-tuning to the student model using all training data. In Stage 2, we further fine-tune the student model using both LoRA fine-tuning and DPO on the data points where teachers' predictions conflict. This two-stage strategy reduces annotation costs and helps the student model uncover subtle patterns in more challenging cases. Experimental results demonstrate that our approach achieves state-of-the-art performance using less than 10% labeled data.

[Arxiv](https://arxiv.org/abs/2505.22517)