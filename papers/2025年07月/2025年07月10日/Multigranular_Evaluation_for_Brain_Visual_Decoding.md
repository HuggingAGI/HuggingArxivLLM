# # 大脑视觉解码的多粒度评估

发布时间：2025年07月10日

`其他` `神经科学` `人工智能`

> Multigranular Evaluation for Brain Visual Decoding

# 摘要

> 现有的脑视觉解码评估协议主要依赖于模糊的指标，这些指标掩盖了模型之间的差异，缺乏神经科学基础，且无法捕捉到视觉上的细微差别。为了解决这些问题，我们提出了BASIC——一个统一的、多粒度的评估框架，能够同时量化解码图像与真实图像之间的结构保真度、推理一致性以及上下文连贯性。

在结构层面，我们引入了一套基于分层分割的指标套件，包括前景、语义、实例和组件掩膜，这些掩膜基于粒度感知的对应关系，锚定在掩膜结构中。在语义层面，我们利用多模态大型语言模型提取结构化的场景表示，涵盖对象、属性和关系，从而实现与真实刺激的详细、可扩展且上下文丰富的比较。

我们在此统一评估框架内对多种视觉解码方法进行了基准测试，涵盖多个刺激-神经成像数据集。这些标准共同为衡量脑视觉解码方法提供了一个更具区分性、可解释性和全面性的基础。

> Existing evaluation protocols for brain visual decoding predominantly rely on coarse metrics that obscure inter-model differences, lack neuroscientific foundation, and fail to capture fine-grained visual distinctions. To address these limitations, we introduce BASIC, a unified, multigranular evaluation framework that jointly quantifies structural fidelity, inferential alignment, and contextual coherence between decoded and ground truth images. For the structural level, we introduce a hierarchical suite of segmentation-based metrics, including foreground, semantic, instance, and component masks, anchored in granularity-aware correspondence across mask structures. For the semantic level, we extract structured scene representations encompassing objects, attributes, and relationships using multimodal large language models, enabling detailed, scalable, and context-rich comparisons with ground-truth stimuli. We benchmark a diverse set of visual decoding methods across multiple stimulus-neuroimaging datasets within this unified evaluation framework. Together, these criteria provide a more discriminative, interpretable, and comprehensive foundation for measuring brain visual decoding methods.

[Arxiv](https://arxiv.org/abs/2507.07993)