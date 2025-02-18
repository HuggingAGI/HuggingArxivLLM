# 揭示算术差距：评估大型语言模型基本数值能力的基准

发布时间：2025年02月16日

`LLM理论

理由：这篇论文探讨了大型语言模型在数值推理任务中的表现及其不足，并提出了一个新的基准测试来评估和改进这些模型的能力。它涉及模型的理论能力和潜在改进，属于LLM理论的范畴。` `数值推理` `人工智能`

> Exposing Numeracy Gaps: A Benchmark to Evaluate Fundamental Numerical Abilities in Large Language Models

# 摘要

> 大型语言模型（LLMs）在文本生成和语义理解等自然语言处理任务中表现出色，但在基本算术、数值检索和数量比较等数值推理任务上的表现却令人失望。这种差距源于模型对表面级统计模式的依赖，而非真正理解数字的连续性。现有基准测试主要关注语言能力或结构化数学问题解决，忽视了现实场景中所需的基本数值推理能力。为此，我们提出了NumericBench，一个全面的基准测试，用于评估六种基本数值能力：数字识别、算术运算、上下文检索、比较、摘要和逻辑推理。NumericBench涵盖从合成数字列表到爬取的现实世界数据的各种数据集，解决了长上下文、噪声和多步推理等挑战。在GPT-4和DeepSeek等最先进的LLMs上进行的广泛实验揭示了数值推理方面的持续弱点，突显了改进数值感知语言建模的迫切需求。该基准已发布在：https://github.com/TreeAI-Lab/NumericBench。


> Large Language Models (LLMs) have demonstrated impressive capabilities in natural language processing tasks, such as text generation and semantic understanding. However, their performance on numerical reasoning tasks, such as basic arithmetic, numerical retrieval, and magnitude comparison, remains surprisingly poor. This gap arises from their reliance on surface-level statistical patterns rather than understanding numbers as continuous magnitudes. Existing benchmarks primarily focus on either linguistic competence or structured mathematical problem-solving, neglecting fundamental numerical reasoning required in real-world scenarios. To bridge this gap, we propose NumericBench, a comprehensive benchmark to evaluate six fundamental numerical capabilities: number recognition, arithmetic operations, contextual retrieval, comparison, summary, and logical reasoning. NumericBench includes datasets ranging from synthetic number lists to the crawled real-world data, addressing challenges like long contexts, noise, and multi-step reasoning. Extensive experiments on state-of-the-art LLMs, including GPT-4 and DeepSeek, reveal persistent weaknesses in numerical reasoning, highlighting the urgent need to improve numerically-aware language modeling. The benchmark is released in: https://github.com/TreeAI-Lab/NumericBench.

[Arxiv](https://arxiv.org/abs/2502.11075)