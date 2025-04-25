# 突破模态壁垒：借助多模态大语言模型实现通用嵌入学习

发布时间：2025年04月24日

`LLM应用` `多模态`

> Breaking the Modality Barrier: Universal Embedding Learning with Multimodal LLMs

# 摘要

> 对比语言-图像预训练（CLIP）框架在多模态表示学习领域得到了广泛应用，尤其在图像-文本检索和聚类方面表现突出。然而，其效果受到三个关键限制：（1）文本标记截断，（2）孤立的图文编码，以及（3）因词袋行为导致的组合性不足。尽管近期的多模态大型语言模型（MLLMs）在泛化视觉-语言理解方面取得了显著进展，但其在学习可迁移多模态表示方面的潜力尚未得到充分探索。为此，我们提出了UniME（通用多模态嵌入），一个新颖的两阶段框架，旨在利用MLLMs学习适用于多种下游任务的判别表示。在第一阶段，我们通过从强大的基于LLM的教师模型中进行文本判别知识蒸馏，显著增强了MLLM语言组件的嵌入能力。在第二阶段，我们引入了增强负样本指令微调，进一步提升判别表示学习的效果。具体而言，我们首先缓解假阴性污染，然后在每个批次中为每个实例采样多个硬负样本，迫使模型关注更具挑战性的样本。这种方法不仅显著提升了判别能力，还增强了下游任务中的指令遵循能力。我们在MMEB基准和多个检索任务（包括短文本和长文本检索以及组合检索）上进行了广泛实验。实验结果表明，UniME在所有任务中均实现了性能的一致提升，展现出卓越的判别和组合能力。

> The Contrastive Language-Image Pre-training (CLIP) framework has become a widely used approach for multimodal representation learning, particularly in image-text retrieval and clustering. However, its efficacy is constrained by three key limitations: (1) text token truncation, (2) isolated image-text encoding, and (3) deficient compositionality due to bag-of-words behavior. While recent Multimodal Large Language Models (MLLMs) have demonstrated significant advances in generalized vision-language understanding, their potential for learning transferable multimodal representations remains underexplored.In this work, we present UniME (Universal Multimodal Embedding), a novel two-stage framework that leverages MLLMs to learn discriminative representations for diverse downstream tasks. In the first stage, we perform textual discriminative knowledge distillation from a powerful LLM-based teacher model to enhance the embedding capability of the MLLMś language component. In the second stage, we introduce hard negative enhanced instruction tuning to further advance discriminative representation learning. Specifically, we initially mitigate false negative contamination and then sample multiple hard negatives per instance within each batch, forcing the model to focus on challenging samples. This approach not only improves discriminative power but also enhances instruction-following ability in downstream tasks. We conduct extensive experiments on the MMEB benchmark and multiple retrieval tasks, including short and long caption retrieval and compositional retrieval. Results demonstrate that UniME achieves consistent performance improvement across all tasks, exhibiting superior discriminative and compositional capabilities.

[Arxiv](https://arxiv.org/abs/2504.17432)