# 探究大型语言模型作为裁判的非传递性

发布时间：2025年02月19日

`LLM理论` `人工智能`

> Investigating Non-Transitivity in LLM-as-a-Judge

# 摘要

> 基于大型语言模型 (LLMs) 的自动评估方法正在成为评估 LLM 基础代理指令遵循能力的评估工具的标准选择。在此范式下最常见的方法，即与基线模型进行成对比较，关键取决于传递偏好的假设。然而，这一假设的有效性仍未得到充分探索。在本研究中，我们调查了 AlpacaEval 框架内是否存在非传递性，并分析其对模型排名的影响。我们发现，LLM 评估者表现出非传递偏好，导致排名对基线模型选择的高度敏感性。为缓解这一问题，我们证明将循环赛结合偏好 Bradley-Terry 模型可以生成更为可靠的排名。值得注意的是，我们的方法在与 Chatbot Arena 的对比中，显著提高了斯皮尔曼相关系数和肯德尔相关系数（分别为 95.0% 到 96.4% 和 82.1% 到 86.3%）。针对循环赛的计算成本问题，我们提出了瑞士智慧匹配锦标赛 (Swim)，通过动态匹配策略在保持计算效率的同时，捕捉循环赛的优势。

> Automatic evaluation methods based on large language models (LLMs) are emerging as the standard tool for assessing the instruction-following abilities of LLM-based agents. The most common method in this paradigm, pairwise comparisons with a baseline model, critically depends on the assumption of transitive preferences. However, the validity of this assumption remains largely unexplored. In this study, we investigate the presence of non-transitivity within the AlpacaEval framework and analyze its effects on model rankings. We find that LLM judges exhibit non-transitive preferences, leading to rankings that are sensitive to the choice of the baseline model. To mitigate this issue, we show that round-robin tournaments combined with Bradley-Terry models of preference can produce more reliable rankings. Notably, our method increases both the Spearman correlation and the Kendall correlation with Chatbot Arena (95.0% -> 96.4% and 82.1% -> 86.3% respectively). To address the computational cost of round-robin tournaments, we propose Swiss-Wise Iterative Matchmaking (Swim) tournaments, using a dynamic matching strategy to capture the benefits of round-robin tournaments while maintaining computational efficiency.

[Arxiv](https://arxiv.org/abs/2502.14074)