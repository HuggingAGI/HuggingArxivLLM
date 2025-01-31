# <翻译失败>

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要探讨了DeepSeek R1语言模型在解决高难度数学问题上的表现，并与其他模型进行了对比。研究重点在于模型的应用效果和性能优化，属于LLM在实际任务中的应用研究，因此分类为LLM应用。` `语言模型`

> Token-Hungry, Yet Precise: DeepSeek R1 Highlights the Need for Multi-Step Reasoning Over Speed in MATH

# 摘要

> 本研究探索了DeepSeek R1语言模型在30个MATH数据集中的高难度数学问题上的表现，这些问题曾因时间限制而难倒其他模型。与以往研究不同，本次实验取消了时间限制，旨在验证DeepSeek R1基于token推理的架构是否能够通过多步推理实现精准求解。研究将DeepSeek R1与gemini-1.5-flash-8b、gpt-4o-mini-2024-07-18、llama3.1:8b和mistral-8b-latest四个模型在11种温度设置下进行对比。结果显示，DeepSeek R1在复杂问题上表现出更高的准确性，但其token生成量远超其他模型，印证了其token密集型的推理特点。研究揭示了LLM在数学问题求解中准确性与效率的权衡：DeepSeek R1虽在准确性上占优，但其大量token生成的方式可能不适用于需要快速响应的场景。研究强调了选择LLM时需考虑任务需求，并指出温度设置对性能优化的重要性。

> This study investigates the performance of the DeepSeek R1 language model on 30 challenging mathematical problems derived from the MATH dataset, problems that previously proved unsolvable by other models under time constraints. Unlike prior work, this research removes time limitations to explore whether DeepSeek R1's architecture, known for its reliance on token-based reasoning, can achieve accurate solutions through a multi-step process. The study compares DeepSeek R1 with four other models (gemini-1.5-flash-8b, gpt-4o-mini-2024-07-18, llama3.1:8b, and mistral-8b-latest) across 11 temperature settings. Results demonstrate that DeepSeek R1 achieves superior accuracy on these complex problems but generates significantly more tokens than other models, confirming its token-intensive approach. The findings highlight a trade-off between accuracy and efficiency in mathematical problem-solving with large language models: while DeepSeek R1 excels in accuracy, its reliance on extensive token generation may not be optimal for applications requiring rapid responses. The study underscores the importance of considering task-specific requirements when selecting an LLM and emphasizes the role of temperature settings in optimizing performance.

[Arxiv](https://arxiv.org/abs/2501.18576)