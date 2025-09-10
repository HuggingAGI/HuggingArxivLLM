# 点语言模型：基于桥接式大型3D语言模型的任意对象分割

发布时间：2025年09月09日

`LLM应用` `工业与制造`

> Point Linguist Model: Segment Any Object via Bridged Large 3D-Language Model

# 摘要

> 借助大型语言模型（LLMs）进行3D目标分割凭借其广泛语义、任务灵活性与强泛化性，已成为主流范式。但该范式面临表示错位难题：LLMs处理高层语义token，而3D点云仅传递密集几何结构。以往方法中，这种错位在输入和输出阶段均带来局限：输入时，密集点块需大量预对齐，既削弱目标级语义，又易混淆相似干扰物；输出时，预测仅依赖密集特征却无显式几何线索，导致细粒度精度下降。为此，我们提出点语言模型（PLM）——一个无需3D-文本或3D-图像大规模预对齐、即可弥合LLMs与密集3D点云表示差距的通用框架。具体而言，我们引入目标中心判别表示（OcDR），通过难负样本感知训练学习目标中心token，精准捕捉目标语义与场景关系。这有效缓解了LLM token与3D点的错位，增强抗干扰能力，并推动LLMs内的语义级推理。为实现精准分割，我们设计几何重激活解码器（GRD），将携带LLM推断几何信息的OcDR token与对应密集特征融合以预测掩码，全程保留完整密集特征。实验表明，PLM在3D指代分割任务中表现卓越：ScanNetv2数据集上mIoU提升7.3，Multi3DRefer数据集上提升6.0；更在涵盖4类任务的7个基准测试中均获一致增益，充分证明全面的目标中心推理对鲁棒3D理解的有效性。

> 3D object segmentation with Large Language Models (LLMs) has become a prevailing paradigm due to its broad semantics, task flexibility, and strong generalization. However, this paradigm is hindered by representation misalignment: LLMs process high-level semantic tokens, whereas 3D point clouds convey only dense geometric structures. In prior methods, misalignment limits both input and output. At the input stage, dense point patches require heavy pre-alignment, weakening object-level semantics and confusing similar distractors. At the output stage, predictions depend only on dense features without explicit geometric cues, leading to a loss of fine-grained accuracy. To address these limitations, we present the Point Linguist Model (PLM), a general framework that bridges the representation gap between LLMs and dense 3D point clouds without requiring large-scale pre-alignment between 3D-text or 3D-images. Specifically, we introduce Object-centric Discriminative Representation (OcDR), which learns object-centric tokens that capture target semantics and scene relations under a hard negative-aware training objective. This mitigates the misalignment between LLM tokens and 3D points, enhances resilience to distractors, and facilitates semantic-level reasoning within LLMs. For accurate segmentation, we introduce the Geometric Reactivation Decoder (GRD), which predicts masks by combining OcDR tokens carrying LLM-inferred geometry with corresponding dense features, preserving comprehensive dense features throughout the pipeline. Extensive experiments show that PLM achieves significant improvements of +7.3 mIoU on ScanNetv2 and +6.0 mIoU on Multi3DRefer for 3D referring segmentation, with consistent gains across 7 benchmarks spanning 4 different tasks, demonstrating the effectiveness of comprehensive object-centric reasoning for robust 3D understanding.

[Arxiv](https://arxiv.org/abs/2509.07825)