# 打破专注：大型语言模型中的上下文干扰难题

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在实际应用中的一个关键漏洞——上下文干扰漏洞（CDV），并提出了基于树的搜索方法来自动生成CDV示例。论文还研究了多种缓解策略，并发现后目标训练方法能有效提升模型对上下文干扰的鲁棒性。这些研究内容主要集中在LLMs的理论层面，探讨了模型的能力和知识层面的问题，因此应归类为LLM理论。` `模型可靠性`

> Breaking Focus: Contextual Distraction Curse in Large Language Models

# 摘要

> # 摘要
大型语言模型（LLMs）的最新进展彻底革新了生成系统，在各个领域表现卓越。然而，尽管这些模型在受控环境中表现出色，但在实际应用中，它们常常面临包含关键和无关细节的输入。我们的研究揭示了LLMs中的一个关键漏洞——上下文干扰漏洞（CDV）。当模型无法在语义连贯但无关的上下文修改的问题上保持稳定性能时，CDV现象便会出现。为了系统研究这一漏洞，我们提出了一种基于树的高效搜索方法，自动生成CDV示例。该方法在四个数据集中成功生成CDV示例，导致顶尖LLMs的平均性能下降约45%。为解决这一关键问题，我们探索了多种缓解策略，发现后目标训练方法能有效提升模型对上下文干扰的鲁棒性。研究结果表明，CDV本质上是能力层面的挑战，而非知识层面的问题，因为模型在没有干扰时能正确回答问题，展示了必要的知识。这呼吁社区在模型开发中重视CDV问题，以确保模型可靠性。代码已开源：https://github.com/wyf23187/LLM_CDV。

> Recent advances in Large Language Models (LLMs) have revolutionized generative systems, achieving excellent performance across diverse domains. Although these models perform well in controlled environments, their real-world applications frequently encounter inputs containing both essential and irrelevant details. Our investigation has revealed a critical vulnerability in LLMs, which we term Contextual Distraction Vulnerability (CDV). This phenomenon arises when models fail to maintain consistent performance on questions modified with semantically coherent but irrelevant context. To systematically investigate this vulnerability, we propose an efficient tree-based search methodology to automatically generate CDV examples. Our approach successfully generates CDV examples across four datasets, causing an average performance degradation of approximately 45% in state-of-the-art LLMs. To address this critical issue, we explore various mitigation strategies and find that post-targeted training approaches can effectively enhance model robustness against contextual distractions. Our findings highlight the fundamental nature of CDV as an ability-level challenge rather than a knowledge-level issue since models demonstrate the necessary knowledge by answering correctly in the absence of distractions. This calls the community's attention to address CDV during model development to ensure reliability. The code is available at https://github.com/wyf23187/LLM_CDV.

[Arxiv](https://arxiv.org/abs/2502.01609)