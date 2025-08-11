# 大型语言模型能否作为动态治疗规划器？一项基于先验知识注入视角的体外研究

发布时间：2025年08月06日

`LLM应用` `医疗信息化`

> Are Large Language Models Dynamic Treatment Planners? An In Silico Study from a Prior Knowledge Injection Angle

# 摘要

> 基于强化学习（RL）的动态治疗方案（DTRs）在自动化复杂临床决策方面展现出巨大潜力，但实际应用仍受限于复杂工程需求。近期大型语言模型（LLMs）的进步为这一领域提供了新思路：通过语言提示自然嵌入隐性知识和临床启发，无需特定环境训练。本研究在1型糖尿病模拟器中评估开源LLMs作为动态胰岛素给药代理的表现，将其零样本推理性能与专门训练的小型神经网络强化学习代理（SRAs）对比。研究发现，精心设计的零样本提示使较小规模的LLMs（如Qwen2.5-7B）在稳定患者群体中达到甚至超越SRAs的效果。然而，LLMs也存在明显局限性，例如在链式推理（CoT）提示下过于激进的胰岛素剂量，暴露出算术幻觉、时间误解和临床逻辑不一致等问题。显式推理隐含临床状态仅带来微小提升，凸显模型在捕捉复杂生理动态方面的局限性。本研究建议谨慎而乐观地将LLMs整合到临床工作流程中，强调提示工程、验证以及结合语言推理与生理建模的混合方法的重要性，以实现安全、稳健且临床有效的决策支持系统。

> Reinforcement learning (RL)-based dynamic treatment regimes (DTRs) hold promise for automating complex clinical decision-making, yet their practical deployment remains hindered by the intensive engineering required to inject clinical knowledge and ensure patient safety. Recent advancements in large language models (LLMs) suggest a complementary approach, where implicit prior knowledge and clinical heuristics are naturally embedded through linguistic prompts without requiring environment-specific training. In this study, we rigorously evaluate open-source LLMs as dynamic insulin dosing agents in an in silico Type 1 diabetes simulator, comparing their zero-shot inference performance against small neural network-based RL agents (SRAs) explicitly trained for the task. Our results indicate that carefully designed zero-shot prompts enable smaller LLMs (e.g., Qwen2.5-7B) to achieve comparable or superior clinical performance relative to extensively trained SRAs, particularly in stable patient cohorts. However, LLMs exhibit notable limitations, such as overly aggressive insulin dosing when prompted with chain-of-thought (CoT) reasoning, highlighting critical failure modes including arithmetic hallucination, temporal misinterpretation, and inconsistent clinical logic. Incorporating explicit reasoning about latent clinical states (e.g., meals) yielded minimal performance gains, underscoring the current model's limitations in capturing complex, hidden physiological dynamics solely through textual inference. Our findings advocate for cautious yet optimistic integration of LLMs into clinical workflows, emphasising the necessity of targeted prompt engineering, careful validation, and potentially hybrid approaches that combine linguistic reasoning with structured physiological modelling to achieve safe, robust, and clinically effective decision-support systems.

[Arxiv](https://arxiv.org/abs/2508.04755)