# 链式思维下的样本复杂度优化：CoT 信息分析

发布时间：2025年05月21日

`LLM理论` `人工智能` `机器学习`

> CoT Information: Improved Sample Complexity under Chain-of-Thought Supervision

# 摘要

> 学习涉及多步骤推理的复杂函数对标准监督学习来说是一项重大挑战。链式思维（CoT）监督作为一种强大的实证技术应运而生，它通过提供中间推理步骤与最终输出，支撑了大型语言模型推理能力的诸多进展。本文研究了 CoT 监督下的统计学习理论。与标准监督学习不同，CoT 设置的一个关键特征是训练目标（CoT 风险）与测试目标（端到端风险）之间的不匹配。我们的分析核心在于通过明确关联这两种风险来实现更精确的样本复杂度界限。这一目标通过 *CoT 信息测度* 【数学公式】实现，它量化了观察推理过程所获得的额外判别能力。理论结果表明，CoT 监督相较于标准端到端监督可以实现显著更快的学习速率。具体而言，研究表明，要达到目标端到端误差 $ε$ 所需的样本复杂度按 $d/\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$ 规模化，其中 $d$ 是假设类复杂度的度量，这可能比标准的 $d/ε$ 速率快得多。我们还获得了基于 CoT 信息的信道理论下界。总体而言，这些结果表明 CoT 信息是链式思维监督下学习的统计复杂度的基本度量。

> Learning complex functions that involve multi-step reasoning poses a significant challenge for standard supervised learning from input-output examples. Chain-of-thought (CoT) supervision, which provides intermediate reasoning steps together with the final output, has emerged as a powerful empirical technique, underpinning much of the recent progress in the reasoning capabilities of large language models. This paper develops a statistical theory of learning under CoT supervision. A key characteristic of the CoT setting, in contrast to standard supervision, is the mismatch between the training objective (CoT risk) and the test objective (end-to-end risk). A central part of our analysis, distinguished from prior work, is explicitly linking those two types of risk to achieve sharper sample complexity bounds. This is achieved via the *CoT information measure* $\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$, which quantifies the additional discriminative power gained from observing the reasoning process. The main theoretical results demonstrate how CoT supervision can yield significantly faster learning rates compared to standard E2E supervision. Specifically, it is shown that the sample complexity required to achieve a target E2E error $ε$ scales as $d/\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$, where $d$ is a measure of hypothesis class complexity, which can be much faster than standard $d/ε$ rates. Information-theoretic lower bounds in terms of the CoT information are also obtained. Together, these results suggest that CoT information is a fundamental measure of statistical complexity for learning under chain-of-thought supervision.

[Arxiv](https://arxiv.org/abs/2505.15927)