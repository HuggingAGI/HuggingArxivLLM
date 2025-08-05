# I2CR: 用于多模态实体链接的跨模态与跨模态协作反思

发布时间：2025年08月04日

`LLM应用` `信息检索` `多模态`

> I2CR: Intra- and Inter-modal Collaborative Reflections for Multimodal Entity Linking

# 摘要

> 多模态实体链接在众多应用场景中发挥着重要作用。基于大语言模型的方法已成为这一任务的主流范式，通过有效结合文本和视觉模态显著提升了性能表现。尽管如此，现有方法仍面临两大挑战：其一是在某些场景下对图像数据的引入显得多余，其二是仅依赖一次性提取的视觉特征，这可能削弱模型的效果和准确性。针对这些挑战，我们提出了一种全新的基于大语言模型的多模态实体链接框架，命名为Intra- and Inter-modal Collaborative Reflections。该框架优先利用文本信息来完成任务。当仅凭文本信息不足以通过跨模态评估准确链接实体时，它会启用一种多轮迭代策略，整合图像多方面的关键视觉线索以支持推理并提升匹配精度。在三个广泛使用的公共数据集上进行的大量实验表明，我们的框架在该任务中始终优于当前最先进的方法，分别取得了3.2%、5.1%和1.6%的性能提升。我们的代码可在https://github.com/ziyan-xiaoyu/I2CR/获取。


> Multimodal entity linking plays a crucial role in a wide range of applications. Recent advances in large language model-based methods have become the dominant paradigm for this task, effectively leveraging both textual and visual modalities to enhance performance. Despite their success, these methods still face two challenges, including unnecessary incorporation of image data in certain scenarios and the reliance only on a one-time extraction of visual features, which can undermine their effectiveness and accuracy. To address these challenges, we propose a novel LLM-based framework for the multimodal entity linking task, called Intra- and Inter-modal Collaborative Reflections. This framework prioritizes leveraging text information to address the task. When text alone is insufficient to link the correct entity through intra- and inter-modality evaluations, it employs a multi-round iterative strategy that integrates key visual clues from various aspects of the image to support reasoning and enhance matching accuracy. Extensive experiments on three widely used public datasets demonstrate that our framework consistently outperforms current state-of-the-art methods in the task, achieving improvements of 3.2%, 5.1%, and 1.6%, respectively. Our code is available at https://github.com/ziyan-xiaoyu/I2CR/.

[Arxiv](https://arxiv.org/abs/2508.02243)