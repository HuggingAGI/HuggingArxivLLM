# Auto-Bench：助力大型语言模型的科学发现自动化基准测试工具

发布时间：2025年02月21日

`LLM应用` `科学研究` `人工智能`

> Auto-Bench: An Automated Benchmark for Scientific Discovery in LLMs

# 摘要

> 大型语言模型（LLMs）的卓越表现引出了一个引人入胜的问题：它们能否像人类一样开展科学研究、发现新知，甚至成为AI科学家？科学发现是一个需要高效知识更新与编码的迭代过程，涉及环境理解、假设提出与行动推理。然而，目前尚无专门针对LLM代理的科学发现标准化基准。为填补这一空白，我们推出了一款全新的评估基准——《Auto-Bench》。它基于因果图发现的原则，全面涵盖了评估LLMs在自然与社会科学领域进行科学发现所需的关键能力。该基准要求模型揭示隐藏的结构并做出最优决策，包括生成合理解释。通过与知识库进行交互式对话，模型能够通过策略性干预逐步完善对潜在交互、化学与社会互动的理解。我们对GPT-4、Gemini、Qwen、Claude和Llama等前沿LLMs进行了评估，发现随着问题复杂度的增加，模型性能显著下降。这一结果凸显了当前机器与人类智能之间的显著差距，为未来LLMs的发展指明了重要方向。

> Given the remarkable performance of Large Language Models (LLMs), an important question arises: Can LLMs conduct human-like scientific research and discover new knowledge, and act as an AI scientist? Scientific discovery is an iterative process that demands efficient knowledge updating and encoding. It involves understanding the environment, identifying new hypotheses, and reasoning about actions; however, no standardized benchmark specifically designed for scientific discovery exists for LLM agents. In response to these limitations, we introduce a novel benchmark, \textit{Auto-Bench}, that encompasses necessary aspects to evaluate LLMs for scientific discovery in both natural and social sciences. Our benchmark is based on the principles of causal graph discovery. It challenges models to uncover hidden structures and make optimal decisions, which includes generating valid justifications. By engaging interactively with an oracle, the models iteratively refine their understanding of underlying interactions, the chemistry and social interactions, through strategic interventions. We evaluate state-of-the-art LLMs, including GPT-4, Gemini, Qwen, Claude, and Llama, and observe a significant performance drop as the problem complexity increases, which suggests an important gap between machine and human intelligence that future development of LLMs need to take into consideration.

[Arxiv](https://arxiv.org/abs/2502.15224)