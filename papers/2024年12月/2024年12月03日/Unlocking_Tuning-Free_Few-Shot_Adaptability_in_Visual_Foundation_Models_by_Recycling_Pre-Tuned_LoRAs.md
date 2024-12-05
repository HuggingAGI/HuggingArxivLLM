# 通过回收预调谐的 LoRAs 来解锁视觉基础模型的免调优少样本适应能力

发布时间：2024年12月03日

`LLM应用` `计算机视觉` `人工智能`

> Unlocking Tuning-Free Few-Shot Adaptability in Visual Foundation Models by Recycling Pre-Tuned LoRAs

# 摘要

> 大型语言模型（LLMs），像 ChatGPT 这样的，无需微调就能展现出强大的少样本适应能力，非常适合数据有限和实时性的应用。但当前的视觉基础模型（VFMs）还没具备这种能力，它们需要有足够的调优数据来进行明确的微调。而且，预训练 - 微调范式催生了众多像低秩自适应（LoRA）这样的任务特定模块化组件。我们首次尝试在不获取原始训练数据的情况下，重用各种预先调优的 LoRA，以实现 VFMs 无需调优的少样本适应。我们的“LoRA 回收”框架，通过元学习目标，利用从预先调优的 LoRA 自身反向生成的代理数据，提炼出元 - LoRA。一旦 VFM 配备了元 - LoRA，就能像 LLMs 的上下文学习那样，在单次前向传递中解决新的少样本任务。另外，我们为框架引入了一种双重高效机制，大大加快了元训练进程，同时保持甚至提升了性能。在不同领域和同领域场景下的各种少样本分类基准上进行的大量实验，都证明了我们框架的优越性。

> Large Language Models (LLMs) such as ChatGPT demonstrate strong few-shot adaptability without requiring fine-tuning, positioning them ideal for data-limited and real-time applications. However, this adaptability has not yet been replicated in current Visual Foundation Models (VFMs), which require explicit fine-tuning with sufficient tuning data. Besides, the pretraining-finetuning paradigm has led to the surge of numerous task-specific modular components, such as Low-Rank Adaptation (LoRA). For the first time, we explore the potential of reusing diverse pre-tuned LoRAs without accessing their original training data, to achieve tuning-free few-shot adaptation in VFMs. Our framework, LoRA Recycle, distills a meta-LoRA from diverse pre-tuned LoRAs with a meta-learning objective, using surrogate data generated inversely from pre-tuned LoRAs themselves. The VFM, once equipped with the meta-LoRA, is empowered to solve new few-shot tasks in a single forward pass, akin to the in-context learning of LLMs. Additionally, we incorporate a double-efficient mechanism tailored to our framework, significantly accelerating the meta-training process while maintaining or even improving performance. Extensive experiments across various few-shot classification benchmarks across both in- and cross-domain scenarios demonstrate the superiority of our framework.

[Arxiv](https://arxiv.org/abs/2412.02220)