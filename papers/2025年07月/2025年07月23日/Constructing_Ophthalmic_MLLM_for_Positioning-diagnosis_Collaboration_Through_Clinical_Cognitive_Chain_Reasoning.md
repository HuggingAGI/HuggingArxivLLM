# 通过临床认知链推理打造眼科多实例学习模型，实现定位诊断协作

发布时间：2025年07月23日

`LLM应用`

> Constructing Ophthalmic MLLM for Positioning-diagnosis Collaboration Through Clinical Cognitive Chain Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）在医学诊断领域展现出巨大潜力，然而在眼科等专业领域，标注粒度的碎片化和临床推理逻辑的不一致性成为精准跨模态理解的阻碍。本文介绍了眼科专用的多模态大型语言模型FundusExpert，它集成了定位诊断推理能力，并通过智能Fundus-Engine系统构建了FundusGen数据集。Fundus-Engine实现了定位自动化，并利用基于MLLM的语义扩展，将全局疾病分类、局部目标检测和细粒度特征分析整合到单眼底图像中。此外，通过构建与临床认知链对齐的推理路径，引导模型生成可解释的推理路径。在FundusGen的指令数据微调下，FundusExpert在眼科问答任务中取得了最佳性能，超过了40B MedRegA的平均准确率26.6%。在零样本报告生成任务中，其临床一致性达到77.0%，远超GPT-4o的47.6%。此外，我们揭示了数据质量和模型能力之间的缩放定律（【数学公式】L ∝ N^{0.068}），证明了FundusGen中认知对齐标注提高了数据利用效率。通过将区域级定位与诊断推理链相结合，我们的工作开发了一个可扩展且与临床对齐的多模态大型语言模型，并探索了一种弥合特定多模态模型视觉语言鸿沟的路径。我们的项目可在https://github.com/MeteorElf/FundusExpert找到。

> Multimodal large language models (MLLMs) demonstrate significant potential in the field of medical diagnosis. However, they face critical challenges in specialized domains such as ophthalmology, particularly the fragmentation of annotation granularity and inconsistencies in clinical reasoning logic, which hinder precise cross-modal understanding. This paper introduces FundusExpert, an ophthalmology-specific MLLM with integrated positioning-diagnosis reasoning capabilities, along with FundusGen, a dataset constructed through the intelligent Fundus-Engine system. Fundus-Engine automates localization and leverages MLLM-based semantic expansion to integrate global disease classification, local object detection, and fine-grained feature analysis within a single fundus image. Additionally, by constructing a clinically aligned cognitive chain, it guides the model to generate interpretable reasoning paths. FundusExpert, fine-tuned with instruction data from FundusGen, achieves the best performance in ophthalmic question-answering tasks, surpassing the average accuracy of the 40B MedRegA by 26.6%. It also excels in zero-shot report generation tasks, achieving a clinical consistency of 77.0%, significantly outperforming GPT-4o's 47.6%. Furthermore, we reveal a scaling law between data quality and model capability ($L \propto N^{0.068}$), demonstrating that the cognitive alignment annotations in FundusGen enhance data utilization efficiency. By integrating region-level localization with diagnostic reasoning chains, our work develops a scalable, clinically-aligned MLLM and explores a pathway toward bridging the visual-language gap in specific MLLMs. Our project can be found at https://github.com/MeteorElf/FundusExpert.

[Arxiv](https://arxiv.org/abs/2507.17539)