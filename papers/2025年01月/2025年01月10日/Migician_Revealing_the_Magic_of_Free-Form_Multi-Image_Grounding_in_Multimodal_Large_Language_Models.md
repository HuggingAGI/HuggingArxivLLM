# Migician: 揭秘多模态大语言模型中自由形式多图像接地的神奇之处

发布时间：2025年01月10日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在多图像定位任务中的应用和改进。论文提出了一个新的模型（Migician）和一个新的数据集（MGrounding-630k），并展示了其在多图像定位任务中的性能提升。这些内容主要涉及如何将大型语言模型应用于具体的任务（多图像定位），因此应归类为LLM应用。` `计算机视觉` `多模态学习`

> Migician: Revealing the Magic of Free-Form Multi-Image Grounding in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展显著提升了其对单张图像的细粒度感知和对多张图像的整体理解能力。然而，现有的MLLMs在复杂的多图像场景中实现精确的定位仍然面临挑战。为此，我们首先探索了一种思维链（CoT）框架，将单图像定位与多图像理解相结合。虽然部分有效，但由于其非端到端的特性，它仍然不稳定，且在捕捉抽象视觉信息方面存在困难。因此，我们推出了Migician，这是首个能够在多张图像之间进行自由形式且准确定位的多图像定位模型。为支持这一模型，我们提出了MGrounding-630k数据集，包含从现有数据集中提取的多个多图像定位任务数据，以及新生成的自由形式定位指令跟随数据。此外，我们还推出了MIG-Bench，这是一个专门用于评估多图像定位能力的综合基准。实验结果表明，我们的模型在多图像定位能力方面显著优于现有最好的MLLMs，性能提升了21.61%，甚至超过了更大的70B模型。我们的代码、模型、数据集和基准完全开源。

> The recent advancement of Multimodal Large Language Models (MLLMs) has significantly improved their fine-grained perception of single images and general comprehension across multiple images. However, existing MLLMs still face challenges in achieving precise grounding in complex multi-image scenarios. To address this, we first explore a Chain-of-Thought (CoT) framework that integrates single-image grounding with multi-image comprehension. While partially effective, it remains unstable and struggles to capture abstract visual information due to its non-end-to-end nature. Therefore, we introduce Migician, the first multi-image grounding model capable of performing free-form and accurate grounding across multiple images. To support this, we present the MGrounding-630k dataset, which comprises data for several multi-image grounding tasks derived from existing datasets, along with newly generated free-form grounding instruction-following data. Furthermore, we propose MIG-Bench, a comprehensive benchmark specifically designed for evaluating multi-image grounding capabilities. Experimental results demonstrate that our model achieves significantly superior multi-image grounding capabilities, outperforming the best existing MLLMs by 21.61% and even surpassing much larger 70B models. Our code, model, dataset, and benchmark are fully open-sourced.

[Arxiv](https://arxiv.org/abs/2501.05767)