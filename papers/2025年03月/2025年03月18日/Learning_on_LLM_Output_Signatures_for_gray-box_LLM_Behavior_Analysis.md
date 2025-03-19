# 基于 LLM 输出特征的灰盒行为分析学习研究

发布时间：2025年03月18日

`LLM应用

摘要讨论了大型语言模型（LLMs）在数据污染和幻觉检测中的应用，提出了一种新的灰盒分析方法，利用完整的输出签名（LOS）来改进检测技术。这种方法属于LLM的应用层面，专注于如何利用LLM的输出进行分析和改进，而不是探讨其理论基础或作为智能体的行为。因此，分类为LLM应用。` `模型安全` `模型分析`

> Learning on LLM Output Signatures for gray-box LLM Behavior Analysis

# 摘要

> 大型语言模型（LLMs）已广泛应用，但对其行为的理解仍有限，特别是在数据污染和幻觉检测方面。近期提出的探针技术虽能通过激活分析提供见解，但受限于“白盒”访问需求，而实际中难以实现。现有的“灰盒”方法通常仅分析序列中实际标记的概率，使用简单的任务特定启发式，忽视了每个处理步骤中完整标记分布的丰富信息。为解决这些限制，我们提出灰盒分析应利用LLMs的完整可观测输出，包括标记概率和完整分布序列——我们将其统称为LOS（LLM输出签名）。为此，我们开发了一种基于Transformer的方法来处理LOS，该方法在理论上保证对现有技术的近似，同时支持更细致的分析。在灰盒设置下，我们的方法在幻觉和数据污染检测中表现优异，显著超越现有基线。此外，其在数据集和模型间的迁移能力表明，LOS捕获了LLM行为中的基本模式。我们的代码可在以下位置获取：https://github.com/BarSGuy/LLM-Output-Signatures-Network。

> Large Language Models (LLMs) have achieved widespread adoption, yet our understanding of their behavior remains limited, particularly in detecting data contamination and hallucinations. While recently proposed probing techniques provide insights through activation analysis, they require "white-box" access to model internals, often unavailable. Current "gray-box" approaches typically analyze only the probability of the actual tokens in the sequence with simple task-specific heuristics. Importantly, these methods overlook the rich information contained in the full token distribution at each processing step. To address these limitations, we propose that gray-box analysis should leverage the complete observable output of LLMs, consisting of both the previously used token probabilities as well as the complete token distribution sequences - a unified data type we term LOS (LLM Output Signature). To this end, we develop a transformer-based approach to process LOS that theoretically guarantees approximation of existing techniques while enabling more nuanced analysis. Our approach achieves superior performance on hallucination and data contamination detection in gray-box settings, significantly outperforming existing baselines. Furthermore, it demonstrates strong transfer capabilities across datasets and LLMs, suggesting that LOS captures fundamental patterns in LLM behavior. Our code is available at: https://github.com/BarSGuy/LLM-Output-Signatures-Network.

[Arxiv](https://arxiv.org/abs/2503.14043)