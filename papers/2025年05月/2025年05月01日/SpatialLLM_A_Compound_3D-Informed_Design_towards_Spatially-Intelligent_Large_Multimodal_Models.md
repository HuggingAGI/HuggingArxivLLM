# # 空间智能大模型：基于3D信息融合的空间智能多模态模型设计

发布时间：2025年05月01日

`LLM理论` `人工智能` `计算机视觉`

> SpatialLLM: A Compound 3D-Informed Design towards Spatially-Intelligent Large Multimodal Models

# 摘要

> 人类天生具备理解三维空间关系的能力，这让人类能够进行复杂的推理，比如预测不同方向车辆的碰撞。不过，当前的大型多模态模型（LMMs）却缺乏这种三维空间推理能力。这一限制源于三维训练数据的稀缺性以及现有模型设计对二维数据的偏见。在本文中，我们系统性地研究了三维信息数据、架构和训练设置的影响，并推出了SpatialLLM——一款具备先进三维空间推理能力的大型多模态模型。为了解决数据限制问题，我们开发了两类基于三维信息的训练数据集：（1）专注于物体三维位置和朝向的探测数据，以及（2）用于复杂空间关系的对话数据。值得注意的是，我们是首个整理包含真实图像中三维朝向关系的VQA数据的研究团队。此外，我们系统性地将这两类训练数据与多模态模型的架构和训练设计相结合，为实现更优的三维推理能力提供了最佳设计路线图。我们的SpatialLLM推动了机器向具备高度三维推理能力的方向发展，相较于GPT-4o，性能提升了8.7%。我们系统的实证设计及其研究成果为未来在此领域的研究提供了宝贵的见解。

> Humans naturally understand 3D spatial relationships, enabling complex reasoning like predicting collisions of vehicles from different directions. Current large multimodal models (LMMs), however, lack of this capability of 3D spatial reasoning. This limitation stems from the scarcity of 3D training data and the bias in current model designs toward 2D data. In this paper, we systematically study the impact of 3D-informed data, architecture, and training setups, introducing SpatialLLM, a large multi-modal model with advanced 3D spatial reasoning abilities. To address data limitations, we develop two types of 3D-informed training datasets: (1) 3D-informed probing data focused on object's 3D location and orientation, and (2) 3D-informed conversation data for complex spatial relationships. Notably, we are the first to curate VQA data that incorporate 3D orientation relationships on real images. Furthermore, we systematically integrate these two types of training data with the architectural and training designs of LMMs, providing a roadmap for optimal design aimed at achieving superior 3D reasoning capabilities. Our SpatialLLM advances machines toward highly capable 3D-informed reasoning, surpassing GPT-4o performance by 8.7%. Our systematic empirical design and the resulting findings offer valuable insights for future research in this direction.

[Arxiv](https://arxiv.org/abs/2505.00788)