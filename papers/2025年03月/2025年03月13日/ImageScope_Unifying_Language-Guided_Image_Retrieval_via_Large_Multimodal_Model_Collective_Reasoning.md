# ImageScope: 基于大规模多模态模型的协同推理，统一语言引导的图像检索方法

发布时间：2025年03月13日

`LLM应用` `图像检索` `计算机视觉`

> ImageScope: Unifying Language-Guided Image Retrieval via Large Multimodal Model Collective Reasoning

# 摘要

> 随着图像在在线内容中的普及，语言指导的图像检索（LGIR）在过去十年中已成为研究热点，涵盖了许多输入形式多样的子任务。尽管大型多模态模型（LMMs）的发展极大地推动了这些任务的进展，但现有方法往往孤立地处理它们，需要为每个任务构建独立的系统。这不仅增加了系统的复杂性和维护成本，还加剧了由语言模糊性和复杂图像内容带来的挑战，使得检索系统难以提供准确可靠的结果。

为此，我们提出了ImageScope，一个无需训练的三阶段框架，通过集体推理来统一处理LGIR任务。统一的核心在于语言的组合性质，它将多样化的LGIR任务转化为一个通用的文本到图像检索过程，同时利用LMMs的推理作为普遍的验证机制来优化结果。

具体而言，在第一阶段，我们通过链式思维（CoT）推理，整合不同语义粒度的搜索意图，提升框架的鲁棒性。在第二和第三阶段，我们分别通过局部验证谓词命题以及全局进行成对评估，对检索结果进行反思。在六个LGIR数据集上进行的实验表明，ImageScope优于具有竞争力的基线方法。全面的评估和消融研究进一步证实了我们设计的有效性。

> With the proliferation of images in online content, language-guided image retrieval (LGIR) has emerged as a research hotspot over the past decade, encompassing a variety of subtasks with diverse input forms. While the development of large multimodal models (LMMs) has significantly facilitated these tasks, existing approaches often address them in isolation, requiring the construction of separate systems for each task. This not only increases system complexity and maintenance costs, but also exacerbates challenges stemming from language ambiguity and complex image content, making it difficult for retrieval systems to provide accurate and reliable results. To this end, we propose ImageScope, a training-free, three-stage framework that leverages collective reasoning to unify LGIR tasks. The key insight behind the unification lies in the compositional nature of language, which transforms diverse LGIR tasks into a generalized text-to-image retrieval process, along with the reasoning of LMMs serving as a universal verification to refine the results. To be specific, in the first stage, we improve the robustness of the framework by synthesizing search intents across varying levels of semantic granularity using chain-of-thought (CoT) reasoning. In the second and third stages, we then reflect on retrieval results by verifying predicate propositions locally, and performing pairwise evaluations globally. Experiments conducted on six LGIR datasets demonstrate that ImageScope outperforms competitive baselines. Comprehensive evaluations and ablation studies further confirm the effectiveness of our design.

[Arxiv](https://arxiv.org/abs/2503.10166)