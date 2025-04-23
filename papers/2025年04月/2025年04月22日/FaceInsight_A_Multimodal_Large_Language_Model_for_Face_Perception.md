# # 面向面部感知的多模态大型语言模型 FaceInsight

发布时间：2025年04月22日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在面部感知任务中的应用，并提出了一种改进方法FaceInsight。它通过视觉-文本对齐和引入面部分割图来提升模型性能，属于LLM的具体应用和改进，因此归类为LLM应用。` `面部感知` `计算机视觉`

> FaceInsight: A Multimodal Large Language Model for Face Perception

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展在理解通用视觉内容方面展现出了强大的能力。然而，这些通用领域的MLLMs在面部感知任务中表现欠佳，常常对特定的面部相关查询产生不准确或误导性的回答。为了解决这一问题，我们提出了FaceInsight——一款多功能的面部感知MLLM，能够提供细致的面部信息。我们的方法通过面部知识的视觉-文本对齐，建模面部信息之间的不确定依赖关系和确定性关系，从而缓解了语言驱动推理的局限性。此外，我们引入面部分割图作为辅助感知模态，通过增强局部结构线索丰富视觉输入，提升语义理解能力。在三个面部感知任务上的全面实验和分析表明，FaceInsight在无训练和微调两种设置下，均显著优于九个对比的MLLMs。

> Recent advances in multimodal large language models (MLLMs) have demonstrated strong capabilities in understanding general visual content. However, these general-domain MLLMs perform poorly in face perception tasks, often producing inaccurate or misleading responses to face-specific queries. To address this gap, we propose FaceInsight, the versatile face perception MLLM that provides fine-grained facial information. Our approach introduces visual-textual alignment of facial knowledge to model both uncertain dependencies and deterministic relationships among facial information, mitigating the limitations of language-driven reasoning. Additionally, we incorporate face segmentation maps as an auxiliary perceptual modality, enriching the visual input with localized structural cues to enhance semantic understanding. Comprehensive experiments and analyses across three face perception tasks demonstrate that FaceInsight consistently outperforms nine compared MLLMs under both training-free and fine-tuned settings.

[Arxiv](https://arxiv.org/abs/2504.15624)