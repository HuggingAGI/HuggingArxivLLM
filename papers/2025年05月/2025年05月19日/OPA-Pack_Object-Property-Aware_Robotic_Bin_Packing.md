# OPA-Pack：面向对象属性的机器人装箱问题

发布时间：2025年05月19日

`其他` `机器人学`

> OPA-Pack: Object-Property-Aware Robotic Bin Packing

# 摘要

> 机器人装箱技术在电子商务和仓储等领域具有广泛应用。然而，现有研究虽注重通过优化装箱紧凑性来考虑物体形状，却忽视了人类在装箱时通常会考虑的重要属性，如易碎性、可食用性和化学性质。本文提出了一种全新的物体属性感知装箱框架OPA-Pack，这是首个在机器人装箱规划中引入物体属性考量的框架。技术层面，我们开发了一种基于检索增强生成和链式推理的物体属性识别方案，并构建了一个包含1032种日常物品属性标注的数据集。此外，我们设计了OPA-Net，旨在通过分离不兼容的物体对、减轻脆弱物体的压力，同时保持装箱紧凑性。OPA-Net包含属性嵌入层，用于编码待装物体的属性，以及脆性高度图和避让高度图，用于跟踪已装物体。我们还设计了一个奖励函数，并采用深度Q学习方案来训练OPA-Net。实验结果表明，OPA-Pack显著提高了分离不兼容物体对的准确率（从52%提升至95%），同时大幅降低了脆弱物体的压力（减少了29.4%），并保持了良好的装箱紧凑性。此外，我们在真实装箱平台上验证了OPA-Pack的有效性，展示了其在实际场景中的广泛应用前景。

> Robotic bin packing aids in a wide range of real-world scenarios such as e-commerce and warehouses. Yet, existing works focus mainly on considering the shape of objects to optimize packing compactness and neglect object properties such as fragility, edibility, and chemistry that humans typically consider when packing objects. This paper presents OPA-Pack (Object-Property-Aware Packing framework), the first framework that equips the robot with object property considerations in planning the object packing. Technical-wise, we develop a novel object property recognition scheme with retrieval-augmented generation and chain-of-thought reasoning, and build a dataset with object property annotations for 1,032 everyday objects. Also, we formulate OPA-Net, aiming to jointly separate incompatible object pairs and reduce pressure on fragile objects, while compacting the packing. Further, OPA-Net consists of a property embedding layer to encode the property of candidate objects to be packed, together with a fragility heightmap and an avoidance heightmap to keep track of the packed objects. Then, we design a reward function and adopt a deep Q-learning scheme to train OPA-Net. Experimental results manifest that OPA-Pack greatly improves the accuracy of separating incompatible object pairs (from 52% to 95%) and largely reduces pressure on fragile objects (by 29.4%), while maintaining good packing compactness. Besides, we demonstrate the effectiveness of OPA-Pack on a real packing platform, showcasing its practicality in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2505.13339)