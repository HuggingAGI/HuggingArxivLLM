# # 提示后仍存偏见：大型语言模型中的持续歧视

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Bias after Prompting: Persistent Discrimination in Large Language Models

# 摘要

> 先前关于偏见迁移假说（BTH）的研究存在一个危险假设：偏见不会从预训练大型语言模型（LLMs）迁移至适配模型。我们通过在提示适配下的因果模型中研究BTH推翻了这一假设，因为提示是现实应用中一种极为流行且易于使用的适配策略。与先前研究不同，我们发现偏见可通过提示迁移，且主流的基于提示的缓解方法无法持续阻止偏见迁移。具体而言，内在偏见与提示适配后的偏见在不同人群和任务中的相关性保持中等到强烈——例如，共指消解任务中的性别（rho ≥ 0.94），问答任务中的年龄（rho ≥ 0.98）和宗教（rho ≥ 0.69）。此外，当改变少样本组合参数（如样本量、刻板印象内容、职业分布和代表性平衡）时，偏见仍保持强相关性（rho ≥ 0.90）。我们评估了多种基于提示的去偏策略，发现不同方法各有优势，但均无法在不同模型、任务或人群中持续减少偏见迁移。这些结果表明，纠正内在模型中的偏见（并可能提升推理能力）可防止偏见向下游任务传播。

> A dangerous assumption that can be made from prior work on the bias transfer hypothesis (BTH) is that biases do not transfer from pre-trained large language models (LLMs) to adapted models. We invalidate this assumption by studying the BTH in causal models under prompt adaptations, as prompting is an extremely popular and accessible adaptation strategy used in real-world applications. In contrast to prior work, we find that biases can transfer through prompting and that popular prompt-based mitigation methods do not consistently prevent biases from transferring. Specifically, the correlation between intrinsic biases and those after prompt adaptation remain moderate to strong across demographics and tasks -- for example, gender (rho >= 0.94) in co-reference resolution, and age (rho >= 0.98) and religion (rho >= 0.69) in question answering. Further, we find that biases remain strongly correlated when varying few-shot composition parameters, such as sample size, stereotypical content, occupational distribution and representational balance (rho >= 0.90). We evaluate several prompt-based debiasing strategies and find that different approaches have distinct strengths, but none consistently reduce bias transfer across models, tasks or demographics. These results demonstrate that correcting bias, and potentially improving reasoning ability, in intrinsic models may prevent propagation of biases to downstream tasks.

[Arxiv](https://arxiv.org/abs/2509.08146)