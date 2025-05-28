# # Hume：在视觉语言动作模型中融入系统2思维

发布时间：2025年05月27日

`Agent` `机器人控制` `人工智能`

> Hume: Introducing System-2 Thinking in Visual-Language-Action Model

# 摘要

> 人类在处理物理世界中的复杂任务时，都会先进行深思熟虑。这种思维模式最近在提升大型语言模型（LLMs）解决数字领域复杂任务方面取得了显著进展。然而，对于与物理世界交互的机器人基础模型而言，深思熟虑的潜力仍未得到充分探索。在此工作中，我们提出了Hume：一个具备价值引导思维和级联动作去噪功能的双系统视觉语言动作（VLA）模型，探索其在灵巧机器人控制中的人类-like思维能力。

Hume的系统2通过扩展视觉语言动作模型主干，并添加一个新型价值查询头来估计预测动作的状态-动作价值，从而实现价值引导的思维。其通过重复采样多个动作候选，并根据状态-动作价值选择其中一个来实现价值引导的思维。Hume的系统1是一个轻量级的反应式视觉运动策略，它接收系统2选择的动作，并进行级联动作去噪以实现灵巧机器人控制。

在部署时，系统2以低频进行价值引导的思维，而系统1则异步接收系统2选择的动作候选，并实时预测流畅的动作。我们在多个模拟基准和真实机器人部署中展示了Hume超越现有最先进的视觉语言动作模型的性能。

> Humans practice slow thinking before performing actual actions when handling complex tasks in the physical world. This thinking paradigm, recently, has achieved remarkable advancement in boosting Large Language Models (LLMs) to solve complex tasks in digital domains. However, the potential of slow thinking remains largely unexplored for robotic foundation models interacting with the physical world. In this work, we propose Hume: a dual-system Vision-Language-Action (VLA) model with value-guided System-2 thinking and cascaded action denoising, exploring human-like thinking capabilities of Vision-Language-Action models for dexterous robot control. System 2 of Hume implements value-Guided thinking by extending a Vision-Language-Action Model backbone with a novel value-query head to estimate the state-action value of predicted actions. The value-guided thinking is conducted by repeat sampling multiple action candidates and selecting one according to state-action value. System 1 of Hume is a lightweight reactive visuomotor policy that takes System 2 selected action and performs cascaded action denoising for dexterous robot control. At deployment time, System 2 performs value-guided thinking at a low frequency while System 1 asynchronously receives the System 2 selected action candidate and predicts fluid actions in real time. We show that Hume outperforms the existing state-of-the-art Vision-Language-Action models across multiple simulation benchmark and real-robot deployments.

[Arxiv](https://arxiv.org/abs/2505.21432)