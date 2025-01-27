# MCRL4OR: 多模态对比学习在越野环境感知中的应用

发布时间：2025年01月23日

`其他

**理由**：这篇论文主要讨论的是自动驾驶车辆在越野环境中的感知问题，提出了一种多模态对比表示学习方法（MCRL4OR）。虽然涉及了多模态表示学习，但其核心内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `自动驾驶` `越野驾驶`

> MCRL4OR: Multimodal Contrastive Representation Learning for Off-Road Environmental Perception

# 摘要

> 大多数自动驾驶车辆（AVs）环境感知的研究聚焦于城市交通环境，这些环境中的感知对象主要来自人造场景，且可使用密集标注的大规模数据集训练监督学习模型。然而，由于越野环境的非结构化特性，手动标注大规模越野驾驶数据集极为困难。本文提出了一种多模态对比表示学习方法MCRL4OR，用于越野环境感知。该方法通过在对齐运动状态与视觉图像和控制动作的融合特征的过程中，联合学习处理视觉图像、运动状态和控制动作的三个编码器。这种对齐策略的因果逻辑在于，惯性运动状态是视觉传感器感知当前地形后采取控制动作的结果。实验中，我们使用大规模越野驾驶数据集对MCRL4OR进行预训练，并将学习到的多模态表示应用于越野驾驶场景中的多种下游感知任务。下游任务的优异表现验证了预训练多模态表示的优势。代码可在url{https://github.com/1uciusy/MCRL4OR}获取。

> Most studies on environmental perception for autonomous vehicles (AVs) focus on urban traffic environments, where the objects/stuff to be perceived are mainly from man-made scenes and scalable datasets with dense annotations can be used to train supervised learning models. By contrast, it is hard to densely annotate a large-scale off-road driving dataset manually due to the inherently unstructured nature of off-road environments. In this paper, we propose a Multimodal Contrastive Representation Learning approach for Off-Road environmental perception, namely MCRL4OR. This approach aims to jointly learn three encoders for processing visual images, locomotion states, and control actions by aligning the locomotion states with the fused features of visual images and control actions within a contrastive learning framework. The causation behind this alignment strategy is that the inertial locomotion state is the result of taking a certain control action under the current landform/terrain condition perceived by visual sensors. In experiments, we pre-train the MCRL4OR with a large-scale off-road driving dataset and adopt the learned multimodal representations for various downstream perception tasks in off-road driving scenarios. The superior performance in downstream tasks demonstrates the advantages of the pre-trained multimodal representations. The codes can be found in url{https://github.com/1uciusy/MCRL4OR}.

[Arxiv](https://arxiv.org/abs/2501.13988)