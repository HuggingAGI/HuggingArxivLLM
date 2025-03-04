# 个性化因果图推理赋能大型语言模型：以饮食建议为案例研究

发布时间：2025年02月28日

`LLM应用` `营养学`

> Personalized Causal Graph Reasoning for LLMs: A Case Study on Dietary Recommendations

# 摘要

> # 个性化因果图推理

大型语言模型 (LLMs) 虽然在常识推理方面表现出色，但在处理多因素个人数据的个性化推理任务时却面临挑战。这种局限性限制了它们在需要针对个人提供上下文感知决策的领域中的应用。

本文提出了一种基于个性化因果图推理的智能体框架，通过整合从个人数据中构建的因果图来提升 LLM 的推理能力。这些因果图为 LLM 的推理过程提供了指导基础。

我们在一个以营养为导向的饮食建议案例研究中验证了这一方法。由于隐含的个人独特饮食效果，该任务需要个性化推理。我们还提出了一种反事实评估方法，用于估计 LLM 推荐食物在血糖管理中的效果。

实验结果显示，与之前的方案相比，提出的方法在三个时间窗口内有效降低了平均血糖 iAUC，证明了其在个性化饮食建议方面的高效性。此外，通过让 LLM 作为评估者的实验结果表明，我们的方法显著提升了推理过程中的个性化水平。

> Large Language Models (LLMs) effectively leverage common-sense knowledge for general reasoning, yet they struggle with personalized reasoning when tasked with interpreting multifactor personal data. This limitation restricts their applicability in domains that require context-aware decision-making tailored to individuals. This paper introduces Personalized Causal Graph Reasoning as an agentic framework that enhances LLM reasoning by incorporating personal causal graphs derived from data of individuals. These graphs provide a foundation that guides the LLM's reasoning process. We evaluate it on a case study on nutrient-oriented dietary recommendations, which requires personal reasoning due to the implicit unique dietary effects. We propose a counterfactual evaluation to estimate the efficiency of LLM-recommended foods for glucose management. Results demonstrate that the proposed method efficiently provides personalized dietary recommendations to reduce average glucose iAUC across three time windows, which outperforms the previous approach. LLM-as-a-judge evaluation results indicate that our proposed method enhances personalization in the reasoning process.

[Arxiv](https://arxiv.org/abs/2503.00134)