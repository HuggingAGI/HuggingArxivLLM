# MLRC-Bench：语言智能体是否能够解决机器学习研究挑战？

发布时间：2025年04月13日

`LLM应用

理由：这篇论文主要探讨了语言模型代理（LLM代理）在科学发现领域的评估方法，特别是通过创建一个新的基准MLRC-Bench来量化这些代理的表现。论文关注的是如何客观评估LLM代理在研究竞赛中的表现，以及它们在提出和实施新研究方法方面的能力。这涉及到LLM在实际应用中的表现和评估，因此归类为LLM应用。` `机器学习` `研究评估`

> MLRC-Bench: Can Language Agents Solve Machine Learning Research Challenges?

# 摘要

> 现有对 LLM 代理在科学发现领域的评估缺乏客观基准和指标来衡量其方法的可行性。为此，我们推出了 MLRC-Bench，一个专注于量化语言代理在机器学习研究竞赛中表现的新基准。与 OpenAI 的 MLE-Bench 和 METR 的 RE-Bench 等现有基准不同，MLRC-Bench 关注需要创新方法的开放性研究问题，而非仅通过工程努力即可解决的任务。与 AI Scientist 等先前工作不同，MLRC-Bench 不仅评估端到端代理管道，更专注于衡量提出和实施新研究方法的关键环节，并采用全新设计的严格协议和客观指标进行评估。我们精心挑选的 7 个竞赛任务揭示了 LLM 代理面临的重大挑战。即使表现最佳的代理 gemini-exp-1206 也只能在基线与顶尖人类得分间缩小 9.3% 的差距。此外，我们发现 LLM 评判的创新性与其在前沿 ML 问题上的实际表现存在显著偏差。MLRC-Bench 作为一个动态基准，将随着新的 ML 竞赛不断扩展，旨在推动对 AI 研究能力的严谨和客观评估。

> Existing evaluation of large language model (LLM) agents on scientific discovery lacks objective baselines and metrics to assess the viability of their proposed methods. To address this issue, we introduce MLRC-Bench, a benchmark designed to quantify how effectively language agents can tackle challenging Machine Learning (ML) Research Competitions. Our benchmark highlights open research problems that demand novel methodologies, in contrast to recent benchmarks such as OpenAI's MLE-Bench (Chan et al., 2024) and METR's RE-Bench (Wijk et al., 2024), which focus on well-established research tasks that are largely solvable through sufficient engineering effort. Unlike prior work, e.g., AI Scientist (Lu et al., 2024b), which evaluates the end-to-end agentic pipeline by using LLM-as-a-judge, MLRC-Bench measures the key steps of proposing and implementing novel research methods and evaluates them with newly proposed rigorous protocol and objective metrics. Our curated suite of 7 competition tasks reveals significant challenges for LLM agents. Even the best-performing tested agent (gemini-exp-1206 under MLAB (Huang et al., 2024a)) closes only 9.3% of the gap between baseline and top human participant scores. Furthermore, our analysis reveals a misalignment between the LLM-judged innovation and their actual performance on cutting-edge ML research problems. MLRC-Bench is a dynamic benchmark, which is designed to continually grow with new ML competitions to encourage rigorous and objective evaluations of AI's research capabilities.

[Arxiv](https://arxiv.org/abs/2504.09702)