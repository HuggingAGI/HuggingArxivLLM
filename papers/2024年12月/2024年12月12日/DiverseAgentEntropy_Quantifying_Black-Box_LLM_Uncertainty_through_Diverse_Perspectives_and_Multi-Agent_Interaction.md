# DiverseAgentEntropy：从不同视角和多智能体交互来量化黑箱 LLM 的不确定性

发布时间：2024年12月12日

`LLM应用` `语言模型` `不确定性评估`

> DiverseAgentEntropy: Quantifying Black-Box LLM Uncertainty through Diverse Perspectives and Multi-Agent Interaction

# 摘要

> 在大型语言模型（LLMs）的事实参数知识中，尤其是在黑箱环境下，量化其不确定性是一项重大挑战。现有的通过评估对原始查询的响应自洽性来衡量模型不确定性的方法，往往无法捕捉到真正的不确定性。模型可能对原始查询的回答始终如一但却是错误的，也可能对同一查询的不同角度的各种问题给出正确回答，反之亦然。在本文中，我们提出了一种新方法——DiverseAgentEntropy，基于多智能体交互来评估模型的不确定性。假设模型确定的话，对于同一原始查询的各种不同问题，它应始终能回忆起对原始查询的答案。我们还实施了弃权策略，在不确定性高时不作出回答。我们的方法能更准确地预测模型的可靠性，进一步检测幻觉，表现优于其他基于自洽性的方法。此外，它表明现有模型即便知道正确答案，在面对同一查询的各种不同问题时，也常常无法始终给出正确答案。

> Quantifying the uncertainty in the factual parametric knowledge of Large Language Models (LLMs), especially in a black-box setting, poses a significant challenge. Existing methods, which gauge a model's uncertainty through evaluating self-consistency in responses to the original query, do not always capture true uncertainty. Models might respond consistently to the origin query with a wrong answer, yet respond correctly to varied questions from different perspectives about the same query, and vice versa. In this paper, we propose a novel method, DiverseAgentEntropy, for evaluating a model's uncertainty using multi-agent interaction under the assumption that if a model is certain, it should consistently recall the answer to the original query across a diverse collection of questions about the same original query. We further implement an abstention policy to withhold responses when uncertainty is high. Our method offers a more accurate prediction of the model's reliability and further detects hallucinations, outperforming other self-consistency-based methods. Additionally, it demonstrates that existing models often fail to consistently retrieve the correct answer to the same query under diverse varied questions even when knowing the correct answer.

[Arxiv](https://arxiv.org/abs/2412.09572)