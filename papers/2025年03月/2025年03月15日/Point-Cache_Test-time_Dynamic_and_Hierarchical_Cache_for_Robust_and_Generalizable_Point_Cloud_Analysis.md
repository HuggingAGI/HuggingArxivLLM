# 点缓存：测试时动态分层缓存，实现鲁棒且通用的点云分析

发布时间：2025年03月15日

`其他` `计算机视觉` `3D建模`

> Point-Cache: Test-time Dynamic and Hierarchical Cache for Robust and Generalizable Point Cloud Analysis

# 摘要

> 本文提出了一种通用解决方案，使点云识别模型能够处理测试时的分布变化。与以往依赖训练数据的方法不同，这些数据在在线推理过程中往往无法获取，并且仅限于识别训练时预定义的固定点云类别集。我们探索了一个更具现实意义且更具挑战性的场景：仅基于在线测试数据对模型进行调整，使其能够识别测试时的已见类别以及全新的未知类别。为此，我们开发了Point-Cache，这是一种分层缓存模型，能够捕捉在线测试样本的关键线索，特别关注点云的全局结构及其局部细节。Point-Cache作为丰富的3D知识库，通过动态管理来优先纳入高质量样本。我们的方法设计为即插即用模块，可灵活集成到大型多模态3D模型中，支持开放词汇表的点云识别。值得注意的是，我们的解决方案运行效率与零样本推理相当，因为它完全不需要训练。Point-Cache在8个具有挑战性的基准测试和4个代表性的大型3D模型上均取得了显著提升，充分证明了其有效性。代码可在https://github.com/auniquesun/Point-Cache获取。

> This paper proposes a general solution to enable point cloud recognition models to handle distribution shifts at test time. Unlike prior methods, which rely heavily on training data-often inaccessible during online inference-and are limited to recognizing a fixed set of point cloud classes predefined during training, we explore a more practical and challenging scenario: adapting the model solely based on online test data to recognize both previously seen classes and novel, unseen classes at test time. To this end, we develop Point-Cache, a hierarchical cache model that captures essential clues of online test samples, particularly focusing on the global structure of point clouds and their local-part details. Point-Cache, which serves as a rich 3D knowledge base, is dynamically managed to prioritize the inclusion of high-quality samples. Designed as a plug-and-play module, our method can be flexibly integrated into large multimodal 3D models to support open-vocabulary point cloud recognition. Notably, our solution operates with efficiency comparable to zero-shot inference, as it is entirely training-free. Point-Cache demonstrates substantial gains across 8 challenging benchmarks and 4 representative large 3D models, highlighting its effectiveness. Code is available at https://github.com/auniquesun/Point-Cache.

[Arxiv](https://arxiv.org/abs/2503.12150)