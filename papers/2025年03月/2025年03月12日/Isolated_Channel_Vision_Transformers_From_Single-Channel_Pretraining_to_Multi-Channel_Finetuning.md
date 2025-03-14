# # 分离式通道视觉变压器：从单通道预训练到多通道微调的完整过程

发布时间：2025年03月12日

`其他`

> Isolated Channel Vision Transformers: From Single-Channel Pretraining to Multi-Channel Finetuning

# 摘要

> 视觉Transformer（ViTs）在标准RGB图像处理任务中表现卓越。然而，将其直接应用于多通道成像（MCI）数据（如医学和遥感领域）仍具挑战性。MCI数据通常由不同模态获取的层组成，直接训练可能导致互补信息被掩盖，进而影响性能。本文提出了一种适用于大规模MCI数据的简单而有效的预训练框架。我们的方法——独立通道ViT（IC-ViT），通过对图像通道进行独立分块，实现了多模态多通道任务的预训练。研究表明，这种基于通道的分块是处理MCI数据的关键技术。更重要的是，IC-ViT可以在单个通道上预训练，并在下游多通道数据集上进行微调。该预训练框架不仅捕获补丁间的依赖关系，还能理解通道间的关联，生成稳健的特征表示。在包括细胞显微成像（JUMP-CP和CHAMMI）和卫星成像（So2Sat-LCZ42）在内的多种任务和基准测试中，实验结果显示，与现有基于通道自适应的方法相比，IC-ViT在性能上提升了4-14个百分点。此外，其高效的训练特性使其成为在异构数据上对基础模型进行大规模预训练的理想选择。

> Vision Transformers (ViTs) have achieved remarkable success in standard RGB image processing tasks. However, applying ViTs to multi-channel imaging (MCI) data, e.g., for medical and remote sensing applications, remains a challenge. In particular, MCI data often consist of layers acquired from different modalities. Directly training ViTs on such data can obscure complementary information and impair the performance. In this paper, we introduce a simple yet effective pretraining framework for large-scale MCI datasets. Our method, named Isolated Channel ViT (IC-ViT), patchifies image channels individually and thereby enables pretraining for multimodal multi-channel tasks. We show that this channel-wise patchifying is a key technique for MCI processing. More importantly, one can pretrain the IC-ViT on single channels and finetune it on downstream multi-channel datasets. This pretraining framework captures dependencies between patches as well as channels and produces robust feature representation. Experiments on various tasks and benchmarks, including JUMP-CP and CHAMMI for cell microscopy imaging, and So2Sat-LCZ42 for satellite imaging, show that the proposed IC-ViT delivers 4-14 percentage points of performance improvement over existing channel-adaptive approaches. Further, its efficient training makes it a suitable candidate for large-scale pretraining of foundation models on heterogeneous data.

[Arxiv](https://arxiv.org/abs/2503.09826)