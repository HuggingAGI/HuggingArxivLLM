# # 标题
在控制维度扩展的情况下，大型语言模型的向量对人类阅读时间和fMRI数据的预测效果较差。

发布时间：2025年05月17日

`LLM理论` `认知科学` `人工智能`

> Vectors from Larger Language Models Predict Human Reading Time and fMRI Data More Poorly when Dimensionality Expansion is Controlled

# 摘要

> 大型语言模型（LLMs）引人注目的语言能力使其被推荐为人类句子处理的模型。一些研究推测，语言模型（LMs）在上下文中预测单词能力的提升，会使其对心理测量数据的拟合程度持续改进（Wilcox et al., 2023）。这表明，LLM架构中的某些元素，如对上下文的真实关注以及预测即将出现单词的独特目标，反映了人类句子处理机制的架构。然而，随着模型规模的扩大，研究发现这种扩展关系会反转（Oh和Schuler，2023）。当使用单词预测概率（作为信息论上的意外度）作为预测因子时，这种反转尤为明显。其他研究利用不同规模LLMs的完整向量进行分析，仍显示出正向扩展（Schrimpf et al., 2021），但并未控制来自更大LLMs向量中预测因子数量的增加。本研究在控制了这一变量后，利用完整LLM向量评估LLM扩展。结果显示反向扩展成立，表明预测人类阅读时间和脑成像数据的不足可能源于LLMs与人类句子处理机制之间存在重大不一致，且这种不一致随着模型规模的增大而加剧。

> The impressive linguistic abilities of large language models (LLMs) have recommended them as models of human sentence processing, with some conjecturing a positive 'quality-power' relationship (Wilcox et al., 2023), in which language models' (LMs') fit to psychometric data continues to improve as their ability to predict words in context increases. This is important because it suggests that elements of LLM architecture, such as veridical attention to context and a unique objective of predicting upcoming words, reflect the architecture of the human sentence processing faculty, and that any inadequacies in predicting human reading time and brain imaging data may be attributed to insufficient model complexity, which recedes as larger models become available. Recent studies (Oh and Schuler, 2023) have shown this scaling inverts after a point, as LMs become excessively large and accurate, when word prediction probability (as information-theoretic surprisal) is used as a predictor. Other studies propose the use of entire vectors from differently sized LLMs, still showing positive scaling (Schrimpf et al., 2021), casting doubt on the value of surprisal as a predictor, but do not control for the larger number of predictors in vectors from larger LMs. This study evaluates LLM scaling using entire LLM vectors, while controlling for the larger number of predictors in vectors from larger LLMs. Results show that inverse scaling obtains, suggesting that inadequacies in predicting human reading time and brain imaging data may be due to substantial misalignment between LLMs and human sentence processing, which worsens as larger models are used.

[Arxiv](https://arxiv.org/abs/2505.12196)