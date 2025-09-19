# UnifiedVisual：构建统一视觉语言数据集的框架

发布时间：2025年09月18日

`其他` `基础理论`

> UnifiedVisual: A Framework for Constructing Unified Vision-Language Datasets

# 摘要

> 统一视觉大型语言模型（VLLMs）近年来在多模态理解与生成两方面均取得了显著进展，推动了视觉问答、文本引导图像合成等应用的发展。然而，统一VLLMs的发展仍受限于缺乏能充分发挥这两种核心能力协同潜力的数据集。现有数据集往往孤立处理理解与生成任务，从而限制了统一VLLMs的性能。为弥合这一关键差距，我们提出了一种新颖的数据集构建框架UnifiedVisual，同时发布了精心构建的高质量数据集UnifiedVisual-240K，旨在实现多模态理解与生成能力的相互增强。UnifiedVisual-240K无缝整合了丰富多样的视觉与文本输入输出，支持全面的跨模态推理和精确的文本-图像对齐。该数据集覆盖了广泛的任务类型和数据源，保证了丰富的多样性，并弥补了现有资源的主要不足。大量实验结果表明，基于UnifiedVisual-240K训练的模型在各类任务中均表现优异。尤为重要的是，这些模型在多模态理解与生成之间呈现出显著的相互增强效应，进一步验证了我们框架和数据集的有效性。我们认为，UnifiedVisual为推动统一VLLMs发展、释放其全部潜力提供了新的增长点。相关代码和数据集已在https://github.com/fnlp-vision/UnifiedVisual开放获取。

> Unified vision large language models (VLLMs) have recently achieved impressive advancements in both multimodal understanding and generation, powering applications such as visual question answering and text-guided image synthesis. However, progress in unified VLLMs remains constrained by the lack of datasets that fully exploit the synergistic potential between these two core abilities. Existing datasets typically address understanding and generation in isolation, thereby limiting the performance of unified VLLMs. To bridge this critical gap, we introduce a novel dataset construction framework, UnifiedVisual, and present UnifiedVisual-240K, a high-quality dataset meticulously designed to facilitate mutual enhancement between multimodal understanding and generation. UnifiedVisual-240K seamlessly integrates diverse visual and textual inputs and outputs, enabling comprehensive cross-modal reasoning and precise text-to-image alignment. Our dataset encompasses a wide spectrum of tasks and data sources, ensuring rich diversity and addressing key shortcomings of prior resources. Extensive experiments demonstrate that models trained on UnifiedVisual-240K consistently achieve strong performance across a wide range of tasks. Notably, these models exhibit significant mutual reinforcement between multimodal understanding and generation, further validating the effectiveness of our framework and dataset. We believe UnifiedVisual represents a new growth point for advancing unified VLLMs and unlocking their full potential. Our code and datasets is available at https://github.com/fnlp-vision/UnifiedVisual.

[Arxiv](https://arxiv.org/abs/2509.14738)