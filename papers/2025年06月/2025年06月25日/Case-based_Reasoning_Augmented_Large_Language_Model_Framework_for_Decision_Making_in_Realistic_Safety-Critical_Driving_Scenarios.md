# 基于案例推理的增强型大型语言模型框架，用于现实安全关键驾驶场景的决策制定

发布时间：2025年06月25日

`LLM应用

论文摘要：在安全关键场景下的驾驶需要快速、情境感知的决策，这些决策需要基于对情境的理解和经验推理。大型语言模型（LLMs）凭借其强大的通用推理能力，为这样的决策提供了有前途的基础。然而，由于领域适应、情境 grounding 以及缺乏在动态、高风险环境中做出可靠且可解释决策所需的经验知识，LLMs 直接应用于自动驾驶仍然存在限制。为了解决这一差距，本文提出了一种基于案例推理增强的大型语言模型（CBR-LLM）框架，用于复杂风险场景下的规避动作决策。我们的方法将来自车载摄像头视频输入的语义场景理解与相关过去驾驶案例的检索相结合，使 LLMs 能够生成既情境敏感又与人类一致的规避动作建议。在多个开源 LLM 上的实验表明，我们的框架提高了决策准确性、解释质量以及与人类专家行为的一致性。风险感知提示策略进一步增强了在不同风险类型下的性能，而基于相似性的案例检索在引导上下文学习方面始终优于随机采样。案例研究进一步展示了该框架在具有挑战性的现实条件下的鲁棒性，强调了其作为智能驾驶系统自适应且值得信赖的决策支持工具的潜力。

LLM应用` `自动驾驶` `人工智能`

> Case-based Reasoning Augmented Large Language Model Framework for Decision Making in Realistic Safety-Critical Driving Scenarios

# 摘要

> 在安全关键场景下的驾驶需要快速、情境感知的决策，这些决策需要基于对情境的理解和经验推理。大型语言模型（LLMs）凭借其强大的通用推理能力，为这样的决策提供了有前途的基础。然而，由于领域适应、情境 grounding 以及缺乏在动态、高风险环境中做出可靠且可解释决策所需的经验知识，LLMs 直接应用于自动驾驶仍然存在限制。为了解决这一差距，本文提出了一种基于案例推理增强的大型语言模型（CBR-LLM）框架，用于复杂风险场景下的规避动作决策。我们的方法将来自车载摄像头视频输入的语义场景理解与相关过去驾驶案例的检索相结合，使 LLMs 能够生成既情境敏感又与人类一致的规避动作建议。在多个开源 LLM 上的实验表明，我们的框架提高了决策准确性、解释质量以及与人类专家行为的一致性。风险感知提示策略进一步增强了在不同风险类型下的性能，而基于相似性的案例检索在引导上下文学习方面始终优于随机采样。案例研究进一步展示了该框架在具有挑战性的现实条件下的鲁棒性，强调了其作为智能驾驶系统自适应且值得信赖的决策支持工具的潜力。


> Driving in safety-critical scenarios requires quick, context-aware decision-making grounded in both situational understanding and experiential reasoning. Large Language Models (LLMs), with their powerful general-purpose reasoning capabilities, offer a promising foundation for such decision-making. However, their direct application to autonomous driving remains limited due to challenges in domain adaptation, contextual grounding, and the lack of experiential knowledge needed to make reliable and interpretable decisions in dynamic, high-risk environments. To address this gap, this paper presents a Case-Based Reasoning Augmented Large Language Model (CBR-LLM) framework for evasive maneuver decision-making in complex risk scenarios. Our approach integrates semantic scene understanding from dashcam video inputs with the retrieval of relevant past driving cases, enabling LLMs to generate maneuver recommendations that are both context-sensitive and human-aligned. Experiments across multiple open-source LLMs show that our framework improves decision accuracy, justification quality, and alignment with human expert behavior. Risk-aware prompting strategies further enhance performance across diverse risk types, while similarity-based case retrieval consistently outperforms random sampling in guiding in-context learning. Case studies further demonstrate the framework's robustness in challenging real-world conditions, underscoring its potential as an adaptive and trustworthy decision-support tool for intelligent driving systems.

[Arxiv](https://arxiv.org/abs/2506.20531)