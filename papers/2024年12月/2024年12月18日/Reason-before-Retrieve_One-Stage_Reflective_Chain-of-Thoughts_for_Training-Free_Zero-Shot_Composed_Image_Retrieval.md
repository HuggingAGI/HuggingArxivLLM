# Reason-before-Retrieve：用于免训练零样本组合图像检索的单阶段反思性思维链

发布时间：2024年12月18日

`LLM应用` `图像检索` `视觉语言`

> Reason-before-Retrieve: One-Stage Reflective Chain-of-Thoughts for Training-Free Zero-Shot Composed Image Retrieval

# 摘要

> 组合图像检索（CIR）旨在检索与参考图像高度相似、并融合了用户指定文本修改的目标图像，从而更精准地捕捉用户意图。现有的无训练零样本 CIR（ZS-CIR）方法通常分两步走：先为参考图像生成标题，再借助大型语言模型推理得出目标描述。然而，这些方法存在关键视觉细节缺失、推理能力有限的问题，致使检索效果不佳。为应对这些挑战，我们提出了一种全新的无训练单阶段方法——用于 ZS-CIR 的单阶段反思性思维链推理（OSrCIR），它运用多模态大型语言模型在单阶段推理过程中留存关键视觉信息，避免了两阶段方法中的信息丢失。我们的反思性思维链框架通过将操作意图与参考图像的上下文线索相匹配，进一步提高了解释的准确性。OSrCIR 在多个任务中比现有的无训练方法性能提升了 1.80% 至 6.44%，在 ZS-CIR 领域创造了新的领先成果，增强了其在视觉语言应用中的实用性。我们的代码将在 https://github.com/Pter61/osrcir2024/ 上公布。

> Composed Image Retrieval (CIR) aims to retrieve target images that closely resemble a reference image while integrating user-specified textual modifications, thereby capturing user intent more precisely. Existing training-free zero-shot CIR (ZS-CIR) methods often employ a two-stage process: they first generate a caption for the reference image and then use Large Language Models for reasoning to obtain a target description. However, these methods suffer from missing critical visual details and limited reasoning capabilities, leading to suboptimal retrieval performance. To address these challenges, we propose a novel, training-free one-stage method, One-Stage Reflective Chain-of-Thought Reasoning for ZS-CIR (OSrCIR), which employs Multimodal Large Language Models to retain essential visual information in a single-stage reasoning process, eliminating the information loss seen in two-stage methods. Our Reflective Chain-of-Thought framework further improves interpretative accuracy by aligning manipulation intent with contextual cues from reference images. OSrCIR achieves performance gains of 1.80% to 6.44% over existing training-free methods across multiple tasks, setting new state-of-the-art results in ZS-CIR and enhancing its utility in vision-language applications. Our code will be available at https://github.com/Pter61/osrcir2024/.

[Arxiv](https://arxiv.org/abs/2412.11077)