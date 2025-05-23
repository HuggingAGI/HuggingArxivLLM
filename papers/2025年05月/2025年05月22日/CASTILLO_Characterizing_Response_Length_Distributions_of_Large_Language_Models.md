# CASTILLO: 研究大型语言模型的响应长度分布特性

发布时间：2025年05月22日

`LLM应用

摘要讨论了大语言模型（LLM）在实际应用中的计算资源管理挑战，特别是响应长度的估计和资源分配。引入了新的数据集和分析框架，支持主动调度和模型行为分析，属于模型应用层面的优化和研究。` `计算资源管理` `生成语言建模`

> CASTILLO: Characterizing Response Length Distributions of Large Language Models

# 摘要

> # 摘要  
    大语言模型（LLM）推理过程中的计算资源管理仍具挑战性，这主要源于自回归文本生成的随机性和变长特性。提前准确估计响应长度能够实现主动资源分配，但现有方法要么使文本生成偏向特定长度，要么依赖忽略模型和提示特异性变异的假设。  
    我们引入了CASTILLO数据集，该数据集描述了在七个不同的遵循指令语料库上评估的13个广泛使用的开源LLM的响应长度分布。对于每个$\langle$prompt, model$angle$样本对，我们使用固定的解码超参数生成10个独立的完成，记录每个响应的token长度，并发布汇总统计信息（均值、标准差、百分位数），以及最短和最长的完成，以及确切的生成设置。  
    我们的分析揭示了响应长度的跨模型和跨样本的显著变异性（即使在相同的生成设置下），以及特定于模型的行为和仅在部分响应中出现的文本退化现象。CASTILLO支持主动调度的预测模型开发，并为分析特定于模型的生成行为提供了一个系统化的框架。我们公开发布了该数据集和代码，以促进生成语言建模与系统研究的交叉领域发展。

> Efficiently managing compute resources for Large Language Model (LLM) inference remains challenging due to the inherently stochastic and variable lengths of autoregressive text generation. Accurately estimating response lengths in advance enables proactive resource allocation, yet existing approaches either bias text generation towards certain lengths or rely on assumptions that ignore model- and prompt-specific variability. We introduce CASTILLO, a dataset characterizing response length distributions across 13 widely-used open-source LLMs evaluated on seven distinct instruction-following corpora. For each $\langle$prompt, model$\rangle$ sample pair, we generate 10 independent completions using fixed decoding hyper-parameters, record the token length of each response, and publish summary statistics (mean, std-dev, percentiles), along with the shortest and longest completions, and the exact generation settings. Our analysis reveals significant inter- and intra-model variability in response lengths (even under identical generation settings), as well as model-specific behaviors and occurrences of partial text degeneration in only subsets of responses. CASTILLO enables the development of predictive models for proactive scheduling and provides a systematic framework for analyzing model-specific generation behaviors. We publicly release the dataset and code to foster research at the intersection of generative language modeling and systems.

[Arxiv](https://arxiv.org/abs/2505.16881)