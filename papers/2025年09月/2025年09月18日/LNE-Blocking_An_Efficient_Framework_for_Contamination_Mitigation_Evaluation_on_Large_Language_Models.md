# LNE-Blocking：大型语言模型污染缓解评估的高效框架

发布时间：2025年09月18日

`LLM应用` `基础理论`

> LNE-Blocking: An Efficient Framework for Contamination Mitigation Evaluation on Large Language Models

# 摘要

> 在大型语言模型（LLMs）的开发过程中，数据污染问题如今几乎难以避免——训练数据常会整合各类评估基准数据集，即便这并非有意为之。这一问题进而导致LLMs的公平评估变得棘手。为此，我们未选择构建难度极大的无污染数据集，而是提出全新框架	extbf{LNE-Blocking}，旨在从可能存在数据泄露的数据集上恢复模型受污染前的性能。该框架包含两个核心组件：污染检测与干扰操作。针对提示词，框架首先通过污染检测方法	extbf{LNE}评估模型的污染程度，随后据此调整干扰操作	extbf{Blocking}的强度，以诱导模型生成非记忆化的回答。作为首个能高效恢复模型贪婪解码性能的框架，它在多个存在潜在泄露风险的数据集上表现优异，且在不同模型、不同数据污染程度下均能稳定实现性能恢复。我们已在https://github.com/RuijieH/LNE-Blocking开源代码，以期推动相关研究。

> The problem of data contamination is now almost inevitable during the development of large language models (LLMs), with the training data commonly integrating those evaluation benchmarks even unintentionally. This problem subsequently makes it hard to benchmark LLMs fairly. Instead of constructing contamination-free datasets (quite hard), we propose a novel framework, \textbf{LNE-Blocking}, to restore model performance prior to contamination on potentially leaked datasets. Our framework consists of two components: contamination detection and disruption operation. For the prompt, the framework first uses the contamination detection method, \textbf{LNE}, to assess the extent of contamination in the model. Based on this, it adjusts the intensity of the disruption operation, \textbf{Blocking}, to elicit non-memorized responses from the model. Our framework is the first to efficiently restore the model's greedy decoding performance. This comes with a strong performance on multiple datasets with potential leakage risks, and it consistently achieves stable recovery results across different models and varying levels of data contamination. We release the code at https://github.com/RuijieH/LNE-Blocking to facilitate research.

[Arxiv](https://arxiv.org/abs/2509.15218)