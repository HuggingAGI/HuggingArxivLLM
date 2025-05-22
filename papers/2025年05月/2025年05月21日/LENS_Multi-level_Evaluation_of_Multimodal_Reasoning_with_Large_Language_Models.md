# LENS：多层级评估大型语言模型的多模态推理能力

发布时间：2025年05月21日

`LLM应用` `计算机视觉`

> LENS: Multi-level Evaluation of Multimodal Reasoning with Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 在整合视觉与语言信息方面取得了显著进展，但它们在处理复杂现实场景的推理能力上仍有待提升。现有基准测试通常以任务为导向构建，缺乏对不同任务样本来自同一数据分布的保证，因此难以有效评估低级感知能力对高级推理的协同效应。为了解决这一问题，我们提出了Lens，一个包含3.4K当代图像和60K+人工编写问题的多层级基准测试，覆盖八项任务和十二种日常场景，形成三个逐步进阶的任务层级：感知、理解和推理。每张图像都配备了适用于所有任务的丰富标注信息，支持从基础感知到组合推理的全面评估。此外，我们的图像来自人工收集的社交媒体，其中53%的图像发布于2025年1月之后。我们评估了15个前沿MLLMs，包括Qwen2.5-VL-72B、InternVL3-78B、GPT-4o，以及两个推理模型QVQ-72B-preview和Kimi-VL。这些模型的发布时间晚于2024年12月，但在推理任务中，没有一个模型的准确率超过60%。项目页面：https://github.com/Lens4MLLMs/lens。ICCV 2025研讨会页面：https://lens4mllms.github.io/mars2-workshop-iccv2025/

> Multimodal Large Language Models (MLLMs) have achieved significant advances in integrating visual and linguistic information, yet their ability to reason about complex and real-world scenarios remains limited. The existing benchmarks are usually constructed in the task-oriented manner without guarantee that different task samples come from the same data distribution, thus they often fall short in evaluating the synergistic effects of lower-level perceptual capabilities on higher-order reasoning. To lift this limitation, we contribute Lens, a multi-level benchmark with 3.4K contemporary images and 60K+ human-authored questions covering eight tasks and 12 daily scenarios, forming three progressive task tiers, i.e., perception, understanding, and reasoning. One feature is that each image is equipped with rich annotations for all tasks. Thus, this dataset intrinsically supports to evaluate MLLMs to handle image-invariable prompts, from basic perception to compositional reasoning. In addition, our images are manully collected from the social media, in which 53% were published later than Jan. 2025. We evaluate 15+ frontier MLLMs such as Qwen2.5-VL-72B, InternVL3-78B, GPT-4o and two reasoning models QVQ-72B-preview and Kimi-VL. These models are released later than Dec. 2024, and none of them achieve an accuracy greater than 60% in the reasoning tasks. Project page: https://github.com/Lens4MLLMs/lens. ICCV 2025 workshop page: https://lens4mllms.github.io/mars2-workshop-iccv2025/

[Arxiv](https://arxiv.org/abs/2505.15616)