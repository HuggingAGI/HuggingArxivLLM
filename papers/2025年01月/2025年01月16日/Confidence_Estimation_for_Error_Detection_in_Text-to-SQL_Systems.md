# 文本到SQL系统中错误检测的置信度估计

发布时间：2025年01月16日

`LLM应用

**理由**：该论文主要探讨了如何将选择性分类器集成到Text-to-SQL系统中，以解决LLMs在自然语言到SQL查询转换中的泛化和解释性置信度问题。这属于LLM在实际应用中的优化和改进，因此归类为LLM应用。` `数据库`

> Confidence Estimation for Error Detection in Text-to-SQL Systems

# 摘要

> Text-to-SQL 让用户能够通过自然语言与数据库交互，简化了信息检索与合成。尽管 LLMs 在将自然语言问题转换为 SQL 查询方面表现出色，但其广泛应用仍面临两大挑战：一是实现多样化查询的鲁棒泛化，二是确保预测的解释性置信度。为解决这些问题，我们研究了将选择性分类器集成到 Text-to-SQL 系统中的方法。通过基于熵的置信度估计与选择性分类器，我们分析了覆盖率与风险之间的权衡，并评估其对模型整体性能的影响。此外，我们还探索了模型的初始校准，并通过校准技术提升置信度与准确性之间的对齐。实验结果显示，编码器-解码器 T5 的校准效果优于上下文学习 GPT 4 和解码器 Llama 3，因此基于熵的外部选择性分类器表现更佳。研究还发现，在错误检测方面，选择性分类器更倾向于检测与无关问题相关的错误，而非错误的查询生成。

> Text-to-SQL enables users to interact with databases through natural language, simplifying the retrieval and synthesis of information. Despite the success of large language models (LLMs) in converting natural language questions into SQL queries, their broader adoption is limited by two main challenges: achieving robust generalization across diverse queries and ensuring interpretative confidence in their predictions. To tackle these issues, our research investigates the integration of selective classifiers into Text-to-SQL systems. We analyse the trade-off between coverage and risk using entropy based confidence estimation with selective classifiers and assess its impact on the overall performance of Text-to-SQL models. Additionally, we explore the models' initial calibration and improve it with calibration techniques for better model alignment between confidence and accuracy. Our experimental results show that encoder-decoder T5 is better calibrated than in-context-learning GPT 4 and decoder-only Llama 3, thus the designated external entropy-based selective classifier has better performance. The study also reveal that, in terms of error detection, selective classifier with a higher probability detects errors associated with irrelevant questions rather than incorrect query generations.

[Arxiv](https://arxiv.org/abs/2501.09527)