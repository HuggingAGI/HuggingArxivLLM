# 无训练且任务无关的框架，用于提升MLLM在高分辨率图像上的性能表现

发布时间：2025年07月14日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在处理高分辨率图像时的挑战，并提出了一种新的框架来提升其性能，属于应用层面的改进，因此归类为LLM应用。` `计算机视觉`

> A Training-Free, Task-Agnostic Framework for Enhancing MLLM Performance on High-Resolution Images

# 摘要

> 多模态大型语言模型（MLLMs）在视觉语言理解、推理和生成方面表现卓越，但在处理高分辨率图像时却面临挑战。这一限制源于MLLMs通常基于固定分辨率的图像进行微调，以与预训练的图像编码器保持一致。直接输入高分辨率图像会导致训练与测试分辨率不匹配，从而影响泛化能力。虽然下采样图像可以确保一致性，但会损害精细细节，导致性能下降。为解决这一问题，我们提出了一种名为提取候选区域后预测（ECP）的新型无训练、任务无关的两阶段框架。ECP的核心直觉在于，尽管MLLMs在高分辨率图像上表现不佳，但它们在下采样图像上的预测仍包含隐含的定位线索。通过首先基于粗略预测识别候选区域，然后基于该区域进行最终预测，ECP在保留精细细节的同时，有效缓解了高分辨率数据带来的挑战。我们在4K GUI定位和4K、8K MLLM感知任务上验证了框架的有效性，与基线方法相比，分别实现了+21.3%、+5.8%、+5.2%的绝对提升。代码可在https://github.com/yenncye/ECP获取。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in vision-language understanding, reasoning, and generation. However, they struggle with tasks requiring fine-grained localization and reasoning in high-resolution images. This constraint stems from the fact that MLLMs are fine-tuned with fixed image resolution to align with the pre-trained image encoder used in MLLM. Consequently, feeding high-resolution images directly into MLLMs leads to poor generalization due to a train-test resolution discrepancy, while downsampling these images-although ensuring consistency-compromises fine-grained visual details and ultimately degrades performance. To address this challenge, we propose Extract Candidate then Predict (ECP), a novel training-free, task-agnostic two-stage framework designed to enhance MLLM performance on high-resolution images. The key intuition behind ECP is that while MLLMs struggle with high-resolution images, their predictions on downsampled images still contain implicit localization cues. By first identifying candidate region using the coarse prediction and then predicting the final output based on candidate region, ECP effectively preserves fine-grained details while mitigating the challenges posed by high-resolution data. We validate our framework on 4K GUI grounding and 4K, 8K MLLM perception, achieving +21.3%, +5.8%, +5.2% absolute improvement compared to baseline respectively, demonstrating its effectiveness. Code is available at https://github.com/yenncye/ECP.

[Arxiv](https://arxiv.org/abs/2507.10202)