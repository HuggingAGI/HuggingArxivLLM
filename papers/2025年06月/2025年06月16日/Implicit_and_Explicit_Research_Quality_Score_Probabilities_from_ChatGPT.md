# ChatGPT 的隐式与显式研究质量评分概率分析

发布时间：2025年06月16日

`LLM应用` `学术出版` `质量评估`

> Implicit and Explicit Research Quality Score Probabilities from ChatGPT

# 摘要

> ChatGPT在大多数领域对期刊文章的质量评分与人类判断的相关性比一些基于引用的指标更强。通过对多个ChatGPT评分进行平均，可以改善结果，这显然利用了其内部的概率模型。为了更好地利用这些概率，本文测试了两种新策略：要求评分的百分比可能性和从响应中提取替代标记的概率。随后，利用这些概率估计计算加权平均分数。两种策略均使用ChatGPT 4o-mini在五次迭代中对提交给2021年英国研究卓越框架（REF 2021）的96,800篇文章进行了评估，采用部门级平均的REF2021质量评分作为文章质量的代理指标。数据针对34个基于领域的REF评估单位进行了分别分析。对于第一种策略，明确要求评分百分比可能性的表格显著降低了评分的价值（与代理质量指标的相关性较低）。相比之下，评分标记概率的加权平均值略微提高了与质量代理指标的相关性，且这些概率合理准确地反映了ChatGPT的输出。因此，标记概率方法是按研究质量对文章进行排名的最准确方法，同时成本也低于类似的ChatGPT策略。

> The large language model (LLM) ChatGPT's quality scores for journal articles correlate more strongly with human judgements than some citation-based indicators in most fields. Averaging multiple ChatGPT scores improves the results, apparently leveraging its internal probability model. To leverage these probabilities, this article tests two novel strategies: requesting percentage likelihoods for scores and extracting the probabilities of alternative tokens in the responses. The probability estimates were then used to calculate weighted average scores. Both strategies were evaluated with five iterations of ChatGPT 4o-mini on 96,800 articles submitted to the UK Research Excellence Framework (REF) 2021, using departmental average REF2021 quality scores as a proxy for article quality. The data was analysed separately for each of the 34 field-based REF Units of Assessment. For the first strategy, explicit requests for tables of score percentage likelihoods substantially decreased the value of the scores (lower correlation with the proxy quality indicator). In contrast, weighed averages of score token probabilities slightly increased the correlation with the quality proxy indicator and these probabilities reasonably accurately reflected ChatGPT's outputs. The token probability approach is therefore the most accurate method for ranking articles by research quality as well as being cheaper than comparable ChatGPT strategies.

[Arxiv](https://arxiv.org/abs/2506.13525)