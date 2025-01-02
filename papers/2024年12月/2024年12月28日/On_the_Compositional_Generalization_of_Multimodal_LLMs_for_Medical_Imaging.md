# 论及医学成像中多模态大型语言模型的组合泛化

发布时间：2024年12月28日

`LLM应用` `多模态语言模型`

> On the Compositional Generalization of Multimodal LLMs for Medical Imaging

# 摘要

> 多模态大型语言模型（MLLMs）在医疗领域潜力巨大，然而其能力常受某些医疗领域数据匮乏所限，这凸显出搞清楚 MLLMs 能利用哪些类型的图像来实现泛化的必要性。当下研究显示，多任务训练优于单任务，因为不同任务能相互受益，可它们往往忽视了这些任务间的内在联系，在选择数据集以强化特定任务方面提供的指引有限。为剖析此现象，我们尝试运用组合泛化（CG）——即模型通过重新组合已学元素来理解新组合的能力——作为指导框架。由于医学图像能通过模态、解剖区域和任务精准界定，这自然为探索 CG 营造了环境。于是，我们整合了 106 个医疗数据集来创建 Med-MAT 以开展综合实验。实验证实，MLLMs 能够运用 CG 来理解未曾见过的医学图像，并认定 CG 是多任务训练中所观察到的泛化的主要驱动因素之一。另外，进一步的研究表明，CG 能有效支持数据有限的数据集，并在不同的骨干网络中表现出稳定的性能，突显了其通用性和广泛适用性。Med-MAT 可在 https://github.com/FreedomIntelligence/Med-MAT 公开获取。

> Multimodal large language models (MLLMs) hold significant potential in the medical field, but their capabilities are often limited by insufficient data in certain medical domains, highlighting the need for understanding what kinds of images can be used by MLLMs for generalization. Current research suggests that multi-task training outperforms single-task as different tasks can benefit each other, but they often overlook the internal relationships within these tasks, providing limited guidance on selecting datasets to enhance specific tasks. To analyze this phenomenon, we attempted to employ compositional generalization (CG)-the ability of models to understand novel combinations by recombining learned elements-as a guiding framework. Since medical images can be precisely defined by Modality, Anatomical area, and Task, naturally providing an environment for exploring CG. Therefore, we assembled 106 medical datasets to create Med-MAT for comprehensive experiments. The experiments confirmed that MLLMs can use CG to understand unseen medical images and identified CG as one of the main drivers of the generalization observed in multi-task training. Additionally, further studies demonstrated that CG effectively supports datasets with limited data and delivers consistent performance across different backbones, highlighting its versatility and broad applicability. Med-MAT is publicly available at https://github.com/FreedomIntelligence/Med-MAT.

[Arxiv](https://arxiv.org/abs/2412.20070)