# # 基于LLM的搜索设计用于删除纠错码

发布时间：2025年04月01日

`其他` `信息论` `纠错码`

> LLM-Guided Search for Deletion-Correcting Codes

# 摘要

> 寻找最大尺寸的删除纠错码是一个存在70多年的难题，即使是单个删除的情况也不例外。本文提出了一种全新的构建删除纠错码的方法。我们通过根据优先级函数贪心地添加最高优先级的序列来构建码，其中码是由满足特定约束条件的序列组成的集合。为了找到优秀的优先级函数，我们采用了FunSearch——Romera等人于2024年提出的一种基于大语言模型（LLM）引导的进化搜索工具。FunSearch通过迭代生成、评估和优化优先级函数来构建大规模删除纠错码。

对于单个删除的情况，我们的进化搜索发现的函数能够构建出与已知最大尺寸相匹配的码，达到了最大尺寸的Varshamov-Tenengolts码的规模（尽管最大尺寸未知），并以等效形式独立重新发现了它们。对于两个删除的情况，我们找到了能够构建出长度为【数学公式】\( n = 12, 13 \)和\( 16 \)【数学公式】的码的函数，这些码具有新的最佳已知尺寸，从而建立了改进的下界。

这些结果不仅展示了LLM引导的搜索在信息论和码设计中的巨大潜力，更标志着此类方法首次成功应用于纠错码的构建，为这一领域开辟了全新的研究方向。

> Finding deletion-correcting codes of maximum size has been an open problem for over 70 years, even for a single deletion. In this paper, we propose a novel approach for constructing deletion-correcting codes. A code is a set of sequences satisfying certain constraints, and we construct it by greedily adding the highest-priority sequence according to a priority function. To find good priority functions, we leverage FunSearch, a large language model (LLM)-guided evolutionary search proposed by Romera et al., 2024. FunSearch iteratively generates, evaluates, and refines priority functions to construct large deletion-correcting codes. For a single deletion, our evolutionary search finds functions that construct codes which match known maximum sizes, reach the size of the largest (conjectured optimal) Varshamov-Tenengolts codes where the maximum is unknown, and independently rediscover them in equivalent form. For two deletions, we find functions that construct codes with new best-known sizes for code lengths \( n = 12, 13 \), and \( 16 \), establishing improved lower bounds. These results demonstrate the potential of LLM-guided search for information theory and code design and represent the first application of such methods for constructing error-correcting codes.

[Arxiv](https://arxiv.org/abs/2504.00613)