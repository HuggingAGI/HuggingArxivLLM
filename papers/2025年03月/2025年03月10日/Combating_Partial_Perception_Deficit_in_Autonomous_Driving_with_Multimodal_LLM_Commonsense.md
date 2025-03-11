# 利用多模态LLM的常识，解决自动驾驶中的部分感知问题

发布时间：2025年03月10日

`LLM应用` `自动驾驶` `大型语言模型`

> Combating Partial Perception Deficit in Autonomous Driving with Multimodal LLM Commonsense

# 摘要

> 部分感知缺陷可能威胁自动驾驶的安全性，因为它们会干扰车辆对环境的理解。目前的解决方案通常采取立即停车或最小风险操作，这不仅恶化了交通流，还缺乏对罕见驾驶场景的灵活性。在本文中，我们提出了 LLM-RCO 框架，该框架利用大型语言模型将人类驾驶常识整合到面临感知缺陷的自动驾驶系统中。LLM-RCO 框架包含四个关键模块：风险推断、短期运动规划器、动作条件验证器和安全约束生成器。这些模块与动态驾驶环境互动，能够主动采取情境感知的控制动作，从而覆盖原始自动驾驶代理的控制策略。为了在这些具有挑战性的条件下提升安全性，我们构建了 DriveLM-Deficit 数据集，其中包含 53,895 个具有安全关键对象缺陷的视频片段，并附带了基于 LLM 的风险推断和运动规划微调的标注。在 CARLA 模拟器的不利驾驶条件下进行的大量实验表明，配备 LLM-RCO 的系统显著提升了驾驶性能，突显了其增强自动驾驶在不利感知缺陷下恢复能力的潜力。我们的结果还表明，经过 DriveLM-Deficit 数据集微调的 LLM 能够在感知缺陷的背景下实现更积极主动的动作，而不是保守的停车。

> Partial perception deficits can compromise autonomous vehicle safety by disrupting environmental understanding. Current protocols typically respond with immediate stops or minimal-risk maneuvers, worsening traffic flow and lacking flexibility for rare driving scenarios. In this paper, we propose LLM-RCO, a framework leveraging large language models to integrate human-like driving commonsense into autonomous systems facing perception deficits. LLM-RCO features four key modules: hazard inference, short-term motion planner, action condition verifier, and safety constraint generator. These modules interact with the dynamic driving environment, enabling proactive and context-aware control actions to override the original control policy of autonomous agents. To improve safety in such challenging conditions, we construct DriveLM-Deficit, a dataset of 53,895 video clips featuring deficits of safety-critical objects, complete with annotations for LLM-based hazard inference and motion planning fine-tuning. Extensive experiments in adverse driving conditions with the CARLA simulator demonstrate that systems equipped with LLM-RCO significantly improve driving performance, highlighting its potential for enhancing autonomous driving resilience against adverse perception deficits. Our results also show that LLMs fine-tuned with DriveLM-Deficit can enable more proactive movements instead of conservative stops in the context of perception deficits.

[Arxiv](https://arxiv.org/abs/2503.07020)