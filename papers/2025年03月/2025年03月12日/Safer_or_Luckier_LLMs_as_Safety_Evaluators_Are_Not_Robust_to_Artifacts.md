# LLM作为安全评估器：是更安全还是只是更幸运？它们对人工制品的鲁棒性不足

发布时间：2025年03月12日

`LLM应用` `内容安全` `评估方法`

> Safer or Luckier? LLMs as Safety Evaluators Are Not Robust to Artifacts

# 摘要

> 大型语言模型（LLMs）越来越多地被用作自动评估器，用于评估生成内容的安全性，但它们的可靠性仍有待验证。本研究对11种LLM评估模型进行了全面评估，重点关注其在关键安全领域的表现，包括自洽性、与人类判断的一致性以及对输入artifacts的敏感性。研究发现，LLM评估器中的偏见可能导致对内容安全性的判断产生显著偏差，甚至高达98%。令人意外的是，更大的模型并不总是更 robust，而较小的模型有时在特定artifacts面前表现得更 robust。为了改善这一问题，我们提出了基于陪审团的评估方法，通过聚合多个模型的决策来提升评估的可靠性和一致性。然而，即使在最佳陪审团配置下，对artifacts的敏感性仍然存在。这些发现强调了开发多样化且抗artifacts的方法的迫切需求，以确保安全评估的可靠性。

> Large Language Models (LLMs) are increasingly employed as automated evaluators to assess the safety of generated content, yet their reliability in this role remains uncertain. This study evaluates a diverse set of 11 LLM judge models across critical safety domains, examining three key aspects: self-consistency in repeated judging tasks, alignment with human judgments, and susceptibility to input artifacts such as apologetic or verbose phrasing. Our findings reveal that biases in LLM judges can significantly distort the final verdict on which content source is safer, undermining the validity of comparative evaluations. Notably, apologetic language artifacts alone can skew evaluator preferences by up to 98\%. Contrary to expectations, larger models do not consistently exhibit greater robustness, while smaller models sometimes show higher resistance to specific artifacts. To mitigate LLM evaluator robustness issues, we investigate jury-based evaluations aggregating decisions from multiple models. Although this approach both improves robustness and enhances alignment to human judgements, artifact sensitivity persists even with the best jury configurations. These results highlight the urgent need for diversified, artifact-resistant methodologies to ensure reliable safety assessments.

[Arxiv](https://arxiv.org/abs/2503.09347)