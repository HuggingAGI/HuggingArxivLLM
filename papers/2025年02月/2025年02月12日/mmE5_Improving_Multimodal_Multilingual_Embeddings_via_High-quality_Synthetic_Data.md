# mmE5: 利用高质量合成数据优化多模态多语言嵌入表示

发布时间：2025年02月12日

`其他` `多模态` `数据生成`

> mmE5: Improving Multimodal Multilingual Embeddings via High-quality Synthetic Data

# 摘要

> 多模态嵌入模型因其能够将文本、图像等不同模态的数据映射到统一的表示空间而备受关注。然而，有限的标注多模态数据常常限制了嵌入性能。近期研究通过数据合成来解决这一问题，但合成数据的质量仍然是关键瓶颈。在本研究中，我们提出了高质量合成多模态数据的三大标准。首先，广泛的适用范围确保生成的数据涵盖多种任务和模态，适用于各种下游场景。其次，强大的跨模态对齐使不同模态在语义上保持一致。最后，高保真度确保合成数据保留现实细节，从而提升其可靠性。基于这些原则，我们合成的 dataset 具备以下特点：(1) 涵盖广泛的 tasks、模态组合和语言；(2) 通过多模态大语言模型的单次深度思考生成；(3) 结合真实图像与准确相关的文本，并通过自我评估和优化确保保真度。借助这些高质量的合成和标注数据集，我们训练出了多模态多语言的 E5 模型 mmE5。大量实验表明，mmE5 在 MMEB 基准测试中达到 state-of-the-art 性能，并在 XTD 基准测试中展现出卓越的多语言能力。我们的代码、数据集和模型已开源，地址为 https://github.com/haon-chen/mmE5。

> Multimodal embedding models have gained significant attention for their ability to map data from different modalities, such as text and images, into a unified representation space. However, the limited labeled multimodal data often hinders embedding performance. Recent approaches have leveraged data synthesis to address this problem, yet the quality of synthetic data remains a critical bottleneck. In this work, we identify three criteria for high-quality synthetic multimodal data. First, broad scope ensures that the generated data covers diverse tasks and modalities, making it applicable to various downstream scenarios. Second, robust cross-modal alignment makes different modalities semantically consistent. Third, high fidelity ensures that the synthetic data maintains realistic details to enhance its reliability. Guided by these principles, we synthesize datasets that: (1) cover a wide range of tasks, modality combinations, and languages, (2) are generated via a deep thinking process within a single pass of a multimodal large language model, and (3) incorporate real-world images with accurate and relevant texts, ensuring fidelity through self-evaluation and refinement. Leveraging these high-quality synthetic and labeled datasets, we train a multimodal multilingual E5 model mmE5. Extensive experiments demonstrate that mmE5 achieves state-of-the-art performance on the MMEB Benchmark and superior multilingual performance on the XTD benchmark. Our codes, datasets and models are released in https://github.com/haon-chen/mmE5.

[Arxiv](https://arxiv.org/abs/2502.08468)