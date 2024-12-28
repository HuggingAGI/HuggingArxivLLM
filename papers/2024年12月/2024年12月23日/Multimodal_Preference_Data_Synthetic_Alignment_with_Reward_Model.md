# 多模态偏好数据与奖励模型的合成式对齐

发布时间：2024年12月23日

`LLM应用` `多模态` `视觉语言`

> Multimodal Preference Data Synthetic Alignment with Reward Model

# 摘要

> 多模态大型语言模型（MLLMs）整合视觉与文本数据，在字幕生成、视觉问答等任务上进步显著。但因其预训练数据和真实用户提示存在差异，有时会产出有误导或幻觉性的内容。视觉语言任务中运用直接偏好优化（DPO）的现有方法，往往依赖 GPT-4 或 CLIP 等强大模型来判定正负响应。在此，我们提出一个新框架，利用奖励模型作为人类偏好的代理来生成合成数据，以实现有效的多模态对齐和 DPO 训练。所得的 DPO 数据集涵盖 2K 至 9K 的图像 - 文本对，并在 LLaVA-v1.5-7B 上进行评估。我们的方法在多个幻觉和视觉语言基准测试中，大幅提升了基础模型的可信度和推理能力。实验结果显示，整合诸如来自生成模型和奖励模型的选定合成数据，能够有效降低对人工标注数据的依赖，同时增强 MLLMs 的对齐能力，为更安全的部署提供了可扩展的解决方案。

> Multimodal large language models (MLLMs) have significantly advanced tasks like caption generation and visual question answering by integrating visual and textual data. However, they sometimes produce misleading or hallucinate content due to discrepancies between their pre-training data and real user prompts. Existing approaches using Direct Preference Optimization (DPO) in vision-language tasks often rely on strong models like GPT-4 or CLIP to determine positive and negative responses. Here, we propose a new framework in generating synthetic data using a reward model as a proxy of human preference for effective multimodal alignment with DPO training. The resulting DPO dataset ranges from 2K to 9K image-text pairs, was evaluated on LLaVA-v1.5-7B, where our approach demonstrated substantial improvements in both the trustworthiness and reasoning capabilities of the base model across multiple hallucination and vision-language benchmark. The experiment results indicate that integrating selected synthetic data, such as from generative and rewards models can effectively reduce reliance on human-annotated data while enhancing MLLMs' alignment capability, offering a scalable solution for safer deployment.

[Arxiv](https://arxiv.org/abs/2412.17417)