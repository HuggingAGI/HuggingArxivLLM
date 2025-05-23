# CoT 信息：在思维链（Chain-of-Thought）监督下优化了采样复杂度

发布时间：2025年05月21日

`LLM理论` `人工智能` `理论计算机科学`

> CoT Information: Improved Sample Complexity under Chain-of-Thought Supervision

# 摘要

> 学习涉及多步推理的复杂函数，对标准监督学习来说是一个重大挑战。链式思维（CoT）监督通过提供中间推理步骤和最终输出，成为提升大型语言模型推理能力的重要技术。本文针对CoT监督下的学习问题，构建了一个统计理论框架。与标准监督学习不同，CoT监督的一个显著特点是训练目标（CoT风险）与测试目标（端到端风险）之间的不匹配。我们的分析重点在于将这两种风险明确关联，以获得更精确的样本复杂度界限。这一目标通过*链式思维信息度量* $\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$ 实现，它量化了观察推理过程所获得的额外判别能力。主要理论成果表明，与标准端到端监督相比，CoT监督能够显著加快学习速率。具体而言，实现目标端到端误差 $ε$ 所需的样本复杂度按 $d/\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$ 的比例缩放，其中 $d$ 是假设类复杂度的度量，这可能比标准的 $d/ε$ 速率快得多。我们还获得了基于链式思维信息的下界。这些结果共同表明，链式思维信息是链式思维监督下学习的统计复杂度的基本度量。

> Learning complex functions that involve multi-step reasoning poses a significant challenge for standard supervised learning from input-output examples. Chain-of-thought (CoT) supervision, which provides intermediate reasoning steps together with the final output, has emerged as a powerful empirical technique, underpinning much of the recent progress in the reasoning capabilities of large language models. This paper develops a statistical theory of learning under CoT supervision. A key characteristic of the CoT setting, in contrast to standard supervision, is the mismatch between the training objective (CoT risk) and the test objective (end-to-end risk). A central part of our analysis, distinguished from prior work, is explicitly linking those two types of risk to achieve sharper sample complexity bounds. This is achieved via the *CoT information measure* $\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$, which quantifies the additional discriminative power gained from observing the reasoning process. The main theoretical results demonstrate how CoT supervision can yield significantly faster learning rates compared to standard E2E supervision. Specifically, it is shown that the sample complexity required to achieve a target E2E error $ε$ scales as $d/\mathcal{I}_{\mathcal{D}, h_\star}^{\mathrm{CoT}}(ε; \calH)$, where $d$ is a measure of hypothesis class complexity, which can be much faster than standard $d/ε$ rates. Information-theoretic lower bounds in terms of the CoT information are also obtained. Together, these results suggest that CoT information is a fundamental measure of statistical complexity for learning under chain-of-thought supervision.

[Arxiv](https://arxiv.org/abs/2505.15927)