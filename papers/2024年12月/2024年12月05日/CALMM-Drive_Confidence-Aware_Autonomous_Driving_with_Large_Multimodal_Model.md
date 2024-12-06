# CALMM-Drive：采用大型多模态模型的置信度感知式自动驾驶

发布时间：2024年12月05日

`LLM应用` `自动驾驶`

> CALMM-Drive: Confidence-Aware Autonomous Driving with Large Multimodal Model

# 摘要

> 决策和运动规划对保障自动驾驶汽车（AVs）的安全与效率至关重要。现有的方法通常有两种范式：先决策再规划，或者先生成再评分。然而，前者常出现决策与规划不匹配的情况，后者在整合短期操作效用和长期战术效能时面临巨大挑战。为应对这些问题，我们推出了 CALMM-Drive，这是一个新型的置信度感知大型多模态模型（LMM）赋能的自动驾驶框架。我们的方法运用了 Top-K 置信度激发，有助于生成多个候选决策及其置信度水平。此外，我们还提出了一个新的规划模块，它集成了用于轨迹生成的扩散模型和分层细化流程，以找出最优路径。该框架能选出兼顾低层次解决方案质量和高层次战术置信度的最佳方案，降低一次性决策的风险，克服短视评分机制的局限。在 nuPlan 闭环模拟环境中的全面评估表明，CALMM-Drive 在实现可靠且灵活的驾驶性能方面成效显著，展现了在 LMM 赋能的 AVs 中整合不确定性方面的重大进步。代码在被接收后将会发布。

> Decision-making and motion planning are pivotal in ensuring the safety and efficiency of Autonomous Vehicles (AVs). Existing methodologies typically adopt two paradigms: decision then planning or generation then scoring. However, the former often struggles with misalignment between decisions and planning, while the latter encounters significant challenges in integrating short-term operational utility with long-term tactical efficacy. To address these issues, we introduce CALMM-Drive, a novel Confidence-Aware Large Multimodal Model (LMM) empowered Autonomous Driving framework. Our approach employs Top-K confidence elicitation, which facilitates the generation of multiple candidate decisions along with their confidence levels. Furthermore, we propose a novel planning module that integrates a diffusion model for trajectory generation and a hierarchical refinement process to find the optimal path. This framework enables the selection of the best plan accounting for both low-level solution quality and high-level tactical confidence, which mitigates the risks of one-shot decisions and overcomes the limitations induced by short-sighted scoring mechanisms. Comprehensive evaluations in nuPlan closed-loop simulation environments demonstrate the effectiveness of CALMM-Drive in achieving reliable and flexible driving performance, showcasing a significant advancement in the integration of uncertainty in LMM-empowered AVs. The code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2412.04209)