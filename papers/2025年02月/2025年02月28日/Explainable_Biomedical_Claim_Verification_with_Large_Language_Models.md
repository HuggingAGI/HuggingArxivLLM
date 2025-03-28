# 基于大型语言模型的可解释生物医学声明验证

发布时间：2025年02月28日

`LLM应用` `生物医学` `人工智能`

> Explainable Biomedical Claim Verification with Large Language Models

# 摘要

> 生物医学声明的验证对医疗决策、公共卫生政策及科学研究至关重要。我们提出了一种交互式验证系统，将大型语言模型（LLMs）、透明的模型解释与用户引导的论证相结合。系统中，用户首先从持续更新的医学文献库中检索相关研究，并通过任务自适应推理框架，观察不同LLMs如何执行自然语言推理（NLI），将每项研究分类为“支持”、“矛盾”或“信息不足”。用户可通过SHAP值深入理解模型推理过程，查看单词级别对最终结果的贡献。这种结合使模型决策过程更加透明易懂。总结阶段，用户可选择由LLMs生成的叙述性论证整合结果，形成基于共识的最终决策，助力安全且可问责的AI辅助生物医学决策。未来，我们计划将此可解释验证系统整合到更广泛的证据合成框架中，支持高效的人机协作。

> Verification of biomedical claims is critical for healthcare decision-making, public health policy and scientific research. We present an interactive biomedical claim verification system by integrating LLMs, transparent model explanations, and user-guided justification. In the system, users first retrieve relevant scientific studies from a persistent medical literature corpus and explore how different LLMs perform natural language inference (NLI) within task-adaptive reasoning framework to classify each study as "Support," "Contradict," or "Not Enough Information" regarding the claim. Users can examine the model's reasoning process with additional insights provided by SHAP values that highlight word-level contributions to the final result. This combination enables a more transparent and interpretable evaluation of the model's decision-making process. A summary stage allows users to consolidate the results by selecting a result with narrative justification generated by LLMs. As a result, a consensus-based final decision is summarized for each retrieved study, aiming safe and accountable AI-assisted decision-making in biomedical contexts. We aim to integrate this explainable verification system as a component within a broader evidence synthesis framework to support human-AI collaboration.

[Arxiv](https://arxiv.org/abs/2502.21014)