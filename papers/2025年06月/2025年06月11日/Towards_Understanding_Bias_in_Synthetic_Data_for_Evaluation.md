# # 理解用于评估的合成数据中的偏见之路

发布时间：2025年06月11日

`LLM应用` `信息检索` `合成数据`

> Towards Understanding Bias in Synthetic Data for Evaluation

# 摘要

> 测试集合在评估信息检索（IR）系统中扮演着关键角色。然而，为这些测试集合创建多样化的用户查询仍然充满挑战，而获取相关性判断（用于评估检索文档与查询匹配程度）往往成本高昂且耗时费力。近期，利用大型语言模型（LLMs）生成合成数据在多个领域引起了广泛关注。尽管先前的研究已经尝试通过LLMs生成合成查询或文档来优化排名模型，但使用LLMs创建合成测试集合仍是一个相对未被深入探索的领域。先前研究~\cite{rahmani2024synthetic}表明，合成测试集合在系统评估方面具有潜力，然而，这一结论仍需进一步验证。本文将全面探讨基于LLMs构建的合成测试集合的可靠性，涵盖合成查询、标签或两者的生成过程。特别地，我们深入分析了在评估中使用这些测试集合时可能出现的潜在偏见。首先，我们通过实证展示了评估结果中存在此类偏见，并探讨了其对系统评估可能产生的影响。随后，我们借助线性混合效应模型进一步验证了这些偏见的存在。研究发现，尽管合成测试集合评估结果中的偏见可能对计算系统的绝对性能产生显著影响，但在比较不同系统的相对性能时，其影响可能相对较小。相关代码和数据已开放获取，链接为：https://github.com/rahmanidashti/BiasSyntheticData.

> Test collections are crucial for evaluating Information Retrieval (IR) systems. Creating a diverse set of user queries for these collections can be challenging, and obtaining relevance judgments, which indicate how well retrieved documents match a query, is often costly and resource-intensive. Recently, generating synthetic datasets using Large Language Models (LLMs) has gained attention in various applications. While previous work has used LLMs to generate synthetic queries or documents to improve ranking models, using LLMs to create synthetic test collections is still relatively unexplored. Previous work~\cite{rahmani2024synthetic} showed that synthetic test collections have the potential to be used for system evaluation, however, more analysis is needed to validate this claim. In this paper, we thoroughly investigate the reliability of synthetic test collections constructed using LLMs, where LLMs are used to generate synthetic queries, labels, or both. In particular, we examine the potential biases that might occur when such test collections are used for evaluation. We first empirically show the presence of such bias in evaluation results and analyse the effects it might have on system evaluation. We further validate the presence of such bias using a linear mixed-effects model. Our analysis shows that while the effect of bias present in evaluation results obtained using synthetic test collections could be significant, for e.g.~computing absolute system performance, its effect may not be as significant in comparing relative system performance. Codes and data are available at: https://github.com/rahmanidashti/BiasSyntheticData.

[Arxiv](https://arxiv.org/abs/2506.10301)