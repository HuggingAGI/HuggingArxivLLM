# Triad: 利用视觉专家指导的视觉分词器和制造流程，赋能基于LMM的异常检测。

发布时间：2025年03月17日

`LLM应用` `工业检测` `制造过程`

> Triad: Empowering LMM-based Anomaly Detection with Vision Expert-guided Visual Tokenizer and Manufacturing Process

# 摘要

> 尽管大模型在工业异常检测领域的应用尝试不断推进，但其泛化能力与通用任务相比仍有显著差距。我们将其归因于两个关键因素。首先，通用大模型难以准确识别视觉模态中的缺陷，导致对缺陷区域的关注不足。为此，我们建议对LLaVA模型的AnyRes结构进行调整，将现有工业异常检测模型识别出的潜在异常区域引入大模型。其次，现有方法多聚焦于缺陷模式的学习或与正常样本的对比，却忽视了缺陷成因的深入理解。鉴于缺陷生成与制造过程密不可分，我们提出了一种基于制造过程的工业异常检测新范式。通过设计工业异常检测指令调优数据集（InstructIAD）和基于制造过程的思维链数据组织方法（CoT-M），我们成功将制造过程融入工业异常检测。基于以上改进，我们开发了Triad，一种结合专家指导的兴趣区域 tokenizer 和制造过程的新型大模型工业异常检测方法。实验结果表明，Triad不仅在现有大模型中表现出色，更在引入制造过程信息后实现了更高的检测精度。我们的源代码、训练数据和预训练模型现已公开，详情请访问https://github.com/tzjtatata/Triad。

> Although recent methods have tried to introduce large multimodal models (LMMs) into industrial anomaly detection (IAD), their generalization in the IAD field is far inferior to that for general purposes. We summarize the main reasons for this gap into two aspects. On one hand, general-purpose LMMs lack cognition of defects in the visual modality, thereby failing to sufficiently focus on defect areas. Therefore, we propose to modify the AnyRes structure of the LLaVA model, providing the potential anomalous areas identified by existing IAD models to the LMMs. On the other hand, existing methods mainly focus on identifying defects by learning defect patterns or comparing with normal samples, yet they fall short of understanding the causes of these defects. Considering that the generation of defects is closely related to the manufacturing process, we propose a manufacturing-driven IAD paradigm. An instruction-tuning dataset for IAD (InstructIAD) and a data organization approach for Chain-of-Thought with manufacturing (CoT-M) are designed to leverage the manufacturing process for IAD. Based on the above two modifications, we present Triad, a novel LMM-based method incorporating an expert-guided region-of-interest tokenizer and manufacturing process for industrial anomaly detection. Extensive experiments show that our Triad not only demonstrates competitive performance against current LMMs but also achieves further improved accuracy when equipped with manufacturing processes. Source code, training data, and pre-trained models will be publicly available at https://github.com/tzjtatata/Triad.

[Arxiv](https://arxiv.org/abs/2503.13184)