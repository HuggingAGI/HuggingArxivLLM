# ImageChain：推动多模态大语言模型在序列图像到文本推理上的发展

发布时间：2025年02月26日

`LLM应用` `机器人`

> ImageChain: Advancing Sequential Image-to-Text Reasoning in Multimodal Large Language Models

# 摘要

> 多模态大语言模型 (MLLM) 在图像序列推理方面仍面临挑战。尽管近期模型在预训练中引入了多图像数据，但它们仍难以识别序列结构，往往独立处理每张图像。为此，我们提出了 ImageChain，一个通过将视觉序列建模为多轮对话来增强 MLLMs 对图像数据进行序列推理能力的框架。在 ImageChain 中，图像与相应的文本描述交替出现，形成一个受控对话，显式捕捉时间依赖性和叙述进展。我们的方法针对下一场景描述任务进行了优化，模型根据先前的视觉和文本线索生成对下一个场景的上下文感知描述。实验结果表明，我们的方法在下一场景描述任务上显著提升了性能，SimRate 指标（衡量与人工标注真实值的语义相似性）平均提升了 3.7% 到 19%。此外，ImageChain 在从漫画到机器人等应用中实现了强大的零样本跨领域性能。大量实验验证了在多模态、多轮对话设计中的指令微调是弥合静态图像理解与时间感知推理之间差距的关键。


> Reasoning over sequences of images remains a challenge for multimodal large language models (MLLMs). While recent models incorporate multi-image data during pre-training, they still struggle to recognize sequential structures, often treating images independently. This work introduces ImageChain, a framework that enhances MLLMs with sequential reasoning capabilities over image data by modeling visual sequences as a multi-turn conversation. In ImageChain, images are interleaved with corresponding textual descriptions to form a controlled dialogue that explicitly captures temporal dependencies and narrative progression. Our method optimizes for the task of next-scene description, where the model generates a context-aware description of an upcoming scene based on preceding visual and textual cues. We demonstrate that our approach improves performance on the next-scene description task -- achieving an average improvement from 3.7% to 19% in SimRate, a metric that quantifies semantic similarity to human-annotated ground truths. Moreover, ImageChain achieves robust zero-shot out-of-domain performance in applications ranging from comics to robotics. Extensive experiments validate that instruction-tuning in a multimodal, multi-turn conversation design is key to bridging the gap between static image understanding and temporally-aware reasoning.

[Arxiv](https://arxiv.org/abs/2502.19409)