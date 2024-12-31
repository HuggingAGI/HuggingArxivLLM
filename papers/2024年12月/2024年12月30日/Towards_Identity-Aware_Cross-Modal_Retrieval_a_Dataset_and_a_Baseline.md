# 走向身份感知的跨模态检索：一个数据集与一条基线

发布时间：2024年12月30日

`LLM应用` `多媒体检索` `人物识别`

> Towards Identity-Aware Cross-Modal Retrieval: a Dataset and a Baseline

# 摘要

> 深度学习的最新进展大幅提升了基于内容的检索方法，尤其是像 CLIP 这类能将图像和文本映射至共享嵌入空间的模型。然而，这些方法在处理特定领域实体和训练数据中缺失的长尾概念时，往往力不从心，特别是在识别特定个体方面。在本文中，我们探究了身份感知的跨模态检索任务，旨在依据自然语言查询在特定情境下检索人物图像。这一任务在多种场景中都极为关键，比如搜索和浏览个性化视频合集或者国家广播公司维护的大型视听档案。我们引入了一个新的数据集——COCO 人物换脸（COCO-PFS），它源于广泛使用的 COCO 数据集，并通过 VGGFace2 中的深度伪造生成的面孔加以丰富。该数据集弥补了此任务训练和评估模型所欠缺的大规模数据集。我们的实验评估了为该任务重新运用的不同 CLIP 变体的性能，包括我们的架构——身份感知 CLIP（Id-CLIP），其通过针对性微调实现了颇具竞争力的检索性能。我们的贡献为能够识别长尾身份和上下文细微差异的更强大的跨模态检索系统奠定了基础。数据和代码可在 https://github.com/mesnico/IdCLIP 获取。

> Recent advancements in deep learning have significantly enhanced content-based retrieval methods, notably through models like CLIP that map images and texts into a shared embedding space. However, these methods often struggle with domain-specific entities and long-tail concepts absent from their training data, particularly in identifying specific individuals. In this paper, we explore the task of identity-aware cross-modal retrieval, which aims to retrieve images of persons in specific contexts based on natural language queries. This task is critical in various scenarios, such as for searching and browsing personalized video collections or large audio-visual archives maintained by national broadcasters. We introduce a novel dataset, COCO Person FaceSwap (COCO-PFS), derived from the widely used COCO dataset and enriched with deepfake-generated faces from VGGFace2. This dataset addresses the lack of large-scale datasets needed for training and evaluating models for this task. Our experiments assess the performance of different CLIP variations repurposed for this task, including our architecture, Identity-aware CLIP (Id-CLIP), which achieves competitive retrieval performance through targeted fine-tuning. Our contributions lay the groundwork for more robust cross-modal retrieval systems capable of recognizing long-tail identities and contextual nuances. Data and code are available at https://github.com/mesnico/IdCLIP.

[Arxiv](https://arxiv.org/abs/2412.21009)