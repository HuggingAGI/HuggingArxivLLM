# ObjectVLA：端到端无需演示的开放世界物体操作

发布时间：2025年02月26日

`其他` `机器人` `机器人学习`

> ObjectVLA: End-to-End Open-World Object Manipulation Without Demonstration

# 摘要

> 模仿学习在教授机器人灵巧操作技能方面表现出色，但其依赖大量人类演示数据的特性限制了在动态真实环境中的应用。物体泛化是其中一大挑战：机器人在完成“传递苹果”等任务后，往往难以将技能迁移到语义相似但视觉不同的物体，如“传递桃子”。此前研究尚未充分解决同一类别以外新物体的泛化问题。本文提出了一种通过视觉-语言-动作（VLA）模型实现物体泛化的简单而有效的方法——	extbf{ObjectVLA}。该模型无需针对每个新物体提供额外演示，即可实现技能迁移。通过视觉-语言配对数据，我们的方法以轻量级方式将物体信息注入模型，建立物体与动作间的隐式关联。实验表明，ObjectVLA在100个新物体上实现了64%的成功率。我们还提出了一种更简便的方法，通过智能手机拍摄少量图像并微调模型，进一步提升物体泛化能力。这些结果表明，我们的方法在减少演示需求、实现物体级别泛化方面具有显著优势，为更灵活和可扩展的机器人学习系统奠定了基础。

> Imitation learning has proven to be highly effective in teaching robots dexterous manipulation skills. However, it typically relies on large amounts of human demonstration data, which limits its scalability and applicability in dynamic, real-world environments. One key challenge in this context is object generalization, where a robot trained to perform a task with one object, such as "hand over the apple," struggles to transfer its skills to a semantically similar but visually different object, such as "hand over the peach." This gap in generalization to new objects beyond those in the same category has yet to be adequately addressed in previous work on end-to-end visuomotor policy learning. In this paper, we present a simple yet effective approach for achieving object generalization through Vision-Language-Action (VLA) models, referred to as \textbf{ObjectVLA}. Our model enables robots to generalize learned skills to novel objects without requiring explicit human demonstrations for each new target object. By leveraging vision-language pair data, our method provides a lightweight and scalable way to inject knowledge about the target object, establishing an implicit link between the object and the desired action. We evaluate ObjectVLA on a real robotic platform, demonstrating its ability to generalize across 100 novel objects with a 64\% success rate in selecting objects not seen during training. Furthermore, we propose a more accessible method for enhancing object generalization in VLA models, using a smartphone to capture a few images and fine-tune the pre-trained model. These results highlight the effectiveness of our approach in enabling object-level generalization and reducing the need for extensive human demonstrations, paving the way for more flexible and scalable robotic learning systems.

[Arxiv](https://arxiv.org/abs/2502.19250)