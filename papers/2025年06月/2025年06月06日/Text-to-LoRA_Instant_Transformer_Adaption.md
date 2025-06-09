# Text-to-LoRA：Transformer模型的即时适配方案

发布时间：2025年06月06日

`LLM应用` `人工智能` `机器学习`

> Text-to-LoRA: Instant Transformer Adaption

# 摘要

> 尽管基础模型为快速内容创作提供了通用工具，但它们通常需要针对具体任务进行调整。传统方法依赖于繁琐的数据集整理和反复微调模型，虽然微调技术让基础模型能够适应众多新应用，但其训练成本高昂且耗时，对超参数选择也极为敏感。为了解决这些问题，我们推出了Text-to-LoRA（T2L），一种仅需目标任务的自然语言描述即可实时适应大型语言模型的技术。T2L是一个超网络，经过训练可以在一次廉价的前向传递中构建LoRA。通过使用9个预训练的LoRA适配器（如GSM8K、Arc等）对T2L进行训练，我们发现即兴重构的LoRA实例在对应测试集上的表现可与任务特定适配器相媲美。此外，T2L能够压缩数百个LoRA实例，并实现对完全未见过任务的零样本泛化。这一方法为实现基础模型的民主化专业化迈出了重要一步，同时以极低的计算需求实现了语言适应。我们的代码已在GitHub上开源，地址为https://github.com/SakanaAI/text-to-lora

> While Foundation Models provide a general tool for rapid content creation, they regularly require task-specific adaptation. Traditionally, this exercise involves careful curation of datasets and repeated fine-tuning of the underlying model. Fine-tuning techniques enable practitioners to adapt foundation models for many new applications but require expensive and lengthy training while being notably sensitive to hyper-parameter choices. To overcome these limitations, we introduce Text-to-LoRA (T2L), a model capable of adapting Large Language Models on the fly solely based on a natural language description of the target task. T2L is a hypernetwork trained to construct LoRAs in a single inexpensive forward pass. After training T2L on a suite of 9 pre-trained LoRA adapters (GSM8K, Arc, etc.), we show that the ad-hoc reconstructed LoRA instances match the performance of task-specific adapters across the corresponding test sets. Furthermore, T2L can compress hundreds of LoRA instances and zero-shot generalize to entirely unseen tasks. This approach provides a significant step towards democratizing the specialization of foundation models and enables language-based adaptation with minimal compute requirements. Our code is available at https://github.com/SakanaAI/text-to-lora

[Arxiv](https://arxiv.org/abs/2506.06105)