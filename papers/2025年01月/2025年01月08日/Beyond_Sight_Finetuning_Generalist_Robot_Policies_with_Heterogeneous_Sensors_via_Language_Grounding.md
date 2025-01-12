# 超越视觉：基于语言基础，利用异构传感器微调通用机器人策略

发布时间：2025年01月08日

`Agent

理由：这篇论文主要讨论了一种名为FuSe的创新方法，通过自然语言作为跨模态的共同基础，使得在异构传感器模态上微调视觉运动通用策略成为可能。这种方法旨在提升机器人在多感官环境中的交互能力，特别是在视觉被遮挡时依赖触觉和听觉。论文的核心是提升机器人的感知和决策能力，使其能够更好地与环境互动，这符合Agent的定义，即能够感知环境并采取行动以实现目标的实体。因此，这篇论文应被分类为Agent。` `机器人` `多模态交互`

> Beyond Sight: Finetuning Generalist Robot Policies with Heterogeneous Sensors via Language Grounding

# 摘要

> # 摘要
与世界互动是一种多感官体验：实现高效的通用互动需要充分利用所有可用模态——视觉、触觉和听觉——以弥补部分观察的不足。例如，当视觉被遮挡时，机器人应依赖触觉和听觉。然而，当前最先进的通用机器人策略通常依赖于大规模数据集，仅从视觉和本体感受中预测动作。本文提出FuSe，一种创新方法，通过自然语言作为跨模态的共同基础，使得在异构传感器模态上微调视觉运动通用策略成为可能，即使这些模态的大规模数据集不易获得。我们结合多模态对比损失和基于感官的语言生成损失来编码高级语义。在机器人操作中，FuSe能够在零-shot设置下执行需要联合推理视觉、触觉和听觉的复杂任务，如多模态提示、组合跨模态提示以及与交互对象的描述。我们展示了该方法适用于多种通用策略，包括基于扩散的通用策略和大型视觉-语言-动作（VLA）模型。大量现实实验表明，FuSe将成功率提升了20%以上，远超所有基线。

> Interacting with the world is a multi-sensory experience: achieving effective general-purpose interaction requires making use of all available modalities -- including vision, touch, and audio -- to fill in gaps from partial observation. For example, when vision is occluded reaching into a bag, a robot should rely on its senses of touch and sound. However, state-of-the-art generalist robot policies are typically trained on large datasets to predict robot actions solely from visual and proprioceptive observations. In this work, we propose FuSe, a novel approach that enables finetuning visuomotor generalist policies on heterogeneous sensor modalities for which large datasets are not readily available by leveraging natural language as a common cross-modal grounding. We combine a multimodal contrastive loss with a sensory-grounded language generation loss to encode high-level semantics. In the context of robot manipulation, we show that FuSe enables performing challenging tasks that require reasoning jointly over modalities such as vision, touch, and sound in a zero-shot setting, such as multimodal prompting, compositional cross-modal prompting, and descriptions of objects it interacts with. We show that the same recipe is applicable to widely different generalist policies, including both diffusion-based generalist policies and large vision-language-action (VLA) models. Extensive experiments in the real world show that FuSeis able to increase success rates by over 20% compared to all considered baselines.

[Arxiv](https://arxiv.org/abs/2501.04693)