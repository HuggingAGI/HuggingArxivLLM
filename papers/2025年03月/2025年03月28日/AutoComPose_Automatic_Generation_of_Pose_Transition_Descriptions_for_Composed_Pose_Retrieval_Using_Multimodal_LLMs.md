# AutoComPose：利用多模态大语言模型，自动生成姿态转换描述，助力合成姿态检索。本研究探索了如何通过多模态LLMs实现姿态描述的自动生成，从而提升姿态检索的效率与准确性。

发布时间：2025年03月28日

`LLM应用` `计算机视觉` `多模态学习`

> AutoComPose: Automatic Generation of Pose Transition Descriptions for Composed Pose Retrieval Using Multimodal LLMs

# 摘要

> 姿势组合检索（CPR）让用户可以通过指定参考姿势和姿势转换描述来搜索人体姿势，但该领域的发展受制于标注姿势转换数据的稀缺性和不一致性。现有的CPR数据集依赖昂贵的人工标注或基于启发式规则的生成方法，这两种方式都限制了扩展性和多样性。

在本研究中，我们推出了AutoComPose——首个利用多模态大型语言模型（MLLMs）自动生成丰富且结构化姿势转换描述的框架。通过将转换分解为精细的身体部位运动并引入镜像/交换变体，我们的方法显著提升了标注质量，同时循环一致性约束确保了正向和反向转换的逻辑连贯性。

为了推动CPR研究的发展，我们构建并发布了两个专用基准数据集AIST-CPR和PoseFixCPR，补充了现有数据集的增强属性。大量实验表明，使用AutoComPose训练的检索模型在性能上优于基于人工标注和启发式方法，不仅显著降低了标注成本，还提升了检索质量。我们的工作开创了姿势转换的自动标注，为未来的CPR研究奠定了可扩展的基础。

> Composed pose retrieval (CPR) enables users to search for human poses by specifying a reference pose and a transition description, but progress in this field is hindered by the scarcity and inconsistency of annotated pose transitions. Existing CPR datasets rely on costly human annotations or heuristic-based rule generation, both of which limit scalability and diversity. In this work, we introduce AutoComPose, the first framework that leverages multimodal large language models (MLLMs) to automatically generate rich and structured pose transition descriptions. Our method enhances annotation quality by structuring transitions into fine-grained body part movements and introducing mirrored/swapped variations, while a cyclic consistency constraint ensures logical coherence between forward and reverse transitions. To advance CPR research, we construct and release two dedicated benchmarks, AIST-CPR and PoseFixCPR, supplementing prior datasets with enhanced attributes. Extensive experiments demonstrate that training retrieval models with AutoComPose yields superior performance over human-annotated and heuristic-based methods, significantly reducing annotation costs while improving retrieval quality. Our work pioneers the automatic annotation of pose transitions, establishing a scalable foundation for future CPR research.

[Arxiv](https://arxiv.org/abs/2503.22884)