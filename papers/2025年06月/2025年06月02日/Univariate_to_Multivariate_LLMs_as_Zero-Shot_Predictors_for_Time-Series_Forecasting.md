# 从单变量到多变量：LLMs在时间序列预测中的零样本预测能力

发布时间：2025年06月02日

`LLM应用` `时间序列预测` `数据分析`

> Univariate to Multivariate: LLMs as Zero-Shot Predictors for Time-Series Forecasting

# 摘要

> 时间序列预测在许多现实世界动态系统中具有重要意义。近期研究提出了使用大型语言模型（LLMs）进行时间序列预测，得益于其强大的泛化能力和无需大量预训练即可表现良好的能力。然而，LLMs在处理复杂、噪声和多变量时间序列数据方面的有效性仍待进一步探索。为解决这一问题，我们提出了LLMPred方法，通过将时间序列转换为文本并输入到LLMs中进行零样本预测，同时结合两种主要的数据预处理技术来提升LLM的时间序列预测能力。首先，我们采用时间序列序列分解方法，以提高对复杂和噪声单变量序列的预测准确性。其次，我们通过一种轻量级提示处理策略，将单变量预测能力扩展到多变量数据。通过在较小规模的LLMs（如Llama 2 7B、Llama 3.2 3B、GPT-4o-mini和DeepSeek 7B）上进行的大量实验表明，LLMPred相比现有最先进基线方法取得了具有竞争力甚至更优的性能。此外，全面的消融实验进一步凸显了LLMPred中所提出关键组件的重要性。

> Time-series prediction or forecasting is critical across many real-world dynamic systems, and recent studies have proposed using Large Language Models (LLMs) for this task due to their strong generalization capabilities and ability to perform well without extensive pre-training. However, their effectiveness in handling complex, noisy, and multivariate time-series data remains underexplored. To address this, we propose LLMPred which enhances LLM-based time-series prediction by converting time-series sequences into text and feeding them to LLMs for zero shot prediction along with two main data pre-processing techniques. First, we apply time-series sequence decomposition to facilitate accurate prediction on complex and noisy univariate sequences. Second, we extend this univariate prediction capability to multivariate data using a lightweight prompt-processing strategy. Extensive experiments with smaller LLMs such as Llama 2 7B, Llama 3.2 3B, GPT-4o-mini, and DeepSeek 7B demonstrate that LLMPred achieves competitive or superior performance compared to state-of-the-art baselines. Additionally, a thorough ablation study highlights the importance of the key components proposed in LLMPred.

[Arxiv](https://arxiv.org/abs/2506.02389)