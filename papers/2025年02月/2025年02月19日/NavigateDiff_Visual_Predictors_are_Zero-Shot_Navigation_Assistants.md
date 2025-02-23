# NavigateDiff：视觉预测器助力零样本导航

发布时间：2025年02月19日

`Agent

理由：这篇论文主要探讨了家庭机器人在陌生环境中的导航问题，提出了一种结合预训练模型和视觉预测器的方法，以提升导航效率和泛化能力。其核心内容涉及机器人导航和自主决策，属于智能体（Agent）领域。` `机器人导航` `机器人学`

> NavigateDiff: Visual Predictors are Zero-Shot Navigation Assistants

# 摘要

> 在陌生环境中导航对家庭机器人来说是一个巨大挑战，需要具备识别和理解新型装饰与布局的能力。现有的强化学习方法由于依赖大量地图绘制和探索，无法直接迁移到新环境，导致效率低下。为了解决这一难题，我们尝试将预训练基础模型的逻辑知识和泛化能力应用到零样本导航中。通过结合大型视觉-语言模型与扩散网络，我们的方法\mname构建了一个视觉预测器，能够持续预测代理在下一步的潜在观察结果，从而辅助机器人生成更可靠的行动方案。为了适应导航的时间特性，我们引入了时间历史信息，确保预测图像与导航场景保持一致。此外，我们设计了一个信息融合框架，将预测的未来帧作为指导嵌入到目标到达策略中，从而有效解决下游图像导航任务。这一方法显著提升了模拟与真实环境中的导航控制和泛化能力。通过大量实验，我们验证了该方法的鲁棒性和多功能性，展现了其在提升机器人导航效率与效果方面的巨大潜力。

> Navigating unfamiliar environments presents significant challenges for household robots, requiring the ability to recognize and reason about novel decoration and layout. Existing reinforcement learning methods cannot be directly transferred to new environments, as they typically rely on extensive mapping and exploration, leading to time-consuming and inefficient. To address these challenges, we try to transfer the logical knowledge and the generalization ability of pre-trained foundation models to zero-shot navigation. By integrating a large vision-language model with a diffusion network, our approach named \mname ~constructs a visual predictor that continuously predicts the agent's potential observations in the next step which can assist robots generate robust actions. Furthermore, to adapt the temporal property of navigation, we introduce temporal historical information to ensure that the predicted image is aligned with the navigation scene. We then carefully designed an information fusion framework that embeds the predicted future frames as guidance into goal-reaching policy to solve downstream image navigation tasks. This approach enhances navigation control and generalization across both simulated and real-world environments. Through extensive experimentation, we demonstrate the robustness and versatility of our method, showcasing its potential to improve the efficiency and effectiveness of robotic navigation in diverse settings.

[Arxiv](https://arxiv.org/abs/2502.13894)